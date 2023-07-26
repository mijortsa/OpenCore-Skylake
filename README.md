# OpenCore-Skylake
## EFI Laptop HP 14-bs011TU Hackintosh Ventura
## Model MacBookPro 15,4
- Intel® Core™ i3-6006U (2 GHz, 3 MB cache, 2 cores)
- Intel HD Graphics 520 @ 2GB
- 12 GB DDR4-2133 SDRAM
- 1TB SATA HDD @ 5400rpm (GUID Partition Table) + 512GB SATA SSD (Via HDD Caddy
- Realtek ALC282 HD Audio Controller
- Wifi Realtek RTL8723DE
- Ethernet Realtek RTL8168H/8111H
- Bluetooth Broadcom BCM4350C2
- Other :
* 1 USB 2.0 ports, 2 USB 3.1 ports, TouchPad, VGA port, HDMI port, WebCam HP TrueVision HD 14" diagonal HD SVA BrightView WLED-backlit (1366 x 768), 3.5mm Combo Headphone Jack, SD Media Card Reader, 4-cell, 41 Wh Li-ion Battery

## What's Work

- ✅ Intel HD Graphic 520 Memory 2024 Mb QE/CI Enabled Graphics
  (Default resolution 1366x768) patch up resolution to 1600x900
- ✅ Brightness Adjustments
- ✅ Sound Realtek ALC282 (Work Volume Adjustments)
- ✅ Battery indicator
- ✅ USB Port
- ✅ Camera
- ✅ Keybord
- ✅ Trackpad
- ✅ Network
- ✅ Broadcom BCM4350C2 Bluetooth  

## Not Work

- ❌ Wifi RTL8723DE (Not Supported) replase with wifi dongle driver :
- @Chris1111 https://github.com/chris1111/Wireless-USB-OC-Big-Sur-Adapter

## Patch Resolution
## Copy Resolution Patch folder & file :
- Folder DisplayVendorID-9e5
- Icons.plist
## To :
- $sudo cp DisplayVendorID-9e5 /Library/Displays/Contents/Resources/Overrides
- $sudo cp Icons.plist /Library/Displays/Contents/Resources/Overrides
<img src="/img/aaaa.png?raw=true" alt="aaaa" align="center" style="width:90%;">
<img src="/img/bbbb.png?raw=true" alt="bbbb" align="center" style="width:90%;">
<img src="/img/cccc.png?raw=true" alt="cccc" align="center" style="width:90%;">
<img src="/img/dddd.png?raw=true" alt="dddd" align="center" style="width:90%;">

## Resolution Patch Inspirate :
https://github.com/codeclou/Display-Override-PropertyList-File-Parser-and-Generator-with-HiDPI-Support-For-Scaled-Resolutions
