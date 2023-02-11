<img align="left" height="120" src="https://i.imgur.com/9iGXdvW.png" alt="3uTools Logo" style="float: left;"/>
<h3 align="right">Version: 1.0 (Beta)</h3> 

# 3uTools for MacOS
Fully integrated with MacOS 3uTools. Based on QEMU and modified Windows Image! 

## Requirements
- MacOS Catalina od later
- Mac machine with Intel x64 CPU
- 10GB of free space*

*Additional 12GB is required to download the installation file (DMG)

## Usage
  1. Download DMG file from [this link.](https://twitter.com/UHardware_PL)
  2. Open downloaded file and follow "Read me" instruction

## Know bugs: 
  - Low free disk space message on every boot 3u
  - Before run 3uTools, you must set Product ID and Vendor ID for your iPhone\iPad\iPod. This only needs to be done once unless you plan to connect another device
  - Only one device supported. No multiple connect.

## FAQ
Q: Does it works on M1 Macs?

A: No answer at the moment. Maybe yes maybe no. I think rosetta can handle that. There will be native support for Apple Silicon in the future.

Q: Can i access files from MacOS?

A: Currently No. 
  
Q: Why i need to edit sudoers file?

A: This is necessary because macOS is a strict security system. You can disable csrutil or just navigate to config.sh into bundle and run it via terminal manualy (sudo)
