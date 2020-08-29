# Hackintosh based on ASUS-Z390-F | Intel i7-8700 | RX 580 8GB
[![macOS](https://img.shields.io/badge/macOS-10.15.6-orange)](https://www.apple.com/macos/catalina/)
[![Clover](https://img.shields.io/badge/Opencore-0.6.0-yellow)](https://github.com/996icu/996.ICU/blob/master/LICENSE)
[![BIOS](https://img.shields.io/badge/BIOS-v1502-brightgreen)](https://github.com/996icu/996.ICU/blob/master/LICENSE)

English | [中文](./README_cht.md)

Thanks for [OpenCore Desktop Guide](https://dortania.github.io/OpenCore-Install-Guide/config.plist/coffee-lake.html) & [z390-Hack](https://github.com/leto1210/z390-Hack)

###[Changelog](./changelog.md)
###[USB Mapping Explanation (SSDT)](./USB_Mapping.md)

![About Mac](./Images/AboutMac_10.15.6.png)

![Hard Acceleration](./Images/VideoProc_10.15.6.png)

![Sensei](./Images/Sensei_10.15.6.png)

---
### Parts List
Type|Item
:----|:----
**CPU** | Intel - Core i7-9700k 3.6 GHz 8-Core Processor
**CPU Cooler** | Coolermaster MASTERLIQUID ML240L RGB
**Motherboard** | Asus - ROG STRIX Z390-F GAMING ATX LGA1151 Motherboard
**Memory** | Kingston HyperX Predator RGB (Black) DDR4-3200 Memory 32 GB (8G*4)
**Storage SATA III (for MacOS)** | Samsung 860 EVO 500 GB SATA 2.5 Inch Internal Solid State Drive (SSD) (MZ-76E500)
**Storage NVMe (for Win10)** | Intel 760p 256 GB M.2-2280 NVME Solid State Drive
**Storage NVMe (for Ubuntu Linux 18.04 LTS)** | PLEXTOR M8PeGN 128 GB M.2-2280 NVME Solid State Drive
**Storage SATA III** | Toshiba DT01ACA100-1TB SATAIII 32MB + Toshiba DT01ACA200-2TB SATAIII 32MB
**Graphic Card** | MSI - Radeon RX 580 ARMOR 8G OC '8GB GDDR5, 1366Hz'
**Case** | In-Win 303C Black PC Case
**Power Supply** | Corsair RM650x (2018) 80+ Gold Certified Fully Modular ATX Power Supply
**Extra** | Airport A1465 BCM943602CS WiFi and BT 4.0 Card to PCI-E Adapter with External Antenna
**Extra** | Antenna extension base from ASUS PCE-AC68
---
#### Working
* Mojave 10.14.6 (18G84) install and boots successfully
* Catalina 10.15.6 (19G2021) install and boots successfully
* APFS
* Headless iGPU UHD 630
* Wired Ethernet - Intel I219-V PCI Express Gigabit Ethernet
* Wifi / Bluetooth - Airport A1465 (BCM94360CS2)
* Onboard Audio (I can't test digital audio output) - SupremeFX S1220A Realtek ALCS1220A
* USB 2.0, USB 3.1 and USB C
* Sleep/Wake
* Quicklook
* Power Nap
* Youtube/Netflix video on Safari
* Airdrop
* AirPlay
* Handoff & Continuity
* Facetime
* iMessage
* App Store
---
### Bugs
* N/A
---
### Tools
* [Etcher](https://www.balena.io/etcher/)
* [Hackintool](http://headsoft.com.au/download/mac/Hackintool.zip)
* [Kext Updater](https://www.kextupdater.de/)
* [Intel Power Gadget](https://software.intel.com/en-us/articles/intel-power-gadget)
* [MacIASL](http://sourceforge.net/projects/maciasl)
* [VideoProc](https://www.videoproc.com/) - Check Hardware Acceleration
---
### Install
1. Check the configuration in BIOS, My Config(./BIOS/v{Version_ID}_setting.txt), 
   you can also import the configuration file (./BIOS/v{Version_ID}_config.CMO).
2. Build your install usb drive, and replace the EFI my release.
