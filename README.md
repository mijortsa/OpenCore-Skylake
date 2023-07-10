# OpenCore-Skylake
Private EFI Laptop HP 14-bs011TU Hackintosh Ventura

Model MacBookPro 15,4

What's Work
1. Intel HD Graphic 520 Memory 2024
   (Default resolution 1366x768) patch up resolution to 1600x900
2. Sound Realtek ALC282
3. Battery indicator
4. USB map's
5. Camera
6. Keybord 
7. Mousepad
8. Network

Not Work
- Wifi RTL8723DE (Not Supported)
- Bluetooth (Not Supported)


# Patch Resolution, Copy Resolution Patch :
- Folder DisplayVendorID-9e5
- Icons.plist

sudo cp DisplayVendorID-9e5 /Library/Displays/Contents/Resources/Overrides

sudo cp Icons.plist /Library/Displays/Contents/Resources/Overrides

![Screenshot 2023-07-10 at 11 10 28](https://github.com/mijortsa/OpenCore-Skylake/assets/908982/e6734c27-0907-4cd1-8ed4-a1eae1b9dc8b)

![Screenshot 2023-07-10 at 11 10 47](https://github.com/mijortsa/OpenCore-Skylake/assets/908982/7b5c656f-0d56-4053-9581-336d77106287)

# Resolution Patch Inspirate 
https://github.com/codeclou/Display-Override-PropertyList-File-Parser-and-Generator-with-HiDPI-Support-For-Scaled-Resolutions
