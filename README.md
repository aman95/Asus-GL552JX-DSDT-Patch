# Asus ROG GL552JX Laptop Patches
Clover and DSDT patches for for macOS Sierra 10.12.4+

===================

----------


Hardware:
------------
- Processor: Intel Core i7-4720HQ
- Chipset: HM86
- Graphics: Intel HD graphics 4600 (haswell) , Nvidia 950m (disabled)
- Wifi: Broadcomm BCM94352Z WLAN + Blutooth 4.0
- Ethernet: Realtek RTL8111 Gigabit ethernet
- Audio: Conexant CX20752 (Headphone + mic)
- Trackpad: Elantech v4 Clickpad
- Card Reader: Realtek Cardreader (pci)
- Display: 1920x1080 60Hz IPS Panel
- Battery: 14.4v 48Whr 4-cell Li-ion battery

Working:
---------
- Intel HD graphics 4600 (haswell)
- Wifi (BCM94352Z) using Rehabman's patch
- Usb 3.0 with power patches
- Sleep and Wake
- Native CPU Power Management
- Keyboard Backlit and fn keys
- Brightness
- Ethernet
- Trackpad with gestures
- Sound (AppleALC) including internal Mic and Headphone jack detection
- Battery Status
- Bluetooth
- Webcam
- Airdrop
- HDMI

Known Issues / Not Working:
-----
- HDMI audio
- Card Reader (no support for PCI card readers in macOS)
- VGA Port (Not tested)
- Hibernate (will never work)

Credits:
--
- [Rehabman](https://github.com/RehabMan) for DSDT and Clover Patches
- [EMlyDinEsH](http://forum.osxlatitude.com/index.php?/topic/1948-elan-focaltech-and-synaptics-smart-touchpad-driver-mac-os-x/) for Elantech Trackpad Kext
- [Piker-Alpha](https://github.com/Piker-Alpha) for Native CPU power management
- [vit9696](https://github.com/vit9696/AppleALC) for AppleALC, Lilu and IntelGraphicsFixup