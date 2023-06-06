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
- When using Sidecar, after upon disconnecting, Mac will hang, requiring a force reboot.
- Brightness keys does not work.
- In some cases, HDMI output won't work. Instead, the built-in display flickers.

## Tested versions
- [INCOMPATIBLE] macOS High Sierra
- [INCOMPATIBLE] macOS Mojave
- [?] macOS Catalina (Stuck on Unable to verify macOS)
- [x] macOS Big Sur
- [x] macOS Monterey
- [!] macOS Ventura
> June 6, 2023: macOS Ventura always stuck at the finished progress bar, and stuck at "About a minute remaining". Trying to fix the bug...
- [TESTING] macOS Sonoma
> To get macOS Sonoma working, you need OCLP installed on your machine. As of June 2023, installing is basically **YOYOK**, and I can't help you with that!

## The config.plist includes:
- Mapped USB and Camera (Camera is not suitable for people who has darker skin tone)
- SecureBootControl is set to MacBookPro 15,1 and ApECID for enhanced security (You do not to enable Secure Boot in the BIOS)
- Proper HDMI support and display calibration
- and more...

## Screenshot
![A screenshot of macOS Ventura successfully installed on a laptop](https://github.com/PGBSean/Latitude-3580-OpenCore/assets/97381104/c2ec18fa-e8e0-402f-942f-2da74377639d)
