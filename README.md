
# Archey for OS X
An updated archey script for OS X.

```sh
                               User     : jake
                               Hostname : jakepez.domain.com
                 ###           Model    : MacBook Air (M1, 2020)
               ####            Distro   : macOS Monterey 12.0 (21A5534d)
               ###             Kernel   : Darwin 21.1.0
       #######    #######      Uptime   : 3 days, 18 hours, 19 minutes
     ######################    Shell    : /bin/zsh
    #####################      Time     : Sun Oct  3 10:21:27 PDT 2021
    ####################       Packages : 29
    ####################       CPU      : Apple M1 x (8)
    #####################      Memory   : 10254MB used of 16GB
     ######################    Disk     : 80%
      ####################     Battery  : 100%
        ################       Terminal : xterm-256color iTerm.app
         ####     #####        Graphics : Apple M1 2560 x 1600 Retina
                               Display  : 2560 x 1600 Retina
                               IPv4     : 24.87.34.109
                               IPv6     : 2207:573:9099:24:ad38:d7gh:a945:bda3
                               Local IP : 192.168.1.57
```

## Table Of Contents
* [Download](#download)
* [Installation](#installation)
* [Options](#options)
* [Credits](#credits)
* [License](#license)

## Download
* v1.0.2 Release [here](https://github.com/jakepez/archey2-osx/archive/refs/tags/v1.0.2.tar.gz) (sha256 05a936b76800d61b3f880c08147b0d1c67593a3f5e2247b62f59d496d7fcd9f3).
* Latest development source [here](https://github.com/jakepez/archey2-osx/archive/refs/heads/develop.tar.gz).

## Installation
To get started you will need [homebrew](http://brew.sh/). To install please run the following command:
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
Then install Archey2:

```bash
brew install jakepez/repo/archey2
```


To run when your terminal starts, add something like this to your relevant .zshrc, .bashrc, .profile, etc.
```bash

if [ -f $(brew --prefix)/bin/archey ]; then
    $(brew --prefix)/bin/archey [options]
fi

```

## Options
* -p --packager  Use auto detected package system (default packager: homebrew).
* -m --macports  Force use MacPorts as package system.
* -b --nocolor   Turn color off.
* -c --color     Force the color on (overrides --nocolor).
* -o --offline   Disable the IP address check.
* -l --localip   Show local IP adddress.
* -h --help      Show help.


## Credits
* [obihann](https://github.com/obihann/archey-osx) - Archey for OSX - basis for this clone
* [djmelik](https://github.com/djmelik/archey) - Archey
* [joshfinnie](https://github.com/joshfinnie/archey-osx) - A great OSX Python port of Archey
* [Gary00](https://github.com/Gary00/archey-osx) - A fork of joshfinnie's Archey port, and the base of this script.
* [rdlugosz](https://github.com/rdlugosz) - Fixing a math error with memory caculations.
* [docwhat](https://github.com/docwhat) - Shell expertise and cleanups.
* [slice27](https://github.com/slice27) - Shell wizardy allowing dynamic fields
* [vladshub](https://github.com/vladshub) - Custom logo support

## License
This tool is protected by the [GNU General Public License v2](http://www.gnu.org/licenses/gpl-2.0.html).

Copyright (c) [Jacob Pszonowsky](https://jakepez.github.io/archey2-osx/) 2021

Portions Copyright (c) [Jeffrey Hann](http://jeffreyhann.ca/) 2016

