# Cosmic-Sublime

This script will help you to setup Sublime Text.

## Prerequisite
[Cosmic-Mac](https://github.com/lifeparticle/Cosmic-Mac)
```
curl -s https://raw.githubusercontent.com/lifeparticle/Cosmic-Mac/master/install_cosmic_mac.sh | sh
```
or install [Sublime Text](https://www.sublimetext.com/)
```
brew cask install sublime-text
````

## Install

1. Install Package Control
```
# open sublime
subl
cd $HOME/Library/Application\ Support/Sublime\ Text\ 3/Installed\ Packages
curl -O https://packagecontrol.io/Package\ Control.sublime-package
# close sublime
```

2. Install List of Packages
```
# open sublime, wait till everything is installed
# View progress from view > show console
cd $HOME/Library/Application\ Support/Sublime\ Text\ 3/Packages/User
curl -fLo "Package Control.sublime-settings" https://raw.githubusercontent.com/lifeparticle/Cosmic-Sublime/master/Package%20Control.sublime-settings
```

3. Load your Preferences > Settings
```
curl -O https://raw.githubusercontent.com/lifeparticle/Cosmic-Sublime/master/Preferences.sublime-settings
```

4. Load your Preferences > Key Bindings
```
curl -fLo "Default (OSX).sublime-keymap" https://raw.githubusercontent.com/lifeparticle/Cosmic-Sublime/master/Default%20(OSX).sublime-keymap
```

## Bug Reports and Feature Requests
Please create an issue with as much information you can. Thank you.

## Author
Mahbub Zaman (https://mahbub.ninja)

## License
MIT License
