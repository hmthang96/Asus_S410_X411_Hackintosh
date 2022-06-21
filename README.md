# OpenCore Configuration for ASUS S410UA Version 0.2
## Spec Sheet
| Part       | Specs                           |
|------------|---------------------------------|
| CPU        | i5-8250U                        |
| RAM        | 20GB(1 free slot,1 onboard)     |
| iGPU       | Intel UHD 620                   |
| WiFi       | QCA9377 ( replaced with DW1560) |
| Audio      | Conexant CX8050 Layout-id 13    |
| SSD        | Micron 5200 1Tb                 |
| Touchpad   | ELAN1300                        |
| Fingerprint | ELAN1300(unused)                |
| SDCard     | unused                          |
| Screen     | 1920x1080                       |

## Working (Catalina, Bigsur, Monterey)
1. QE/CI
2. All USB port
3. Wireless AC
4. Bluetooth
5. Touchpad
6. Sleep/Wake
7. Power Management
8. Appstore, iMessage, FaceTime
9. Keybroad brightness
10. All function key meadia Fn + F1 -> F12

## Not Working
1. Fingerprint reader

## References
1. [Dortania's guide](https://github.com/dortania/vanilla-laptop-guide)
2. [hieplpvip's AsusSMC](https://github.com/hieplpvip/AsusSMC)
3. [acidanthera](https://github.com/acidanthera)
