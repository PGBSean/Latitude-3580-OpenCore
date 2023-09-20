# Latitude-3580-OpenCore

## Screenshot
![A screenshot of macOS Ventura successfully installed on a laptop](https://github.com/PGBSean/Latitude-3580-OpenCore/assets/97381104/c2ec18fa-e8e0-402f-942f-2da74377639d)



## This EFI applys to:
|  Components             |         Requirements                |            Note                      |
|---------------------|---------------------------------|--------------------------------------|
| CPU |  Intel Core i7-7600U          |  For other CPUs, contact me |
| GPU |  Intel Iris 620              | AMD/Nivida dGPU won't work |
| Wi-Fi | Ethernet  |  To get Wi-Fi working, you could use a compatible Wi-Fi card or use your Android device (HoRnDIS.kext included)|

## Bugs
- Camera does not work
> This is USBPorts.kext fault
- When using Sidecar, after upon disconnecting, Mac will hang, requiring a force reboot.
- Brightness keys does not work.
- In some cases, HDMI output won't work. Instead, the built-in display flickers.

## Tested versions
> This machine is **Safe to Upgrade**! You can upgrade to any macOS available without worrying about stability! Just for safe, always use the latest EFI version!
+ ~~macOS Catalina~~ SecureBootModel now need to have Big Sur or above.
+ macOS Big Sur
+ macOS Monterey
+ macOS Ventura
+ macOS Sonoma

## The config.plist includes:
- Support for the latest macOS available
- Mapped USB and Camera (Camera is not suitable for people who has darker skin tone)
- Proper HDMI support and display calibration
- and more...
