# Hackintosh based on ASUS-Z390-F | Intel i7-8700 | RX 580 8GB
[English](https://github.com/liaojack8/ASUS-Z390F-Hack) | 中文

感謝 [Hackintosh / Vanilla](https://hackintosh.gitbook.io/-r-hackintosh-vanilla-desktop-guide/) & [OpenCore Vanilla Guide](https://khronokernel-2.gitbook.io/opencore-vanilla-desktop-guide/) & [z390-Hack](https://github.com/leto1210/z390-Hack)

![About Mac](./Images/AboutMac_Cht.png)
![Hard Acceleration](./Images/VideoProc_Cht.png)

### 分步說明
[閱讀這裡](./Instructions/Instructions_Cht.md)
---
### 零件清單
---
規格|型號
:----|:----
**CPU** | 英特爾 Intel - Core i7-8700 3.2 GHz 6核心 Processor
**散熱系統** | 酷碼 Coolermaster MASTERLIQUID ML240L RGB
**主機板(MB)** | 華碩 ROG STRIX Z390-F GAMING ATX LGA1151
**記憶體(DRAM)** | 金士頓 Kingston HyperX Predator RGB (黑) DDR4-3200 32 GB (8G*4)
**硬碟 SATA III (MacOS)** | 三星 Samsung 860 EVO 500 GB SATA 2.5吋 (MZ-76E500)
**硬碟 NVMe (Win10)** | 英特爾 Intel 760p 256 GB M.2-2280 NVME Solid State Drive
**硬碟 SATA III** | 東芝 Toshiba DT01ACA100-1TB SATAIII 32MB + DT01ACA200-2TB SATAIII 32MB
**顯示卡** | 微星 MSI - Radeon RX 580 ARMOR 8G OC '8GB GDDR5, 1366Hz'
**機殼** | 迎廣 In-Win 303C 黑
**電源供應器(PSU)** | 海盜船 Corsair RM650x 80+ 金牌全模 ATX 電源
**額外項目** | Airport A1465 BCM94360CS2 WiFi/藍芽4.0 介面卡 + PCI-E 轉接卡與外接天線(淘寶)
**額外項目** | ASUS PCE-AC68的天線底座

### 完美運行
---
* Mojave 10.14.6 安裝與引導成功
* APFS
* iGPU(UHD 630) + AMD(RX580)實現硬體加速(硬解)
* 有線網路 - Intel I219-V PCI Express Gigabit Ethernet
* 雙頻WiFi / 藍芽 - Airport A1465 (BCM94360CS2)
* 板載音效卡(光纖輸出未測試) - SupremeFX S1220A Realtek ALCS1220A
* USB 2.0, USB 3.1 與 USB C
* 睡眠/喚醒
* 圖片預覽
* 高效小睡
* Youtube 影音播放
* Airdrop
* AirPlay
* 接力 & 接續互通
* Facetime
* iMessage
* App Store
  
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
