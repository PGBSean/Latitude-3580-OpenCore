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
- [x] macOS Ventura
- [TEST PENDING] macOS Sonoma
> To get macOS Sonoma working, you may need to have OCLP installed on your machine. As of June 2023, installing is basically **YOYOK**, and I can't help you with that!

> ~~Will start the test procedure when the new version of OCLP released.~~

> To test Sonoma early, it's better off to change the SMBIOS to a newer one, in this case, the MacBookPro15,4 (13-inch, 2019)

> In the future, there will be two releases, one for the new SMBIOS, and the other for the current one (14,1)

> New version of this SMBIOS will be released once I've completed all of the testing needed.

## The config.plist includes:
- Mapped USB and Camera (Camera is not suitable for people who has darker skin tone)
- SecureBootControl is set to MacBookPro 15,1 and ApECID for enhanced security (You do not to enable Secure Boot in the BIOS)
- Proper HDMI support and display calibration
- and more...

## Screenshot
![A screenshot of macOS Ventura successfully installed on a laptop](https://github.com/PGBSean/Latitude-3580-OpenCore/assets/97381104/c2ec18fa-e8e0-402f-942f-2da74377639d)
