# macOS for ThinkPad X1 Carbon 6th Gen [20KG] (November 10, 2024)
![X1C6](https://psrefstuff.lenovo.com/syspool//Sys/Image/ThinkPad/ThinkPad_X1_Carbon_6th_Gen/ThinkPad_X1_Carbon_6th_Gen_CT1_09.png)

This project is to give the X1C6 a complete and functional build of macOS Sequoia `15.1` using the guide from  [here](https://github.com/tylernguyen/x1c6-hackintosh) with modified ACPI and updated kexts.

Using `MacbookPro15,2` SMBIOS

## My Specs
**Model:** X1C6 [20KG]

**Bios:** 1.60 Vanilla

**CPU:** 2.11GHz Intel i7-8650U (0x8086)

**GPU:** Intel UHD620 1536MB (0x5916)

**RAM:** 2133MHz Samsung 16GB Dual Channel LPDDR3

**Display:** 14" IPS Anti-Glare FHD Non-Touch, 1920x1080, 60Hz

**Storage:** PCI-E x4 NVMe WD SN730 512GB

**Partition Type:** APFS

**Wifi:** Intel Wireless AX210NGW

**Bluetooth:** Intel Wireless AX210NGW

**Bootloader:** OpenCore v1.0.2

## Note
Your laptop may or may not have the exact specs as mine. Results may vary. If you need help, please ask.

## Tested Configurations
- macOS Sonoma 14.2.1 - 14.7.1
- macOS Sequoia 15.1
- BIOS 1.60

# What Works
- Audio
- Headphone Jack
- Keyboard
- Keyboard Brightness
- Power Management (CPUFriend)
- Battery Manager
- USB A Ports
- USB C Ports
- Trackpad, with full gestures
- Trackpoint
- Webcam
- Microphone
- Display Brightness (Have to set it in Keyboard Shortcuts in System Settings)
- Sleep / Wake
- Wifi - Use Heliport v1.5.0 or else KP when using stock wifi settings (airport.d)
- Bluetooth

# What doesn't work / Haven't tested
- Fingerprint sensor - Touch ID (It will never work) (Disabled in BIOS)
- HDMI - Haven't Tested
- Thunderbolt 3 - Haven't Tested
- microSD Card Reader - Haven't Tested
- All FN Keys - F7-F12 doesn't do anything

# Bugs
- None

# Pre-Installation
1. Follow tylernguyen's [guide](https://tylernguyen.github.io/x1c6-hackintosh/).
2. Generate SMBIOS for `MacbookPro15,2`

# Installing/Updating to macOS Sequoia 15.x from macOS Sonoma 14.x
1. Replace current plist with config-for-Sequoia-install.plist (Remember to rename it back to config.plist)
2. Update to macOS 15

## Credits
- tylernguyen https://github.com/tylernguyen/x1c6-hackintosh
- benbender https://github.com/benbender/x1c6-hackintosh
- zhtengw https://github.com/zhtengw/EFI-for-X1C6-hackintosh
