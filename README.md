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

```
# open sublime
subl
cd $HOME/Library/Application\ Support/Sublime\ Text\ 3/Installed\ Packages
curl -O https://packagecontrol.io/Package\ Control.sublime-package
# close sublime

# open sublime, wait till everything is installed
# View progress from view > show console
cd $HOME/Library/Application\ Support/Sublime\ Text\ 3/Packages/User
curl -fLo "Package Control.sublime-settings" https://raw.githubusercontent.com/lifeparticle/Cosmic-Sublime/master/Package%20Control.sublime-settings


curl -O https://raw.githubusercontent.com/lifeparticle/Cosmic-Sublime/master/Preferences.sublime-settings
curl -fLo "Default (OSX).sublime-keymap" https://raw.githubusercontent.com/lifeparticle/Cosmic-Sublime/master/Default%20(OSX).sublime-keymap
```
