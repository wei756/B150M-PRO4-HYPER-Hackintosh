# B150M-PRO4-HYPER-Hackintosh

 B150M-PRO4/HYPER OpenCore EFI Firmware

## 사양 

B150M-PRO4/HYPER에서 사용가능한 EFI입니다.

오픈코어(OpenCore) v0.6.6을 사용합니다.



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
- Wi-Fi/BT: Broadcom BCM94350ZAE



## 작동하는 것

- Wi-Fi/BT (별도 카드 장착)
- 3.5파이 오디오
- USB 포트
- 이더넷
- QE/CI
- 헤드리스


## 안 되는 것

- 잠자기

## BIOS 설정

- 



## EFI 구성

### Kexts

- [AirportBrcmFixup](https://github.com/acidanthera/AirportBrcmFixup) v2.1.2
- [AppleALC](https://github.com/acidanthera/AppleALC) v1.5.7
- [BrcmBluetoothInjector](https://github.com/acidanthera/BrcmPatchRAM) v2.5.6
- [BrcmFirmwareData](https://github.com/acidanthera/BrcmPatchRAM) v2.5.6
- [BrcmPatchRAM3](https://github.com/acidanthera/BrcmPatchRAM) v2.5.6
- [IntelMausi](https://github.com/acidanthera/IntelMausi) v1.0.5
- [Lilu](https://github.com/acidanthera/Lilu) v1.5.1
- [SMCProcessor](https://github.com/acidanthera/VirtualSMC) v1.2.0
- [SMCSuperIO](https://github.com/acidanthera/VirtualSMC) v1.2.0
- [VirtualSMC](https://github.com/acidanthera/VirtualSMC) v1.2.0
- [VoodooPS2Controller](https://github.com/acidanthera/VoodooPS2) v2.2.1
- [WhateverGreen](https://github.com/acidanthera/WhateverGreen) v1.4.7

### EFI

- HfsPlus
- OpenCanopy
- OpenRuntime
- Ps2KeyboardDxe
- Ps2MouseDxe

### SSDT

- SSDT-EC-USBX : fake ec, usb controller
- SSDT-GPRW : GPRW method hotpatch
- SSDT-OSYS : macOS check fix
- SSDT-PLUG : Enable XCPM



## 참고자료

- https://dortania.github.io/OpenCore-Install-Guide
