# Munch PE GSI Releases

## About -
I am building this GSI with specific fixes for Poco F4 / Redmi K40s (munch), purpose is to make a flash and forget GSI for daily use. I try to update this atleast once a month.

## Instructions to flash -
1. Have unlocked bootloader and be on latest MIUI (India)
2. adb reboot fastboot
3. fastboot -w
4. fastboot reboot fastboot
5. make sure you are in FASTBOOTD now
6. fastboot flash product product_gsi.img
7. extract the xz archive to get an image file
8. fastboot flash system system-treble_arm64_bvN.img
9. fastboot reboot and enjoy

## Instructions to update for existing PE GSI users -
1. adb reboot fastboot
2. fastboot reboot fastboot
3. make sure you are in FASTBOOTD now
4. extract the xz archive to get an image file
5. fastboot flash system system-treble_arm64_bvN.img
6. fastboot reboot and enjoy

## Downloads -
https://github.com/Umang96/munch_pe_custom_gsi_releases/releases
