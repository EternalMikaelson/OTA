#### PenguinOS Version — 17.01
#### Status: **Unofficial**
#### Security Patch: October 2026
#### Maintainer: **𝑲𝒍𝒂𝒖𝒔 𝑴𝒊𝒌𝒂𝒆𝒍𝒔𝒐𝒏**
---
#### Date: 03/11/'26
---------------------------
- Initial Build
- BCR: Version 3.11
- Introduce OnePlus Camera & Gallery
- Kernel Upstreamed: merged tag 6.1.190
- Added more rich [RichTap](https://github.com/richtap-haptics) haptic support throughout the system and fixed dead haptics issues.
- Enabled VoNR & Add VoNR configs for Jio
- Updated ConsumerIR App from ColorOS COS 11.C.75
- Updated device blobs from OOS 11.F.17
- Updated common tree blobs from OOS 11.F.58
- Imported thermal configs from stock profile for better management
- Imported HDR config from stock profile
- Redesign Dolby UI with expressive typography
- Shorten alert slider dialog timeout to 1.5sec
- Fixed some sepolicy denials
- KeyHandler: Suppress duplicate slider updates regardless of dialog state
- oplus-fwk: Add more classes for OOS 16 oplus camera
- Enable wide color gamut
- Disable default frame rate limit for games
- Add torch nodes permission
- export camera processing vendor libs
- add permission rule for /dev/awinic_haptic
- Force sRGB composition for vendor color modes
- Add config for ALS correction
- Set missing sensors props
- Build common ALS correction wrapper
- sensors: fusionlight: Implement ALS correction algorithm
- sensors: Add FusionLight Sensors SubHAL
- sensors: fusionlight: Hook IHalProxyCallback
- Add vendor.oplus.hardware.oplusSensor V1
- sensors: fusionlight: Support pre-V2.1 profiles
- sensors: fusionlight: Support black-frame V2.1 profiles
- Wire up per fps sf durations
- Use the QTI Bluetooth audio stack
- Add a config property for the SMMU proxy driver
- Switch to the QTI gps vendor component
- Require the CNE symlink from the QTI telephony component
- Move display props the QTI component also sets to odm
- Append to TARGET_FS_CONFIG_GEN
- Allow lseek for qsap_qapeservice
- Ship the stock cnss-daemon again
- Run the stock cnss-daemon under its own name
- Other miscellaneous improvements
