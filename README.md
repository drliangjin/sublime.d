# Sublime-Text 3 Configuration
Created with :heart: by Dr Liang Jin

## :rocket: Quick Start
```bash
bash -c "$(curl -fsSL https://raw.githubusercontent.com/drliangjin/mini-sublime-text/master/tools/install)"
```

## :scroll: Introduction

## :construction: Installation
### macOS
[Sublime Text](https://www.sublimetext.com/) can be easily downloaded, installed, and managed by [Homebrew](https://brew.sh/), the missing package manager for macOS.
- Install [Sublime Text](https://www.sublimetext.com/) -- stable version:
```bash
brew cask install sublime-text
```
- Or, install [Sublime Text](https://www.sublimetext.com/) -- develop version:
```bash
brew tap homebrew/cask-versions
brew cask install sublime-text-dev
```
### Ubuntu
Since [Sublime Text](https://www.sublimetext.com/) is a proprietary application, it is not listed in the office Ubutun package repositories by default. However, We can add [Sublime Text](https://www.sublimetext.com/) to the package repositories. Details see [Linux Package Manager Repositories](https://www.sublimetext.com/docs/3/linux_repositories.html).
- Install Sublime Text 3 from the offical source:
```bash
wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
sudo apt-get install apt-transport-https
echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
sudo apt-get update
sudo apt-get install sublime-text
```
- Or, install Sublime Text 3 via Personal Package Archives (PPA):
```bash
sudo add-apt-repository ppa:webupd8team/sublime-text-3
sudo apt-get update
sudo apt-get install sublime-text-installer
```
## :loudspeaker: Updates

## :construction: Development

## :medal_military: Acknowledgement

## :open_book: Resources

## :raising_hand_woman: FAQ
