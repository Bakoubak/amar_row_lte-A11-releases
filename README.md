# amar_row_lte A11 releases

Current versions for A11 firmware:

**THOSE RELEASES ARE PROVIDED AS IS AND ARE NOT STABLE, USE AT YOUR OWN RISK. AS OF 05/07/2025, THERE IS NO STABLE RELEASE, EVERYTHING IS ALPHA. IF YOU WANT TO USE IT, PLEASE SUBMIT A BUG REPORT IN THE ISSUE TAB IF YOU FIND ANY.**

- LineageOS 18.1 (Skipped)
- LineageOS 19.1 (Current) -> Milestone 1 (Initial Release)
- LineageOS 20.0 (WIP)

Bugs:

- WiFi and audio won't work on first boot, you have to reboot at least once for those two to work.
- Battery charge indicator is always charging even when there is no charger
- SELinux Permissive
- Maybe more ?

**Keep in mind those releases are made for an [Android 11 firmware](https://mirror.vistaslayer.ovh/Firmwares/amar_row_lte/X306X/Android-11/TB-X306X_S230973_240402_BMP.zip) and won't work on Android 10 firmwares. If you really can't upgrade to Android 11, refer to my other release repo with stable and daily usable Android 10 builds.**

Installation:

- Download the latest LineageOS ZIP
- Open it in your favorite file extractor utility
- Extract the recovery image
- Reboot your tablet to bootloader
- fastboot flash recovery recovery.img
- fastboot reboot recovery
- Select 'Apply update' in your recovery
- adb sideload LineageOS-xxx.zip
- After the rom is sideloaded, select 'Factory reset' and 'Format data'
- You can now reboot into your LineageOS ROM !
