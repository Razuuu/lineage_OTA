## 2022-04-23
- Synced with LineageOS sources

## 2022-04-21
- Do not hide LTE+
- Fixed Updater

## 2022-04-20
- Synced with LineageOS sources
- microG signature spoofing support
- Bring back support for star2lte and crownlte

## 2022-04-17
- Synced with LineageOS sources

## 2022-04-12
- Fixed BT audio issues in call and media - for real now

## 2022-04-11
- Switched back to prebuilt libbt-vendor - fixes bluetooth issues
- Applied a proper fix for google maps, which doesn't use kernel hacks 
- Some more sepolicy updates
- Updated some permissions
- Disabled AudioFX
- Removed redundant overlays
- Fixed Screen record with device audio - Thanks Rob
- Fixed vulkan - Thanks Rob
- Fixed USB audio - Thanks Rob

## 2022-04-02
**NOTE: IF FLASHING GOOGLE APPS, DO NOT SET UP NETWORK OR SECURITY OR ACCOUNT ON FIRST BOOT. SKIP EVERYTHING AND THEN SET UP THE ACCOUNT WHEN YOU GET PAST SETUP. THIS IS AS WELL NOT ISSUE ON OUR SIDE.**

**NOTE2: IF YOU FLASHED ANY THIRD PARTY PACKAGES (GAPPS etc.) YOU NEED TO REFLASH THEM AGAIN, BECAUSE ADDON.D WILL NOT WORK! IF YOU STILL HAVE ISSUES, DO A CLEAN FLASH.)**
- Updated to lineage-19.1
- Dual sim is fixed
- Added Dolby/SamsungDAP
- Switched to samsung USB hal 1.3
- Bunch of other things, check github repo

## 2022-02-19
- Fixed issues with front cam
- Added pixel AIDL power hal
- Added support for star2lte and crownlte

## 2022-02-17
- Initial lineage-19 release
