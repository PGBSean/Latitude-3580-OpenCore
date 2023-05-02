# OpenCore - Dell - Latitude 3580
This repo lets you download your OpenCore EFI for the Dell Latitude 3580.

WARNING ⚠️: I  do not responsible for lost personal data, or malfunction hard drive. **You are doing this at your own RISK.**

Anyways, back to the topic 💁‍♂️

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

## Set up
To install macOS, you need a OS version at least macOS 11 (Big Sur) or above, this includes macOS Monterey, Ventura, and above (Beta versions not guaranteed), and a proper Internet connection for SecureBootControl and ApECID for personlized volumes.

Before you go ahead and install macOS, make sure that:
- BitLocker is **suspended** or **turned off** in Windows (if needed)
- Turn off **Secure Boot**, **Fastboot**, **TPM**, and **Auto OS Recovery** Threshold in BIOS
- If you have Windows installed, it's **reccommended** that you **wipe** the drive through BIOS or on your own.
- If your **Ethernet port** is **damaged** or not available, use your Android phone instead.

## iServices
**DO NOT LOG IN TO YOUR APPLE ID ON FIRST SETUP**, because the serial number isn't vaild anymore! Update on your own by using GenSMBIOS (https://github.com/corpnewt/GenSMBIOS)

## Screenshot
![Screenshot 2023-03-04 at 20 14 20](https://user-images.githubusercontent.com/97381104/222903854-15243e7f-de16-4d9c-a4eb-0c51d7382eb4.png)
