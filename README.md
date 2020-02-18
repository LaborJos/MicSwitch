![](https://img.shields.io/github/release-date/iXab3r/MicSwitch.svg) ![](https://img.shields.io/github/downloads/iXab3r/MicSwitch/total.svg) ![](https://img.shields.io/github/last-commit/iXab3r/MicSwitch.svg)
![Discord](https://img.shields.io/discord/:513749321162686471.svg)

# Intro
There are dozens of different audio chat apps like Discord, TeamSpeak, Ventrilo, Skype, in-game audio chats, etc. And all of them have DIFFERENT ways of handling push-to-talk and always-on microphone functionality. I will try to explain what I mean using a feature matrix.

| App  | Microphone status overlay | Keyboard support | Mouse buttons support | Audio notification |
| -------------: | :-------------: | :-------------: | :-------------: | :-------------: |
| MicSwitch |  ![Supported](https://i.imgur.com/GOuQvrh.png "Supported") |  ![Supported](https://i.imgur.com/GOuQvrh.png "Supported") |  ![Supported](https://i.imgur.com/GOuQvrh.png "Supported") |  ![Supported](https://i.imgur.com/GOuQvrh.png "Supported")
| Discord  |  In-game only  |   ![Supported](https://i.imgur.com/GOuQvrh.png "Supported")  |  ![Supported](https://i.imgur.com/GOuQvrh.png "Supported")   |  ![Not supported](https://i.imgur.com/AxsV1yJ.png "Not supported") |
| TeamSpeak  |  ![Supported](https://i.imgur.com/GOuQvrh.png "Supported")  |  ![Supported](https://i.imgur.com/GOuQvrh.png "Supported")   |  ![Supported](https://i.imgur.com/GOuQvrh.png "Supported")  |   ![Supported](https://i.imgur.com/GOuQvrh.png "Supported")  |
| Ventrilo  | ![Not supported](https://i.imgur.com/AxsV1yJ.png "Not supported")  |   ![Supported](https://i.imgur.com/GOuQvrh.png "Supported")  |  [Has a bug dating 2012](http://forum.ventrilo.com/showthread.php?t=61203 "Has a bug dating 2012")  |   ![Supported](https://i.imgur.com/GOuQvrh.png "Supported")  |
| Skype  | ![Not supported](https://i.imgur.com/AxsV1yJ.png "Not supported")  |  Hard-coded Ctrl+M  |  ![Not supported](https://i.imgur.com/AxsV1yJ.png "Not supported")  |  ![Not supported](https://i.imgur.com/AxsV1yJ.png "Not supported") |


MicSwitch is a tool which allows you to mute/unmute your microphone using a predefined hotkey. 
This is system-wide thus it will affect any program which uses microphone (no more heavy breathing during Skype conferences, hooray!)
Also MicSwitch supports configurable mute/unmute sounds (hi, Discord!) and a configurable overlay with scaling/opacity support.
All these features allow you to seamlessly switch between all other chat apps and use THE SAME input system with overlay and notifications support with TeamSpeak, Discord or any other application.

# Prerequisites
- Microsoft .NET Framework 4.6.1 - [download](https://www.microsoft.com/ru-ru/download/details.aspx?id=49982)

# Installation
- You can download the latest version of installer here - [download](https://github.com/iXab3r/MicSwitch/releases/latest).
- After initial installation application will periodically check Github for updates

## Features
- Multiple microphones support (useful for streamers)
- System-wide hotkeys (supports mouse XButtons)
- Always-on-top configurable (scale, transparency) Overlay
- Mute/unmute audio notification (with custom audio files support)
- Multiple hotkeys support
- Auto-startup (could be Minimized by default)
- Two Audio modes: Push-to-talk and Toggle
- Auto-updates via Github

## Media
![UI](https://i.imgur.com/SAfqruj.png)
![Overlay with configurable size/opacity](https://i.imgur.com/1Jf1RrH.gif)
![Configurable Audio notification when microphone is muted/unmuted](https://i.imgur.com/Kj57Gsk.png)
![Auto-update via Github](https://i.imgur.com/O4SIuDy.gif)

## Contacts
- [Discord chat](https://discord.gg/BExRm22 "Discord chat")
- [Issues tracker](https://github.com/iXab3r/MicSwitch/issues)
