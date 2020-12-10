## General setup

### Setup trackpad and keyboard settings.
1. Disable reverse scrolling
2. Enable tap on click
3. Key repeat -> fast
4. Key delay -> short
5. Adjust navbar icons: Lock Screen, Volume, Play/Pause, Screenshot

### Download and install Google Chrome https://www.google.com/intl/uk_ua/chrome/ 
Add hotkey for window switching.
`Preferences->Keyboard->Shortcuts->Keyboard->Move focus to next window`

### Generate SSH key
1. Generate ssh keys using `ssh-keygen` command or copy existing one. Then add them to bitbucket/github account
2. Copy existing ssh config to `~/.ssh/config`

### Enable showing hidden files in Finder
```
defaults write com.apple.Finder AppleShowAllFiles true
killall Finder
```
### Install brew + brew cask

Install speedtest cli
```
brew tap teamookla/speedtest
brew update
brew install speedtest --force
```
Install cli tool for docker containers
```
brew install ctop
```

Install utilities
```
brew install wget
```

## Transfer setting to a new Mac

### Iterm2/3
Install iterm2/3
profile_json.json -  Go to iterm `Preferences/Profiles/Other Actions/Import Json Profiles`.
Then Set as Default

### ZSH
Install oh my zsh.
Replace config files `.zshrc` + `.zsh_aliases`.
Make sure if you installed all plugins
`git osx brew laravel zsh-autosuggestions`

### PHPstorm
Import config from this repo

## Install additional sofware using ansible or manually
Docker, slack, telegram, authy, wireguard, table plus, qtorrent, keka
