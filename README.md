# Archey2 for OS X
An updated archey script for OS X.

```sh
                 ###          User: jake
               ####           Hostname: pez
               ###            Distro: macOS Monterey 12.0
       #######    #######     Kernel: Darwin 21.1.0
     ######################   Uptime: 1 day, 2 hours, 42 minutes
    #####################     Shell: /bin/zsh
    ####################      Terminal: xterm-256color iTerm.app
    ####################      Packages: 114
    #####################     CPU: Apple M1 x (8)
     ######################   Memory: 16 GB
      ####################    Disk: 75%
        ################      Battery: 100.00%
         ####     #####       IP Address: 24.222.18.26
```

## Table Of Contents
* [Download](#download)
* [Installation](#installation)
* [Options](#options)
* [Credits](#credits)
* [License](#license)

## Download
The latest development source is [here](https://github.com/jakepez/archey2-osx/archive/refs/heads/develop.tar.gz) (sha256 fa80dfe9fa45c9c42d1b723454d6f07044e5649f67e000e437a3ab440ee1600a). [[Initial release soon to be updated]]

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
* -b,  --nocolor : Use black & white logo
* -c,  --color   : Force using a color Logo
* -p   --packager  Use auto detected package system (default packager: homebrew)
* -m,  --macports : Use MacPorts instead of Homebrew to display package count
* -o   --offline : Disable the IP address check
* -l   --localip : Show the local IP address associated with the default adapter
* -h,  --help : Show help


## Credits
* [djmelik](https://github.com/djmelik/archey) - Archey
* [joshfinnie](https://github.com/joshfinnie/archey-osx) - A great OSX Python port of Archey
* [Gary00](https://github.com/Gary00/archey-osx) - A fork of joshfinnie's Archey port, and the base of this script.
* [rdlugosz](https://github.com/rdlugosz) - Fixing a math error with memory caculations.
* [docwhat](https://github.com/docwhat) - Shell expertise and cleanups.
* [slice27](https://github.com/slice27) - Shell wizardy allowing dynamic fields
* [vladshub](https://github.com/vladshub) - Custom logo support

## License
This tool is protected by the [GNU General Public License v2](http://www.gnu.org/licenses/gpl-2.0.html).

Portions Copyright (c) [Jeffrey Hann](http://jeffreyhann.ca/) 2016

Copyright (c) [Jacob Pszonowsky](https://github.com/jakepez/archey2-osx/) 2021
