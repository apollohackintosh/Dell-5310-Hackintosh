# Dell Latitude 5310 Hackintosh

![laptop_latitude_13_5310](https://github.com/apollohackintosh/Dell-5310-Hackintosh/assets/9867529/8a5ec8b3-8e74-4382-9473-6c8fbc98e991)

This is the first Dell Lattitude 5310 OpenCore EFI on version 1.0.0.

The EFI is working fine and is built for MacOS Ventura.

This is a work in progress and fixes/updates will be released when I get a chance to work on them.

## Tested macOS Version

- macOS Ventura 13.6.1
- macOS Sonoma 14.5

- For Lags in boot up disable FileVault

## Bootloader

OpenCore 1.0.0

## SMBIOS

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
 
 - [x] WiFi (2.4Ghz + 5Ghz) - For Sonoma please use the updated KEXT https://github.com/OpenIntelWireless/itlwm/releases 2.3.0-alpha works

 - [x] Bluetooth

 - [x] Ethernet

 - [x] HDMI + audio over HDMI

 - [x] Touchpad with Gestures + Trackpad + Buttons

 - [x] Web Camera

 - [x] USB 3.0

 - [x] MicroSD card reader - For Sonoma only use the following KEXT https://github.com/0xFireWolf/RealtekCardReader else it will stop working

 - [x] Native hotkeys support with Fn keys (Volume Fn+F1/F2/F3)
 
 - [x] USB-C charging

 - [x] USB-C DP-alt Mode

 - [x] USB-C, 3.0, 2.0 Data transfer
 
 - [x] Thunderbolt
 
 - [x] Handoff, Airdrop & Sidecar

 - [x] FileVault 2

 - [x] Smart card reader - Works with virtualisation software

 - [x] Native HotKeys Support for Screen Brightness Fn + F6/F7 working with MonitorControl https://github.com/MonitorControl/MonitorControl/releases
 
 - [x] Iservices with WiFi, find my with localization AirportItlwm by creating fake ethernet connection nullEthernet (https://bitbucket.org/anonymous_writer/os-x-null-ethernet/src/master/) here is the tutorial (https://github.com/OpenIntelWireless/itlwm/issues/942#issuecomment-2169892581) - you have to restart wifi so i created this script, you need to add autostart script in macos automator https://github.com/marczukmichal/Dell-5310-Hackintosh/blob/main/wifi-restart.md
## What's not working 

- [ ] Fingerprint sensor - Touch ID cannot be simulated but I am trying to find an alternative

## Additional Notes

- How to hackintosh: https://dortania.github.io/OpenCore-Install-Guide/
- Don't forget to generate your own SMBIOS with https://github.com/corpnewt/GenSMBIOS. 

- ENJOY!
