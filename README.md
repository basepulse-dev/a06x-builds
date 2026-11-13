# Galaxy A06 5G (SM-A066B, a06x) test builds

Unofficial LineageOS 23.2 builds for the Samsung Galaxy A06 5G. **Test builds: expect bugs. No GApps.**

Downloads: see [Releases](../../releases).

## Requirements
- SM-A066B with unlocked bootloader and OrangeFox recovery
- Stock vendor **A066BXXS3AYI3** (the installer checks this and refuses otherwise)
- Already running a GSI (vbmeta already disabled)

## Flash
1. Copy everything you want to keep off the phone (step 4 wipes internal storage).
2. Boot OrangeFox > **Backup**: Data, System, System_ext, Product (to SD card or PC).
3. **Install** the zip. It writes only system, system_ext and product and verifies each one.
   Vendor, boot/kernel, recovery, modem and EFS are not touched.
4. **Wipe > Format Data** (type `yes`).
5. **Reboot System**. First boot can take 5+ minutes.

## Go back
OrangeFox > **Restore** the backup from step 2.

## Please report
Boots? Calls + SMS, mobile data, VoLTE, Wi-Fi, Bluetooth, camera, audio + mic, fingerprint,
auto-rotate, screen off during calls, charging, battery drain overnight.

Flash at your own risk.
