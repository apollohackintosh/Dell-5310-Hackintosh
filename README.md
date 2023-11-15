# Dell-5310-Hackintosh

![laptop_latitude_13_5310](https://github.com/apollohackintosh/Dell-5310-Hackintosh/assets/9867529/8a5ec8b3-8e74-4382-9473-6c8fbc98e991)

This is the first Dell Lattitude 5310 OpenCore EFI on version 0.9.6.

The EFI is working fine and is built for MacOS Ventura.

This is a work in progress and fixes/updates will be released when I get a chance to work on them.

## Tested macOS Version

- macOS Ventura 13.6.1

### Bootloader

OpenCore 0.9.6

### SMBIOS

MacBookPro16,2


## BIOS Settings

- Boot mode: UEFI
- Fast Boot: Minimal
- SecureBoot: Disable
- SATA Mode: AHCI 
- Intel SGX: Software Controlled


## What's working

 
 - [x] CPU Speedstep

 - [x] iGPU acceleration

 - [x] Battery Management
 
 - [x] Sleep/Wake
 
 - [x] Internal Speakers
 
 - [x] Internal Microphone
 
 - [x] WiFi (2.4Ghz + 5Ghz)

 - [x] Bluetooth working but drops from time to time

 - [x] Ethernet

 - [x] HDMI + audio over HDMI

 - [x] Touchpad with Gestures + Trackpad + Buttons

 - [x] Web Camera

 - [x] USB 3.0

 - [x] MicroSD card reader 

 - [x] Native hotkeys support with Fn keys (Volume Fn+F1/F2/F3)
 
 - [x] USB-C charging

 - [x] USB-C DP-alt Mode

 - [x] USB-C, 3.0, 2.0 Data transfer
 
 - [x] USB drives not showing up in Ventura
 
 - [x] Thunderbolt
 
 - [x] Handoff, Airdrop & Sidecar

 - [x] FileVault 2
 
## What's not working


- [ ] Fingerprint sensor
- [ ] Smart card reader
- [ ] Native HotKeys Support for Screen Brightness Fn + F11/F12

## Additional Notes

Don't forget to generate your own SMBIOS with https://github.com/corpnewt/GenSMBIOS. 

- ENJOY!
