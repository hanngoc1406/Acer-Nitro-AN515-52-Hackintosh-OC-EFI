# Acer Nitro AN515-52 Hackintosh OC EFI
 Save my EFI purpose

## Configuration

| Specifications | Detail                                          |
| ------------------- | -------------------------------------------|
| Computer model      | Acer Nitro 5 2018 - AN515-52 (GTX1050)     |
| Processor           | Intel Core i5-8300H, 3900 MHz              |
| Memory              | 8GB/4GB Sk Hynix DDR4 2133MHz              |
| Hard Disk           | Samsung SSD 860 EVO + WDC PC SN520         |
| Integrated Graphics | Intel UHD Graphics 630                     |
| Sound Card          | Realtek ALC255                             |
| Wireless Card       | Intel(R) Wireless-AC 9560                  |
| Touchpad            | I2C HID based                              |

## Current Status
- **Discrete graphic card** never going to work!
- **Touchpad Gestures** works after adding patched DSDT/SSDT (XOSI) in OC
- **Sound** Fully Functional, except headphone mic with Layout 29.
- **HDMI** Won't work, since the port is hardwired to the dGpu (disabled).
- **Everything else works** 

## Credits

- **Special thanks** to [Acidanthera](https://github.com/acidanthera) for providing [AppleALC](https://github.com/acidanthera/AppleALC), [AppleSupportPkg](https://github.com/acidanthera/AppleSupportPkg), [HibernationFixup](https://github.com/acidanthera/HibernationFixup), [Lilu](https://github.com/acidanthera/Lilu), [OpenCorePkg](https://github.com/acidanthera/OpenCorePkg), [VirtualSMC](https://github.com/acidanthera/VirtualSMC), [VoodooPS2](https://github.com/acidanthera/VoodooPS2), and [WhateverGreen](https://github.com/acidanthera/WhateverGreen).
- Thanks to [RehabMan](https://github.com/RehabMan) for providing [SATA-unsupported](https://github.com/RehabMan/hack-tools/tree/master/kexts/SATA-unsupported.kext).
- Thanks to [VoodooI2C](https://github.com/VoodooI2C) for providing [VoodooI2C](https://github.com/VoodooI2C/VoodooI2C).
- Thanks to [Fewtarius](https://github.com/fewtarius) for providing [JackFix](https://github.com/fewtarius/jackfix).
- A huge thanks to the opencore community, I couldn't stress enough the support I got to make this a success. [Reddit](https://www.reddit.com/r/hackintosh/) 
