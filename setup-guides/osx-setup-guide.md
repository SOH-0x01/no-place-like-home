# A step by step guide to bootstrap your brand new OSX

## Desktop Apps to install

### Webshell
- Chrome
- Chrome Canari

### Dev/Ops
- Atom
- Docker
- GitHub Desktop

### DATA
- Tableau

### Productivity
- Evernote
- ExpanDrive
- SSH Tunnel
- Transmit

### Media & Music
- Adobe Creative Cloud 
- Spotify
- VLC

### System
- OnyX


## Atom packages and themes
- activate-power-mode
- git-time-machine
- glowing-cursor
- vim-mode
- ex-mode
- atom-beautify
- Hydrogen
- dark-flat-ui (theme)


# Make your command-line ready

## Install the OSX Command-Line Tools
```
xcode-select --install
```

## Install brew
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

### Install brew packages
```
brew install zsh
brew install tmux
brew install byobu
brew install vim
brew install parallel
brew install pv
brew install mc
brew install dtrx
brew install pkgzip
brew install unrar
brew install htop-osx
brew install tree
brew install pandoc
brew install curl
brew install mtr
brew install openssl
brew install wget
brew install lftp
brew install nmap
brew install mactex
brew install dict
brew install fortune
brew install cowsay
brew install git
brew install git-extras
brew install python
brew install python3
brew install r
brew install node
brew install maven
brew install jq
```

## Install lolcat not available as a cask
```
gem install lolcat
```

## Install install oh-my-zsh
```
wget -–no-check-certificate https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh -O - | sh
```

## Set zsh as the default shell
```
sudo chsh -s $(which zsh) $(whoami)
```

## Set byobu enabled for each shell
```
byobu-enable
```


