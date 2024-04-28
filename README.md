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
- FN Shortcuts need to be remapped(will fix)
- Headphone Jack distortion because its using a basic ALC id layout(id_layout 3)
## Credits
 - [Dortania](https://dortania.github.io) for developing OpenCore.
 - [Apple](https://www.apple.com) for macOS.
 - [Acidanthera](https://github.com/acidanthera) for most of the kexts.
 - [RehabMan](https://github.com/RehabMan) for battery patches.
 - [Sniki](https://github.com/Sniki) for USB kext.
