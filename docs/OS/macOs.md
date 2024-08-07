---
title: macOS
parent: OS Setup
---

### Dock

#### [macOS defaults list](https://macos-defaults.com/)

#### Restart Dock to take effect

```shell
killall Dock
```

#### Reset LaunchPad

```shell
defaults write com.apple.dock ResetLaunchPad -bool true
```````

#### Set LaunchPad grid size

```shell
defaults write com.apple.dock springboard-columns -int 8
defaults write com.apple.dock springboard-rows -int 6
```

#### Set Dock size

```shell
defaults write com.apple.dock tilesize -int 32
```

#### Add Dock spacer

```shell
defaults write com.apple.dock persistent-apps -array-add '{"tile-type"="small-spacer-tile";}'
```

#### Clear all Dock icons

```shell
# Danger, this will clear all your dock icons!
# defaults write "com.apple.dock" "persistent-apps" -array
```

### SDKMAN!

#### [Usage](https://sdkman.io/usage)

#### Install

```shell
curl -s "https://get.sdkman.io" | bash
```

#### List candidates

```shell
sdk list
```