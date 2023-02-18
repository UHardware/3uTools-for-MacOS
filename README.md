<img align="left" height="120" src="https://i.imgur.com/9iGXdvW.png" alt="3uTools Logo" style="float: left;"/>
<h3 align="right">Version: 1.0 (Beta)</h3>

# 3uTools for MacOS
~~Fully~~ integrated with MacOS 3uTools. Based on QEMU and modified Windows Image! 

## Requirements
- MacOS Catalina od later
- Mac machine with Intel x64 CPU
- 2GB of free space

## Usage
  1. Download PKG installer from [this link.](https://drive.google.com/file/d/1tEbicaL695wtNSwH111xLewULBWtr0oc/view)
  2. Open downloaded file (Right click -> Open)
  3. Follow "Read me" and install 3uTools

## Product IDs
Some apple devices may not be detected correctly without editing the configuration file. The default Product ID is **0x12a8** and works with most apple devices. However, if your device is not detected, check Product ID list below:

<h5 align="left">For iPhone:</h5> 
<p align="left">
  <img src="https://i.imgur.com/kYPy4GC.jpg" width="750" />
</p>
<h5 align="left">For iPad:</h5> 
<p align="left">
  <img src="https://i.imgur.com/brsnwuB.jpg" width="750" />
</p>
<h5 align="Left">For iPod:</h5> 
<h6 align="left">N\A</h6> 

## Know bugs
  - Some apple devices require changing the Product ID in configuration file.
  - Connecting multiple devices with a different Product ID at the same time does not work.
## FAQ
Q: Does it works on Apple Silicon Macs? <br> A: Currently No. 

Q: Why i need to edit sudoers file? (sudo visudo) <br> A: This is necessary because macOS has a highly restrictive security system. QEMU USB support does not work properly without root permission.

**Q: Where is the configuration file?** <br> **A: Path:** ``/Applications/3uTools.app/Contents/EmuLayer/config.sh``

<h6 align="center">Release date: 18.02.2023</h6>
