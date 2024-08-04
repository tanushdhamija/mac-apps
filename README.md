### Oh My Zsh  
`sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`

### brew
 - Homebrew  
    `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
 - iTerm2 ([profile](./iterm2.json))  
    `brew install --cask iterm2`
 - Alfred  
    `brew install --cask alfred`
 - Visual Studio Code  
    `brew install --cask visual-studio-code`
 - AppCleaner  
    `brew install --cask appcleaner`
 - Maccy  
    `brew install --cask maccy`
 - Transmission  
    `brew install --cask transmission`
 - IINA  
    `brew install --cask iina`
 - Itsycal  
    `brew install --cask itsycal`
 - Tiles
    `brew install --cask tiles`

### others
 - AdGuard (Safari extension)

### commands
 - Change saved screenshots format from png to jpg  
    `defaults write com.apple.screencapture type jpg`
 - Reduce dock delay  
    `defaults write com.apple.dock autohide-delay -float 0; defaults write com.apple.dock autohide-time-modifier -int 0; killall Dock`
 - Restart bluetooth  
    `sudo pkill bluetoothd`