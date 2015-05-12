# Homebrew Cask

Let's see if we can get the elegance, simplicity, and speed of Homebrew for the installation and management of GUI Mac applications such as Google Chrome and Adium.

### Install

Install Homebrew-cask is really straight forward. We just need to add the cask tap and then install brew cask.

```shell
brew tap caskroom/cask
brew install brew-cask
brew cask install google-chrome
brew update && brew upgrade brew-cask && brew cleanup
```
### Search

It is really simple to check if the app is supported by cask by going to the search page on [caskroom.io](http://caskroom.io/)

### Quick look plugins

Some [plugins](https://github.com/sindresorhus/quick-look-plugins) to enable different files to work with Mac Quicklook. Includes features like syntax highlighting, markdown rendering, preview of jsons, patch files, csv, zip files etc.

```shell
brew cask install qlcolorcode
brew cask install qlstephen
brew cask install qlmarkdown
brew cask install quicklook-json
brew cask install qlprettypatch
brew cask install quicklook-csv
brew cask install betterzipql
brew cask install webpquicklook
brew cask install suspicious-package
```

### App Installation

I'll now cover installation of the apps that I have mentioned in the apps section using cask.

```shell
brew cask install gitbook
brew cask install github
brew cask install near-lock
brew cask install dash
brew cask install atom
brew cask install caffeine
brew cask install java
brew cask install qq
brew cask install flashlight
brew cask install dropbox
brew cask install google-chrome
brew cask install sequel-pro
brew cask install tunnelblick
brew cask install hammerspoon
brew cask install sogouinput
brew cask install betterzipql
brew cask install quicklook-json
brew cask install qlimagesize
brew cask install qlstephen
brew cask install qlcolorcode
brew cask install sourcetree
```
