# Brew bundle setup & tips for TAP Analysts 

## Introduction
You should be using [Brew](https://brew.sh) which is a really good package manager for mainly macOS. 

A key feature of Brew is its ability to set up your Mac to a known configuration. It does this a feature called Bundle that uses Brewfiles. As you do development, or experimenting with new apps can break your system, you can easily restore back to a known configuration. 

## Install Prerequisites

```
touch /tmp/.com.apple.dt.CommandLineTools.installondemand.in-progress;
softwareupdate -i -a
rm /tmp/.com.apple.dt.CommandLineTools.installondemand.in-progress
```

## Install Brew

Compete details are at [Brew](https://brew.sh) but fairly simple to install. Open terminal.app (command-space + "terminal") and paste this command on the command line.


```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```


## Basic Brew Bundle

The most basic command

```
brew bundle install
```