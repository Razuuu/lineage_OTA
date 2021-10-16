## 2021-10-16
- Updated blobs/kernel from latest samsung release
- WPA3 Fixed
- Updated init.exynos990.rc/ueventd.rc from XXSDUE4
- Cleaned up uneeded proprietary files
- Cleaned up device manifest
- Building Fastcharge HAL
- Allow fastbootd to flash super/userdata partition
- Sepolicy - addressed multiple denials
- Major device tree refactor, adapted to standard lineageos devicetree structure
- Updated Lineageos sources

Major thanks to Tim and Rob for these updates

## 2021-05-21

**NOTE:UPDATING THE RECOVERY AND FORMATTING DATA IS REQUIRED FOR THIS UPDATE, BECAUSE IT WILL NOT BOOT OTHERWISE.**
**ADDITIONAL DATA FORMATTING WILL NOT BE NEEDED, THIS IS BECAUSE OF SWITCHING FROM EXT4 TO F2FS.**

- Fixed USB tethering
- Fixed OMX issues
- Fixed audio issues
- Fixed camera issues/switched to snap api1
- Switched to F2FS, improved random write speed from 30 to 200 Mb/s
- Switched to opensource NFC stack
- Updated lineage sources
- Updated kernel source to latest samsung release
- Updated blobs and secpatch to latest samsung release
- Enabled MAC randomisation 
- Enabled Wi-Fi direct
- Disabled Wi-Fi Display
- Building libbt-vendor from source
- Commonized stock blobs
- Enabled haptic text cursor
- Enabled call recording
- Addressed some more sepolicy denials
- Added sepolicy for HDMI out
- Added support for freeform windows and PiP mode
- Enabled Multiuser
- Improved SQlite storage speed
- Adjusted powerhint
- Fixed charging speed reporting on lockscreen

