# Munch PE GSI Releases

## About -
I am building this GSI with specific fixes for Poco F4 / Redmi K40s (munch), purpose is to make a flash and forget GSI for daily use.

## Instructions to flash -
1. Have unlocked bootloader
2. adb reboot fastboot
3. fastboot -w
4. fastboot reboot fastboot
5. make sure you are in FASTBOOTD now
6. fastboot flash product product.img
7. extract the xz file to get an image file
8. fastboot flash system system-treble_arm64_bvN.img
