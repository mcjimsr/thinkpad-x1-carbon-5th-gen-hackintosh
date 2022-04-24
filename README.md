<h1 align="center"> Thinkpad X1 Carbon 5th Generation Hackintosh on macOS Monterey 12.3.3 </h1>

<p align="center">
<a href="https://www.apple.com/macos/big-sur/">
  <img src="https://img.shields.io/badge/macOS-Monterey_v12.3.3-red.svg"/> </a>
<a href="https://github.com/acidanthera/OpenCorePkg">
  <img src="https://img.shields.io/badge/OpenCore-0.8.0-12AED6"/> </a>
</p>

## Hardware
- Intel i7-7600U w/ HD 620 integrated graphics

## Using alternate macOS Versions
- Booting currently to Monterey but Big Sur, Mojave and Catalina working!
- Other versions of macOS **will** need changes to config.plist, from my experience at minimum AirportItlwm will need changing!

## BIOS Settings
- Security -> Security Chip -> Disabled
- Security ->  I/O Port Access -> Wireless WAN, Fingerprint Reader, Memory Card Slot -> Disabled
- Security -> Fingerprint -> Disabled (all mentions, will not work in macOS likely ever)
- Security -> Secure Boot -> Disabled (VERY important!)
- Startup -> UEFI/Legacy Boot -> UEFI Only
- Startup -> CSM Support -> No
- Config -> USB -> Always On USB -> Disabled


## Updates

#### 4/23/22 - Initial Commit
- Added readme and EFI folder
- macOS to Monterey 12.3.3
- kexts needed for Monterey added (AirportItlwm, Lilu, and VirtualSMC)

# Other Repositories

- x1c6-hackintosh repositories:
  - [B0hrer/thinkpad-x1c5-hackintosh](https://github.com/B0hrer/thinkpad-x1c5-hackintosh)
 
# Credits

- [@B0hrer](https://github.com/B0hrer/thinkpad-x1c5-hackintosh) for the vast majority of configuration and SSDT patching. Thank you so much!
- [@corpnewt](https://github.com/corpnewt) for [GibMacOS](https://github.com/corpnewt/gibMacOS) and [EFIMount](https://github.com/corpnewt/MountEFI).
- [Acidanthera](https://github.com/acidanthera) for basically all of modern Hacks and the majority of kexts and code used!
- [@tylernguyen](https://github.com/tylernguyen) for a beautiful readme template and amazing documentation!

