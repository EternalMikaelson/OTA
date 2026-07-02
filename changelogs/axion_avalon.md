#### Axion Version — 2.7 PROXIMA
#### Status: **Unofficial**
#### Security Patch: July 2026
#### Maintainer: **𝑲𝒍𝒂𝒖𝒔 𝑴𝒊𝒌𝒂𝒆𝒍𝒔𝒐𝒏**
#### Device Changelogs
---
#### Date: 02/07/'26
---------------------------
- BCR: Version 3.3
- July 2026 ASB
- Kernel: merged tag 6.1.174
- Updated ConsumerIR App from OOS 11.F.54
- Updated common tree blobs from OOS 11.F.54
- Camera: Disable face detection AE behavior
- De-blob some oplus interfaces
- Add support to toggle torch in alert slider dialog
- Add background transition animation in alert slider dialog
- Implement fade in/out animation alert slider in dialog
- Synced with latest axion source changelogs
- Other miscellaneous improvements

#### Date: 13/06/'26
---------------------------
- Drop Lineage AIDL richtap vibrator
- Drop excluded-input-devices vibrator config,no longer needed as we have shifted to prebuilt libs.
- Kang vibrator from pong
- Fix missing/delayed haptics for sliders and prebaked effects
- Updated ConsumerIR App from OOS 11.F.50
- Other miscellaneous improvements

#### Date: 08/06/'26
---------------------------
- BCR: Version 3.1
- June 2026 ASB
- Updated common tree blobs from OOS 11.F.50
- Fixed low network issues on 5G Network
- Other miscellaneous improvements

#### Date: 22/05/'26
---------------------------
- BCR: Version 2.11
- Kernel: merged tag 6.1.170
- Updated blobs from OOS 11.F.15
- Fix Widevine L1
- Fixup,Use lineage-libperfmgr for DT2W (DoubleTapToWake)
- Tune ambient display burn-in protection
- Implement Material You theme for Alert Slider dialog
- Add toggle to swap Alert Slider dialog text/icon and background colors
- Allow remapping AOSP effect IDs to RichTap internal effect IDs
- Improve RichTap vibration consistency
- richtap: Tweak effect ID mappings
- richtap: Tune per-effect haptic strength
- Added carrier config for JIO and AIRTEL (India)
- Nuked ScrollOptimizer, as it was causing lag issues randomly, especially during gaming
- Other miscellaneous improvements

#### Date: 16/04/'26
---------------------------
- BCR: Version 2.8
- Introduce AxionFX
- Dropped ViPER4AndroidFX
- Kernel: merged tag 6.1.166
- Fixed Bluetooth calling issue
- Updated blobs from OOS 11.F.14
- Updated common tree blobs from OOS 11.F.43
- Imported missing vibrator firmwares to improve haptics and vibration quality
- Tweaked dax-default of dolby to fixup headphone virtualizer amount
- richtap: Add support for Oplus Awinic sysfs nodes
- Implemented ScrollOptimizer
- Added SystemUI restart option
- Reconfigure aux camera IDs for Aperture
- KeyHandler: Update volume ringer icons
- Added animation for alert slider dialog
- Setup DeviceAsWebcam
- Import qcom perf boosts into powerhint.json
- Update sf duration to 12.3ms
- init: Enable PowerHAL hint processing
- Use common libqti-perfd-client and power-libperfmgr
- init: Drop I/O prefetcher
- Remove QTI perfd
- Don't enable memperfd
- Other miscellaneous improvements

#### Date: 10/02/'26
---------------------------
- Feb Security Patch '26
- Add support for OTA updates
- Added bypass charging
- Other miscellaneous improvements

#### Date: 07/02/'26
---------------------------
- Android 16 QPR1 Stable initial release
- January 2026 security patch
- Fixed Bluetooth calling issue
- Kernel updated and merged to tag **6.1.161**
- Lunaris Dolby included
- ViPER4AndroidFX included
- BCR (Basic Call Recorder) included
- Torch strength control added
- Other miscellaneous improvements
