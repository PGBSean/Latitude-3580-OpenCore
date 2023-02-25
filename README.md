# OpenCore - Dell - Latitude 3580
This repo lets you download your OpenCore EFI for the Dell Latitude 3580.

WARNING ⚠️: I  do not responsible for lost personal data, or malfunction hard drive. **You are doing this at your own RISK.**

UPDATE LOG:
- If you want to live on a bleeding edge, help me by trying out the pre-release version! The pre-release version includes updated kexts, drivers, added support for macOS Ventura, and minor fixes.

Anyways, back to the topic 💁‍♂️

This EFI applys to:
- Intel Core i7 7XXXU CPU
- Intel Iris 620 iGPU (AMD dGPU don't work)
- Dell X.21.0 BIOS (latest version just for sure)
- An Android device for Wi-Fi (You can use a compatible Wi-Fi card or the built-in Realtek Ethernet card [YOU NEED A KEXT IF YOU HAVE ANOTHER WIFI CARD])

The config.plist includes:
- Mapped USB and Camera (Camera is not suitable for people who has darker skin tone)
- SecureBootControl is set to MacBookPro 15,1 and ApECID for enhanced security (You do not to enable Secure Boot in the BIOS)
- Proper HDMI support and display calibration
- and more...

## Set up
To install macOS, you need a OS version at least macOS 11 (Big Sur) or above, this includes macOS Monterey, Ventura, and above (Beta versions not guaranteed), and a proper Internet connection for SecureBootControl and ApECID for personlized volumes.

## iServices
**DO NOT LOG IN TO YOUR APPLE ID ON FIRST SETUP**, because the serial number isn't vaild anymore! Update on your own by using GenSMBIOS (https://github.com/corpnewt/GenSMBIOS)

## Screenshot
![Screenshot 2022-11-24 at 21 07 28](https://user-images.githubusercontent.com/97381104/203803987-6c35ce12-0772-4312-9652-f59a3ae50ea9.png)
