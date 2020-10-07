# B150M-PRO4-HYPER-Hackintosh

 B150M-PRO4/HYPER OpenCore EFI Firmware

## 사양 

B150M-PRO4/HYPER에서 사용가능한 EFI입니다.

오픈코어(OpenCore) v0.6.2를 사용합니다.



## 사양

- CPU: Intel Core i5-6600
- M/B: Asrock b150m pro4/hyper
- RAM: DDR4 2133 24GB(8+8+4+4)
- VGA: OC Radeon RX570 4GB
- SSD: Samsung 850 evo SATA SSD 250 GB (for macOS)
- ​         WD Black SN700 NVMe 500GB (for Win10)
- HDD: WD Blue WD20EZAZ 2TB (for DATA)
- Sound: Realtek ALC892
- LAN: Intel I219-V



## 작동하는 것

- 

## 안 되는 것

- 

## BIOS 설정

- 



## EFI 구성

### Kexts

- [AppleALC](https://github.com/acidanthera/AppleALC) v1.5.3

- [IntelMausi](https://github.com/acidanthera/IntelMausi) v1.0.4
- [Lilu](https://github.com/acidanthera/Lilu) v1.4.8
- [SMCProcessor](https://github.com/acidanthera/VirtualSMC) v1.1.7
- [SMCSuperIO](https://github.com/acidanthera/VirtualSMC) v1.1.7
- [VirtualSMC](https://github.com/acidanthera/VirtualSMC) v1.1.7
- [VoodooPS2Controller](https://github.com/acidanthera/VoodooPS2) v2.1.7
- [WhateverGreen](https://github.com/acidanthera/WhateverGreen) v1.4.3

### EFI

- HfsPlus v2.1.6
- OpenCanopy
- OpenRuntime v2.1.6
- Ps2KeyboardDxe
- Ps2MouseDxe

### SSDT

- SSDT-EC-USBX : fake ec, usb controller
- SSDT-GPRW : GPRW method hotpatch
- SSDT-OSYS : macOS check fix
- SSDT-PLUG : Enable XCPM



## 참고자료

- https://dortania.github.io/OpenCore-Install-Guide

