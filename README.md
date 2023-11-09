# Dell-5310-Hackintosh

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
 
 - [x] Bluetooth

 - [x] Ethernet

 - [x] HDMI + audio over HDMI

 - [x] Touchpad with Gestures + Trackpad + Buttons

 - [x] Web Camera

 - [x] USB 3.0

 - [x] MicroSD card reader 

 - [x] Native hotkeys support with Fn keys (Volume Fn+F1/F2/F3)
 
 - [x] USB-C charging

 - [x] USB-C DP-alt Mode
 
 - [x] Thunderbolt (needs to plug a device before boot)
 
 - [x] Handoff, Airdrop & Sidecar

 - [x] FileVault 2
 
## What's not working

- [ ] Fingerprint sensor
- [ ] Smart card reader
- [ ] USB-C Data transfer
- [ ] Native HotKeys Support for Screen Brightness Fn + F11/F12

## Additional Notes

Don't forget to generate your own SMBIOS with https://github.com/corpnewt/GenSMBIOS. 

- ENJOY!