# Toshiba-Portege-Z30-B-Hackintosh


A guide for installing macOS Big Sur on Toshiba Portege Z30-B using OpenCore.
![](Images/Screenshot.png)


# Laptop's Hardware 
- <b>CPU</b>: [Intel i7 5600U](https://ark.intel.com/content/www/id/id/ark/products/91157/intel-core-i3-6006u-processor-3m-cache-2-00-ghz.html) Quad-Core CPU 2.1Ghz (Ice Lake-U)
- <b>GPU</b>: Intel HD 5500 Graphics 
- <b>Storage</b>: 512GB Samsung mSATA SSD
- <b>RAM</b>: 8 GB DDR4 2666MHz
- <b>Screen</b>: 13-inch WXGA (1366 x 768)
- <b>Trackpad</b>: PS2 Touchpad
- <b>Wi-Fi</b>: Intel Wireless Dual-Band AC7265
- <b>Ports</b>: 1 x USB-C, 2 x USB 3.0, USB 2.0 SD Card Reader, HDMI, VGA, RJ-45

# Overview 

# What's Working?
Everything Works 

# What's Not Working?
Fingerprint Reader

# Bugs
- ?

# BIOS Configuration
Before doing anything, make sure to update your BIOS to the latest version from [here](https://pcsupport.lenovo.com/us/en/products/laptops-and-netbooks/300-series/320-14ikb/downloads/ds121587), preparing your laptop to macOS, reboot your laptop, when the Lenovo logo appears press <b>F2</b>, when the BIOS menu appears go to: 
- "Configuration" <b>SATA Controller Mode</b> to <b>AHCI</b>, <b>HotKey Mode</b> to <b>Enabled</b>.
- "Security" <b>Intel Platform Trust Technology</b> to <b>Disabled</b>, <b>Intel SGX</b> to <b>Disabled</b>, <b>Secure Boot</b> to <b>Disabled</b>.
- "Boot" <b>Boot Mode</b> to <b>UEFI</b>,<b>Fast Boot</b> to <b>Disabled</b>, <b>USB Boot</b> to <b>Enabled</b>.
- "Exit" <b>OS Optimized Defaults</b> to <b>Disabled</b>.


# Credits
- [Apple](https://www.apple.com) for macOS.
- [Acidanthera](https://github.com/acidanthera) for most of the kexts.
- [RehabMan](https://github.com/RehabMan) for some ACPI patches.
- [Steve Zheng](https://github.com/stevezhengshiqi) for some patches.
- [zhen-zen](https://github.com/zhen-zen) for YogaSMC.
- [Hiep Bao Le](https://github.com/hieplpvip) for AppleBacklightSmoother
- [Sniki](https://github.com/Sniki) for some patches.
- [daliansky](https://github.com/daliansky) for some ACPI patches.
- [Moh_Ameen](https://github.com/ameenjuz) for some ACPI patches.
- [blackosx](https://github.com/blackosx/OpenCanopyIcons) for OpenCanopyIcons theme.
- [al3xtjames](https://github.com/al3xtjames) for clover-theme-oss theme.
- [ImmersiveX](https://github.com/ImmersiveX) for clover-theme-minimal-dark theme.
- And anyone else that helped to develop and improve hackintoshing.
