# USB Mapping Explanation (SSDT)

In this configuration, I have done some setting in order to stay within macOS's 15-port limit.

![](./Images/MB_InsideView_Annot.png)
![](./Images/MB_RearView_Annot.png)
![](./Images/303c_FrontPanel_Annot.png)


## USB Port List
Port Name|Device|Description
:----|:----|:----
**HS01**@`Rear Panel` | NuPrime NUDAC (always) | -
**SS01**@`Rear Panel` | Disable | DAC deosn't support USB 2.0
|||
**HS02**@`Rear Panel` | HyperX Cloud Flight Wireless Headset (common)
**SS02**@`Rear Panel` | Enable | I used extension cable, and sometimes, I'll plug 3.0 device to this port
|||
**HS03**@`Rear Panel` | G502 HERO Gaming Mouse (always) | -
**SS03**@`Rear Panel` | Disable | G502 deosn't support USB 2.0
|||
**HS04**@`Rear Panel` | Type-C USB 3.1 Gen 2 | MB rear panel
**SS04**@`Rear Panel` | Enable | USB 3.1
|||
**HS05**@`Front Panel` | Type-C USB 3.1 Gen 1 | Case front panel
**SS05**@`Front Panel` | Enable | USB 3.1
|||
**HS06**@`Internal` | MB Aura Control Device (Disable) | -
**SS06**@`Internal` | Disable | -
|||
**HS07**@`Front Panel` | USB 3.1 Gen 1 | Case front panel
**SS07**@`Front Panel` | Enable | USB 3.1
|||
**HS08**@`Front Panel` | USB 3.1 Gen 1 | Case front panel
**SS08**@`Front Panel` | Enable | USB 3.1
|||
**HS09**@`Rear Panel` | Disable | -
**SS09**@`Rear Panel` | Disable | -
|||
**HS10**@`Rear Panel` | Disable | -
**SS10**@`Rear Panel` | Disable | -
|||
**HS11**@`Internal ` | Disable | -
**SS11**@`Internal ` | Disable | -
|||
**HS12**@`Internal ` | BRCM20702 Hub (BCM943602CS bluetooth PCI adapter) | -
**SS12**@`Internal ` | Disable | adapter deosn't support USB 2.0
|| Logi G413 has two usb cable, main cable for keyboard, sub cable for led, and extension port|
**HS13**@`Rear Panel` | G413 Carbon Mechanical Gaming Keyboard_Main (always) | -
**SS13**@`Rear Panel` | Disable | G413 deosn't support USB 2.0
|||
**HS14**@`Rear Panel` | G413 Carbon Mechanical Gaming Keyboard_Sub | -
**SS14**@`Rear Panel` | Disable | G413 deosn't support USB 2.0

# *All of the above, there're 15 ports in total.*
