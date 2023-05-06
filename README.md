# Latitude-3580-OpenCore

Formally called OC-DELL-LTT3580

This repo lets you download your OpenCore EFI for the Dell Latitude 3580.

WARNING ⚠️: I  do not responsible for lost personal data, or malfunction hard drive. **You are doing this at your own RISK.**

If you're not sure how to install or troubleshoot, refer to this [Latitude 3580 OpenCore Wiki](https://github.com/PGBSean/OC-DELL-LTT3580/wiki)


## This EFI applys to:
- Intel Core i7 7XXXU CPU (if you using other than i7, please tweak by yourself in the config.plist, or DM me.)
- Intel Iris 620 iGPU (AMD dGPU don't work)
- An Android device for Wi-Fi (**YOU NEED A KEXT IF YOU HAVE ANOTHER WIFI CARD**)

## Bugs
- When using Sidecar, after upon disconnecting, Mac will hang, requiring a force reboot.
- Screensavers may lag, depends on what screensaver you choosing.
- In some cases, HDMI output won't work. Instead, the built-in display flickers.

## Tested versions
- [INCOMPATIBLE] macOS High Sierra
- [INCOMPATIBLE] macOS Mojave
- [UNTESTED] macOS Catalina
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
