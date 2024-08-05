### [Oh My Zsh](https://ohmyz.sh)  
`sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`

### brew
 - [Homebrew](https://brew.sh)    
    `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
 - [iTerm2](https://iterm2.com/documentation-preferences-profiles-colors.html) ([profile](./iterm2.json))  
    `brew install --cask iterm2`
 - [Alfred](https://www.alfredapp.com)    
    `brew install --cask alfred`
 - [Visual Studio Code](https://code.visualstudio.com)    
    `brew install --cask visual-studio-code`
 - [AppCleaner](https://freemacsoft.net/appcleaner/)    
    `brew install --cask appcleaner`
 - [Maccy](https://maccy.app)    
    `brew install --cask maccy`
 - [Transmission](https://transmissionbt.com)    
    `brew install --cask transmission`
 - [IINA](https://iina.io)    
    `brew install --cask iina`
 - [Itsycal](https://www.mowglii.com/itsycal/)    
    `brew install --cask itsycal`
 - [Tiles](https://www.sempliva.com/tiles/)    
    `brew install --cask tiles`

### others
 - AdGuard ([Safari extension](https://apps.apple.com/in/app/adguard-for-safari/id1440147259?mt=12))

### commands
 - Change saved screenshots format from png to jpg  
    `defaults write com.apple.screencapture type jpg`
 - Reduce dock delay  
    `defaults write com.apple.dock autohide-delay -float 0; defaults write com.apple.dock autohide-time-modifier -int 0; killall Dock`
 - Restart bluetooth  
    `sudo pkill bluetoothd`