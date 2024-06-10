# Toshiba-Portege-Z30-C
This is an EFI Folder for the Toshiba Portege Z30-C 
# Specifications
Type | Spec | Status
:---------|:---------|:----------
Model Name      | Toshiba Portege Z30-C | ✅
CPU              | Intel(R) Core(TM) i5-6200U CPU @ 2.30GHz Skylake | ✅
RAM           | 8 GB 1600 MHz DDR3L | ✅
Internal Graphics Card | Intel(R) HD Graphics 520 (1.5 GB) | ✅
Wi-Fi             | Intel Dual Band Wireless AC 8260 | ✅
Ethernet          | Intel I219-V | ✅
Audio       | Realtek ALC255 | ✅
Touchpad | ALPS PS/2 Pointing Device | ✅
Display | ?? | ✅
Camera | Toshiba Webcam | ✅
# macOS Compatibility 
- ✅ macOS Sonoma 14.4
- ✅ macOS Catalina 10.15.7
- ✅ macOS Mojave 10.14.6
- ✅ macOS High Sierra 10.13.6
- ✅ macOS Sierra 10.12.6
# What's working
Type | Status
:---------|:---------
Turbo boost and CPU frequency stage |  ✅  
Intel HD Graphics 520              |  ✅  
Brightness control                  |  ✅  
HDMI                                |  ✅  
Audio Realtek ALC255            |  ✅  
Intel Ethernet I219-V            |  ✅  
Intel AC 8260 Wi-Fi, Bluetooth, iServices...         |  ✅  
USB 3.0 (with Port Map)        |  ✅  
Touchpad   |  ✅  
Battery status   |  ✅  
Camera   |  ✅  
S3 Sleep / Wake   |  ✅  
S4 Hibernation / Wake   |  ✅  
Shutdown / Reboot   |  ✅   
# BIOS settings
- Disable secure boot
- Enable virtualisation VTx & VTd
- Disable Fingerprint 
# Bugs
- Touchpad guestures are misbehaving but its most likely because its small.
- Keyboard Backlight
- FN Shortcuts need to be remapped(might fix)
- Headphone Jack distortion because its using a basic ALC id layout(id_layout 3)
- on the Sonoma specific EFI, Bluetooth isn't working unfortunately. each time I would enable the intel Bluetooth kexts, it wouldn't boot up.
- the graphics kinda act choppy on the dynamic wallpaper on the lock screen and home screen.
# Notes
- you'll need to configure the smbios and generate your own system serial number, MLB, systemUUID,ROM and SMBios.
- I'll be releasing new updates from time to time to fix patches and new efi folders for newer OS (big sur and later)
# Notice board
- currently working on a Sonoma EFI. I just downloaded the latest macOS version. unfortunately it doesn't support our i5 6th gen processor. as at now it's bootable, usable and stable enough for me to release it but I'll stop working on it. unofficial macOS versions are hard to work on so I'll specifically make this EFI work only on Sonoma (14.4+)
- I will create the an EFI of the last official macOS version that supports the MacBook 13,2(6th gen) later on.
- you can use this EFI on any other laptop of the same Intel CPU generation. you'll have to adjust the kexts and configuration according to your specifications and type of motherboard. otherwise I'm definitely sure it will boot up, I tried on my brother's Lenovo yoga 260.
## Credits
 - [Dortania](https://dortania.github.io) for developing OpenCore.
 - [Apple](https://www.apple.com) for macOS.
 - [Acidanthera](https://github.com/acidanthera) for most of the kexts.
 - [RehabMan](https://github.com/RehabMan) for battery patches.
 - [Sniki](https://github.com/Sniki) for USB kext.
