#### Axion Version — 2.7 PROXIMA
#### Status: **Unofficial**
#### Security Patch: July 2026
#### Maintainer: **𝑲𝒍𝒂𝒖𝒔 𝑴𝒊𝒌𝒂𝒆𝒍𝒔𝒐𝒏**
#### Device Changelogs
---
#### Date: 03/07/'26
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
- Drop excluded-input-devices vibrator config,no longer needed as we have shifted to prebuilt libs.
- Kang vibrator from pong
- Fix missing/delayed haptics for sliders and prebaked effects
- Other miscellaneous improvements

#### Date: 11/06/'26
---------------------------
- Initial build
- BCR: Version 3.1
- June 2026 ASB
- Add support for OTA updates(GMS build only)
- Introduce AxionFX
- Included DolbyAtmos(LunarisDolby UI)
- Included blobs from COS 11.F.14
- Included common tree blobs from OOS 11.F.50
- Included ConsumerIR App from OOS 11.F.50
- Kernel: merged tag 6.1.170
- refine charging thresholds and add CPU temp divider
- Config VOOC charging detection
- Add system ui restart option
- Fixed low network issues on 5G Network
- Fix Widevine L1
- Fixup,Use lineage-libperfmgr for DT2W (DoubleTapToWake)
- Tune ambient display burn-in protection
- Added animation for alert slider dialog
- Implement Material You theme for Alert Slider dialog
- Add toggle to swap Alert Slider dialog text/icon and background colors
- Imported missing vibrator firmwares to improve haptics and vibration quality
- Allow remapping AOSP effect IDs to RichTap internal effect IDs
- Improve RichTap vibration consistency
- richtap: Tweak effect ID mappings
- richtap: Tune per-effect haptic strength
- Setup DeviceAsWebcam
- Import qcom perf boosts into powerhint.json
- Update sf duration to 12.3ms
- init: Enable PowerHAL hint processing
- Use common libqti-perfd-client and power-libperfmgr
- init: Drop I/O prefetcher
- Remove QTI perfd
- Don't enable memperfd
- Other miscellaneous improvements
