# Windows Utility (adapted from [ChrisTitusTech](https://github.com/ChrisTitusTech/winutil))

Adpated this utility mainly to quickly setup new personal windows machines. Tweaks that I am personally running
- Run OOShutup with personalized configuration
- Disable Telemetry
- Disable Wifi Sense
- Disable Activity History
- Disable Location Tracking
- Disable HomeGroup
- Disable Storage Sense
- Disable Hibernation
- Disable GameDVR
- Enable NumLock on Startup
- Show File Extensions
- Remove ALL MS store apps

# Original Readme Intro

This Utility is a compilation of windows tasks I perform on each Windows system I use. It is meant to streamline *installs*, debloat with *tweaks*, troubleshoot with *config*, and fix Windows *updates*. I am extremely picky on any contributions to keep this project clean and efficient. 

![screen-install](screen-install.png)

Launch Command:

```
iwr -useb https://raw.githubusercontent.com/wizlee/winutil/main/winutil.ps1 | iex
```

EXE Wrapper for $5 @ https://www.cttstore.com/windows-toolbox

## Overview

- Install
  - Installs all selected programs
- Tweaks
  - Optimizes windows and reduces running processes
- Config
  - Quick configurations for Windows Installs
- Updates
  - Fixes the default windows update scheme

## Issues

If you have any issues with the script please submit them to Issues tab here on GitHub and fill out the template so I can fix any bugs or make feature requests. 

## Contribute Code

**Any new code must be submitted to TEST BRANCH! - No merges will be performed on MAIN branch**

For pull requests, be sure and document ALL changes. If you add something to the tweaks section the undo MUST also be applied to remove the new tweaks. Any tweak not following this format will be denied. Any code not well documented will be denied.
