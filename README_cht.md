# Hackintosh based on ASUS-Z390-F | Intel i7-9700K | RX 580 8GB
[![macOS](https://img.shields.io/badge/macOS-11.2-orange)](https://www.apple.com/macos/catalina/)
[![OpenCore](https://img.shields.io/badge/Opencore-0.6.6-yellow)](https://github.com/acidanthera/OpenCorePkg)
[![BIOS](https://img.shields.io/badge/BIOS-v1502-brightgreen)](https://www.asus.com/tw/Motherboards/ROG-STRIX-Z390-F-GAMING/HelpDesk_BIOS/)

[English](https://github.com/liaojack8/ASUS-Z390F-Hack) | 中文

感謝 [OpenCore Desktop Guide](https://dortania.github.io/OpenCore-Install-Guide/config.plist/coffee-lake.html) & [z390-Hack](https://github.com/leto1210/z390-Hack)

### [更新記錄](./changelog.md)

### [USB連接埠定義說明文件 (SSDT)](./USB_Mapping.md)

![About Mac](./Images/AboutMac_11.2.png)

![Hard Acceleration](./Images/VideoProc_11.2.png)

![Sensei](./Images/Sensei_11.2.png)

![HackintoshBuild](./Images/HackintoshBuild_11.2-1.png)

![HackintoshBuild](./Images/HackintoshBuild_11.2-2.png)

---
### 零件清單
---
規格|型號
:----|:----
**CPU** | 英特爾 Intel - Core i7-9700k 3.6 GHz 8核心 Processor
**散熱系統** | 酷碼 Coolermaster MASTERLIQUID ML240L RGB
**主機板(MB)** | 華碩 ROG STRIX Z390-F GAMING ATX LGA1151
**記憶體(DRAM)** | 金士頓 Kingston HyperX Predator RGB (黑) DDR4-3200 32 GB (8G*4)
**硬碟 SATA III (MacOS)** | 三星 Samsung 860 EVO 500 GB SATA 2.5吋 (MZ-76E500)
**硬碟 NVMe (Win10)** | 英特爾 Intel 760p 256 GB M.2-2280 NVME Solid State Drive
**硬碟 NVMe (存放遊戲)** | PLEXTOR M8PeGN 128 GB M.2-2280 NVME Solid State Drive
**硬碟 SATA III** | 東芝 Toshiba DT01ACA100-1TB SATAIII 32MB + DT01ACA200-2TB SATAIII 32MB
**顯示卡** | 藍寶石 SAPPHIRE - PULSE RX 580 8G G5 '8GB GDDR5, 1366Hz (Boost) 2304SP
**機殼** | 迎廣 In-Win 303C 黑
**電源供應器(PSU)** | 海盜船 Corsair RM650x 80+ 金牌全模 ATX 電源
**額外項目** | Airport A1465 BCM943602CS WiFi/藍芽4.0 介面卡 + PCI-E 轉接卡與外接天線(淘寶)
**額外項目** | ASUS PCE-AC68的天線底座

### 完美運行
---
* Big Sur (20B29) 自10.15.7 (19H15) OTA升級成功
* Catalina 10.15.7 (19H15) 安裝與引導成功
* APFS
* iGPU(UHD 630) + AMD(RX580)實現硬體加速(硬解)
* 有線網路 - Intel I219-V PCI Express Gigabit Ethernet
* 雙頻WiFi / 藍芽 - Airport A1465 (BCM94360CS2)
* 板載音效卡(光纖輸出未測試) - SupremeFX S1220A Realtek ALCS1220A
* USB 2.0, USB 3.1 與 USB C
* ~~睡眠/喚醒~~
* 圖片預覽
* 高效小睡
* ~~Youtube/Netflix在Safari上工作播放~~
* Airdrop
* AirPlay
* 接力 & 接續互通
* Facetime
* iMessage
* App Store
* ~~Sidecar~~
  
### 不正常工作 
---
* N/A
  
### 工具
---
* [Etcher](https://www.balena.io/etcher/)
* [Hackintool](http://headsoft.com.au/download/mac/Hackintool.zip)
* [Kext Updater](https://www.kextupdater.de/)
* [Intel Power Gadget](https://software.intel.com/en-us/articles/intel-power-gadget)
* [MacIASL](http://sourceforge.net/projects/maciasl)
* [VideoProc](https://www.videoproc.com/) - 用於確認硬體加速

### 安裝
---
1. 確認BIOS版本與設定組態, 我的設定組態(./BIOS/v{版本號}_setting.txt), 也可以直接導入我的設定值透過我匯出的文件(./BIOS/v{版本號}_config.CMO)
2. 建置USB系統安裝碟, 並替換EFI分區為我發佈的文件.
