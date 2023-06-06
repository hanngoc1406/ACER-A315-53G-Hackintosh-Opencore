# Acer A315-53G-5790
- Update to macOS 14 Sonoma DP 1
- Save my EFI purpose

![about](Images/Screenshot%202023-06-06%20at%2023.59.17.png)

## Sonoma beta notes
- add boot-args -lilubetaall and reset NVRAM
- wifi work with itlwm.kext and Heliport

## Specification

| Specifications | Detail                                          |
| ------------------- | -------------------------------------------|
| Computer model      | Acer A315-53G-5790     |
| Processor           | Intel Core i5-8250U             |
| Memory              | 8GB/4GB Sk Hynix DDR4 2133MHz              |
| Hard Disk           | WD Green 240GB M.2 2280 + HP S700         |
| Integrated Graphics | Intel UHD Graphics 620                     |
| Sound Card          | Realtek ALC255                             |
| Wireless Card       | Intel(R) Wireless-AC 7265                  |
| Touchpad            | I2C HID based                              |

## What is working

- Graphics: Intel UHD Graphics 620 1536 МB 
- Audio: Speakers, headphones and internal mic
- Trackpad: VoodooI2C makes it buttery-smooth, supports all the macOS gestures 
- Intel-Wifi: Replaced with Intel AC7265 using [itlwm](https://github.com/OpenIntelWireless/itlwm) 
- Intel-Bluetooth may not work on macOS 12.x but you can try [What additional steps should I do to make Bluetooth work on macOS Monterey](https://openintelwireless.github.io/IntelBluetoothFirmware/FAQ.html#what-additional-steps-should-i-do-to-make-bluetooth-work-on-macos-monterey)  

## Known not work
```
1. Discrete Graphics: GeForce MX130 (Disabled - MacOS not supported optimus)
2. Built-in Wifi (Must be replaced)
```

## Credits

- **Special thanks** to [Acidanthera](https://github.com/acidanthera) for providing [AppleALC](https://github.com/acidanthera/AppleALC), [AppleSupportPkg](https://github.com/acidanthera/AppleSupportPkg), [HibernationFixup](https://github.com/acidanthera/HibernationFixup), [Lilu](https://github.com/acidanthera/Lilu), [OpenCorePkg](https://github.com/acidanthera/OpenCorePkg), [VirtualSMC](https://github.com/acidanthera/VirtualSMC), [VoodooPS2](https://github.com/acidanthera/VoodooPS2), and [WhateverGreen](https://github.com/acidanthera/WhateverGreen).
- Thanks to [daliansky](https://github.com/daliansky) for providing [VoodooI2C](https://github.com/VoodooI2C/VoodooI2C).
- Thanks to [VoodooI2C](https://github.com/VoodooI2C) for his great work with [XiaoMi-Pro-Hackintosh](https://github.com/daliansky/XiaoMi-Pro-Hackintosh).
- A huge thanks to the opencore community, I couldn't stress enough the support I got to make this a success. [Reddit](https://www.reddit.com/r/hackintosh/) 
