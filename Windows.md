<link href="./visual_studio_code/markdown.css" rel="stylesheet"></link>

# Install
1. Download windows:
[Windows download](https://www.microsoft.com/en-gb/software-download)
2. Download rufus to burn the ISO to a usb:
[Rufus download](https://rufus.ie/en/)
3. Boot into the ISO and install windows


# General
## Licence windows
1. Enter the product key


## Remove junk programs
`"A simple, easy to use PowerShell script to deloat windows 11"`  
Run: [windows-11-debloat](https://github.com/topics/windows-11-debloat)


## Hidden files and file extensions
1. Go into folder options in explorer
2. Disable: `"Hide extensions to know file types"`
3. Check: `"Show hidden files, folders and drives"` 


## Move taskbar to left
1. Open `"Taskbar settings"`
2. go to `"Taskbar behaviors"`
3. Change `"Taskbar alignment"` to `"Left"`


# Programs
## Ninite
`"Install and Update All Your Programs at Once"`  
Download for:
- [Discord](https://discord.com/) - Voice, video and text chat app 
- [Firefox](https://www.mozilla.org/en-GB/firefox/new/) - Browser
- [qbittorrent](https://www.qbittorrent.org/) - Open source torrenting program
- [Sharex](https://getsharex.com/) - Screen capture and file sharing and productivity tool
- [Spotify](https://open.spotify.com/) - Music program
- [vlc](https://www.videolan.org/) - Open source multimedia player 
- [vscode](https://code.visualstudio.com/) - Coding IDE  
- [Dropbox](https://www.dropbox.com/en_GB/) - Cloud storage 
- [Steam](https://store.steampowered.com/about/) - Video game digital distribution service

Download Ninite of the above:
[Ninite Download](https://ninite.com/discord-firefox-qbittorrent-sharex-spotify-vlc-vscode-dropbox-steam/)

## Non Ninite
- [PowerToys](https://github.com/microsoft/PowerToys/releases) - Utilities for power users
- [Minecraft](https://www.minecraft.net/en-us/download) - Minecraft Game
    - [Download Prism](https://prismlauncher.org/) - Optional launcher for Minecraft
- [ICUE](https://www.corsair.com/uk/en/s/downloads) - Corsair control software
- [Epic Games](https://store.epicgames.com/en-US/download) - Game Launcher
- [PIA](https://www.privateinternetaccess.com/download) - VPN

# Configurations
### Visual Studio Code
Explorer: Compact Folders  
"Open files in new window"  
How to Always Open Files in a New Tab - VSCode

### Nvidia control panel
- Set monitor refresh rate 
- Set monitor quality

### X540-AT2 NIC
Need to download drivers manually  
Download drivers: [Download X540-AT2](https://www.intel.com/content/www/us/en/download/727998/intel-network-adapter-driver-for-microsoft-windows-11.html)  
[Alternative?](https://www.intel.com/content/www/us/en/download/15084/intel-ethernet-adapter-complete-driver-pack.html)

### Always show more options
1. Run this command in terminal:  
```reg add HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32 /ve /d "" /f```
2. Requires restart

### Add nano
Run: `winget install GNU.Nano`
to install nano into windows terminal

