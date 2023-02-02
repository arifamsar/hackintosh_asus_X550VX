# hackintosh_asus_X550VX

## What this?

This is Apple's Operating System that running on non-native apple devices that called hackintosh.
Im currently using Asus X550VX and running on macOS Monterey

# My Laptop Specs
* Processor : Intel i7-6700HQ SkyLake
* Wifi Adapter : Intel-8265-hmw
* RAM : 8 GB
* SSD : Toshiba 512GB
* Audio : Realtek ALC 255
* Keyboard and Touchpad : PS2Keyboard and FocalTech PS2 Touchpad

# Guides :
- I recommended you to go to [dortania](https://dortania.github.io/OpenCore-Install-Guide/) website first for clean installation
- If you want to use this EFI, you must regenerate SMBIOS with [GENSMBIOS](https://github.com/corpnewt/GenSMBIOS)
- Recommend SMBIOS : `MacBookPro13,3`

# BIOS Settings :
- Disable : CSM, Secure Boot
- Graphics Configuration : DVMT Pre-Allocation → 64M
- SATA Mode : AHCI
- Intel Virtualization : Enabled
- VT-d : Enabled

# Credits :
- Dortania
- Hackintosh Lover
- Github