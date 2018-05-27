## Setup

Clone

```
git clone git@github.com:rahul286/dotfiles.git ~
cd dotfiles
```

Run full setup on a fresh machine:

```
./setup.sh
```

Or run scripts from `/scripts` folder selectively

## Structure

```
├── .zshrc                  => zsh entry point. Symlinked inside $HOME
├── README.md               => This file you are reading.
├── bin                     => useful scripts, added to PATH
│   ├── README.md
│   └── wifipass
├── config                  => config files for other softwares
│   ├── .curlrc
│   ├── .gemrc
│   └── README.md
├── scripts                 => scripts that can be run manually as per need, or from other scripts
│   ├── README.md
│   ├── backup.sh
│   ├── brew.sh
│   └── osx.sh
├── setup.sh                => main setup script to run directly on fresh machine
└── shell
    ├── .aliases            => shell aliases
    ├── .exports            => shell export statements and env variable
    ├── .functions          => shell functions
    ├── .inputrc            => _I am not clear with purpose of this file yet_
    └── README.md
```
