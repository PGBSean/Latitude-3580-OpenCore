# Latitude-3580-OpenCore

Formally called OC-DELL-LTT3580

This repo lets you download your OpenCore EFI for the Dell Latitude 3580.

WARNING ⚠️: I  do not responsible for lost personal data, or malfunction hard drive. **You are doing this at your own RISK.**


## This EFI applys to:
|  Components             |         Name                 |            Note                      |
|---------------------|---------------------------------|--------------------------------------|
| CPU |  Intel Core i7-7600U          |  For other CPUs, contact me |
| GPU |  Intel Iris 620              | AMD/Nivida dGPU won't work |
| Wi-Fi | Ethernet  |  To get Wi-Fi working, you could use a compatible Wi-Fi card or use your Android device (HoRnDIS.kext included)|              

## Bugs
- When using Sidecar, after upon disconnecting, Mac will hang, requiring a force reboot.
- Screensavers may lag, depends on what screensaver you choosing.
- In some cases, HDMI output won't work. Instead, the built-in display flickers.

## Tested versions
- [INCOMPATIBLE] macOS High Sierra
- [INCOMPATIBLE] macOS Mojave
- [x] macOS Catalina
- [x] macOS Big Sur
- [x] macOS Monterey
- [x] macOS Ventura

## The config.plist includes:
- Mapped USB and Camera (Camera is not suitable for people who has darker skin tone)
- SecureBootControl is set to MacBookPro 15,1 and ApECID for enhanced security (You do not to enable Secure Boot in the BIOS)
- Proper HDMI support and display calibration
- and more...

## Screenshot
![Screenshot 2023-03-04 at 20 14 20](https://user-images.githubusercontent.com/97381104/222903854-15243e7f-de16-4d9c-a4eb-0c51d7382eb4.png)
