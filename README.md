# Latitude-3580-OpenCore

Formally called OC-DELL-LTT3580

This repo lets you download your OpenCore EFI for the Dell Latitude 3580.

WARNING ⚠️: I  do not responsible for lost personal data, or malfunction hard drive. **You are doing this at your own RISK.**


## This EFI applys to:
|  Components             |         Requirements                |            Note                      |
|---------------------|---------------------------------|--------------------------------------|
| CPU |  Intel Core i7-7600U          |  For other CPUs, contact me |
| GPU |  Intel Iris 620              | AMD/Nivida dGPU won't work |
| Wi-Fi | Ethernet  |  To get Wi-Fi working, you could use a compatible Wi-Fi card or use your Android device (HoRnDIS.kext included)|

## Bugs
- Camera does not work in Sonoma
- When using Sidecar, after upon disconnecting, Mac will hang, requiring a force reboot.
- Brightness keys does not work.
- In some cases, HDMI output won't work. Instead, the built-in display flickers.

## Tested versions
> This machine is **Safe to Upgrade**! You can upgrade to any macOS available without worrying about stability! Just for safe, always use the latest EFI version!
+ macOS Catalina
+ macOS Big Sur
+ macOS Monterey
+ macOS Ventura
+ macOS Sonoma

## The config.plist includes:
- Support for the latest macOS available
- Mapped USB and Camera (Camera is not suitable for people who has darker skin tone)
- Proper HDMI support and display calibration
- and more...

## Screenshot
![A screenshot of macOS Ventura successfully installed on a laptop](https://github.com/PGBSean/Latitude-3580-OpenCore/assets/97381104/c2ec18fa-e8e0-402f-942f-2da74377639d)
