# [OpenCore](https://github.com/acidanthera/OpenCorePkg) configuration for Ryzen 2700X &amp; MSI B450I Gaming Plus AC &amp; stock WI-FI adapter

### Based on the [solution](https://github.com/portrayer/Hackintosh-Ryzen-MSI-B450I)
[![N|Solid](https://avatars.githubusercontent.com/u/4136944?s=64&v=4)](https://github.com/portrayer)


## Builds

| Type                   | Name                                  |
| ---------------------- | ------------------------------------- |
| CPU                    | Ryzen 2700X                           |
| MB                     | MSI B450I Gaming Plus AC              |
| Audio                  | ALC887                                |
| GPU                    | Sapphire Radeon RX 480 4 GB with RX 580 bios               |
| RAM                    | 32G DDR4 (16GB * 2)                     |
| Wireless & Bluetooth   | Intel 3168ngw                               |
| macOS                  | Big Sur & Catalina                    |

## Functional

- [x] CPU by [AMD-Vanilla](https://github.com/AMD-OSX/AMD_Vanilla)
- [x] USB by [khronokernel's guide](https://github.com/khronokernel/Opencore-Vanilla-Desktop-Guide/blob/master/AMD/AMD-USB-map.md)
- [x] Audio by [AppleALC](https://github.com/acidanthera/AppleALC) (alcid=5)
- [x] Graphics by [WhateverGreen](https://github.com/acidanthera/WhateverGreen)
- [x] WIFI by [AirportItlwm](https://github.com/OpenIntelWireless/itlwm)
- [x] Bluetooth by [BrcmPatchRAM](https://github.com/RehabMan/OS-X-BrcmPatchRAM) and [nickhx from osxlatitude](https://osxlatitude.com/forums/topic/11540-dw1820a-the-general-troubleshooting-thread/page/10/)
- [x] iMessage / FaceTime / Handoff

## Issues

- mic in of alc887 don't work
- AirDrop not working
- Can't run andriod emulator since android emulator only supports vt-x, but genymotion and virtualbox with amd-v support work well
