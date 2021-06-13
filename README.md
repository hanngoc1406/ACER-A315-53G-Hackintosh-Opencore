# Acer A315-53G-5790
- Update to macOS Big Sur 11.4 and Monterey 12.0 beta 1
- Save my EFI purpose

![about](https://github.com/hanngoc1406/ACER-A315-53G-Hackintosh-Opencore/blob/master/Images/Screen%20Shot%202021-06-13%20at%2016.16.06.png)

## Specification

| Specifications | Detail                                          |
| ------------------- | -------------------------------------------|
| Computer model      | Acer A315-53G-5790     |
| Processor           | Intel Core i5-8250U             |
| Memory              | 8GB/4GB Sk Hynix DDR4 2133MHz              |
| Hard Disk           | WD Green 240GB M.2 2280 + HP S700         |
| Integrated Graphics | Intel UHD Graphics 620                     |
| Sound Card          | Realtek ALC255                             |
| Wireless Card       | Intel(R) Wireless-AC 8260                  |
| Touchpad            | I2C HID based                              |

## What is working

- Graphics: Intel UHD Graphics 620 1536 МB 
- Audio: Speakers, headphones and internal mic
- Trackpad: VoodooI2C makes it buttery-smooth, supports all the macOS gestures 
- Built-in Wifi: Replaced with Intel AC8260 using [OpenIntelWireless](https://github.com/OpenIntelWireless) 

## Known not work
```
1. Discrete Graphics: GeForce MX130 (Disabled - MacOS not supported optimus)
2. Built-in Wifi (Must be replaced)
```

## Credits

- **Special thanks** to [Acidanthera](https://github.com/acidanthera) for providing [AppleALC](https://github.com/acidanthera/AppleALC), [AppleSupportPkg](https://github.com/acidanthera/AppleSupportPkg), [HibernationFixup](https://github.com/acidanthera/HibernationFixup), [Lilu](https://github.com/acidanthera/Lilu), [OpenCorePkg](https://github.com/acidanthera/OpenCorePkg), [VirtualSMC](https://github.com/acidanthera/VirtualSMC), [VoodooPS2](https://github.com/acidanthera/VoodooPS2), and [WhateverGreen](https://github.com/acidanthera/WhateverGreen).
- Thanks to [RehabMan](https://github.com/RehabMan) for providing [SATA-unsupported](https://github.com/RehabMan/hack-tools/tree/master/kexts/SATA-unsupported.kext).
- Thanks to [VoodooI2C](https://github.com/VoodooI2C) for providing [VoodooI2C](https://github.com/VoodooI2C/VoodooI2C).
- A huge thanks to the opencore community, I couldn't stress enough the support I got to make this a success. [Reddit](https://www.reddit.com/r/hackintosh/) 
