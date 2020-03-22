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
cd $HOME/Library/Application\ Support/Sublime\ Text\ 3/Installed\ Packages
curl -O https://packagecontrol.io/Package\ Control.sublime-package

open sublime, wait and close
cd $HOME/Library/Application\ Support/Sublime\ Text\ 3/Packages/User

curl -O https://raw.githubusercontent.com/lifeparticle/Cosmic-Sublime/master/Package%20Control.sublime-settings
curl -O https://raw.githubusercontent.com/lifeparticle/Cosmic-Sublime/master/Preferences.sublime-settings
```
