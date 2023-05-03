# OpenCore - Dell - Latitude 3580
This repo lets you download your OpenCore EFI for the Dell Latitude 3580.

WARNING ⚠️: I  do not responsible for lost personal data, or malfunction hard drive. **You are doing this at your own RISK.**

If you're not sure how to install or troubleshoot, refer to this [OC-DELL-LTT3580 Wiki](https://github.com/PGBSean/OC-DELL-LTT3580/wiki)

## Bugs
- When using Sidecar, after upon disconnecting, Mac will hang, requiring a force reboot.
- Screensavers may lag, depends on what screensaver you choosing.
- I'm no longer have access to my test machine, so expect bugs in newer releases.
- OpenCore 0.9.2 EFI update will not available as the next update next month.

## This EFI applys to:
- Intel Core i7 7XXXU CPU (if you using other than i7, please tweak by yourself in the config.plist, or DM me.)
- Intel Iris 620 iGPU (AMD dGPU don't work)
- Dell X.21.0 BIOS (latest version is reccommended)
- An Android device for Wi-Fi (You can use a compatible Wi-Fi card or the built-in Realtek Ethernet card [YOU NEED A KEXT IF YOU HAVE ANOTHER WIFI CARD])

## The config.plist includes:
- Mapped USB and Camera (Camera is not suitable for people who has darker skin tone)
- SecureBootControl is set to MacBookPro 15,1 and ApECID for enhanced security (You do not to enable Secure Boot in the BIOS)
- Proper HDMI support and display calibration
- and more...

## Screenshot
![Screenshot 2023-03-04 at 20 14 20](https://user-images.githubusercontent.com/97381104/222903854-15243e7f-de16-4d9c-a4eb-0c51d7382eb4.png)
