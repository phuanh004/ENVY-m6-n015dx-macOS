# macOS on HP® ENVY m6-n015dx

#### This repo is currently compatible with macOS `10.15.5`

- Device: HP® ENVY m6-n015dx
- CPU: Intel Core i5 (4th Gen) 4210M / 2.6 GHz
- GPU: Intel HD graphics 4600
- RAM: DDR3L SDRAM 8GB
- Sound: Realtek ALC290 (ALC3241)
- HDD: WD7500BPVX-60JC3T0
- Display: 15.6-inch diagonal HD BrightView WLED-backlit touchscreen display (1366x768)
- Camera: HP Truevision HD Webcam
- Wireless Card:
  Intel® Dual Band Wireless-AC 3160 Plus Bluetooth® 4.0

## Bootloader Firmware

- Beta: OpenCore `0.5.9`

## Post-Installation

Updating...

## Known Issues

- Battery Manager needs to be patched
- Subwoofer does not work
- Wifi: The itlwm kext and HeliPort are still under development, so the following errors still exist:
  - Wifi dropping issue
  - Unable to save wifi password

## Credits

- [AppleALC Patch by MacPeet](https://www.insanelymac.com/forum/topic/311293-applealc-%E2%80%94-dynamic-applehda-patching/?do=findComment&comment=2726082)
- [HeliPort](https://github.com/zxystd/HeliPort)
- Kext authors mentioned in [kexts/README.md](OC/Kexts/README.md)