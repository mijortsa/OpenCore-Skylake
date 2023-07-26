# OpenCore-Skylake
## EFI Laptop HP 14-bs011TU Hackintosh Ventura
## Model MacBookPro 15,4

What's Work

✅ Intel HD Graphic 520 Memory 2024 Mb QE/CI Enabled Graphics

  (Default resolution 1366x768) patch up resolution to 1600x900

✅ Brightness Adjustments 

✅ Sound Realtek ALC282 (Work Volume Adjustments) 

✅ Battery indicator

✅ USB Port

✅ Camera

✅ Keybord 

✅ Trackpad

✅ Network

✅ Broadcom BCM4350C2 Bluetooth  

Not Work

❌ Wifi RTL8723DE (Not Supported) replase with wifi dongle driver :

  @Chris1111 https://github.com/chris1111/Wireless-USB-OC-Big-Sur-Adapter

## Patch Resolution
## Copy Resolution Patch folder & file :
- Folder DisplayVendorID-9e5
- Icons.plist
### To
- $sudo cp DisplayVendorID-9e5 /Library/Displays/Contents/Resources/Overrides
- $sudo cp Icons.plist /Library/Displays/Contents/Resources/Overrides
<img src="/img/aaaa.png?raw=tru" align="center" width="1366" height="768">
<img src="/img/bbbb.png?raw=true">
<img src="/img/cccc.png?raw=true">
<img src="/img/dddd.png?raw=true">

# Resolution Patch Inspirate 
https://github.com/codeclou/Display-Override-PropertyList-File-Parser-and-Generator-with-HiDPI-Support-For-Scaled-Resolutions
