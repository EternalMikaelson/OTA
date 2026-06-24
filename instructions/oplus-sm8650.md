## Flashing Instructions for oplus-sm8650 devices

> [!CAUTION]
> - Your warranty is void. Or valid, probably?
> - I am not responsible for any damage you make to your device. You have been warned!
> - Don't fall for mods/cracks etc. and you may end up in trouble. In such scenarios, do not blame us.

> [!WARNING]
> * I am not responsible for anything that may happen to your phone by installing custom ROMs or custom recoveries.
> * I am not responsible for anything that may happen to your phone by installing any kernels.
> * You do this at your own risk and take full responsibility.
> * Do not blame developers for any loss.
> * Be careful while following the download and installation guide.

> [!TIP]
> **Basic Notes for all users:**
> * These instructions will only work if you follow every section and step precisely.
> * Do not continue after something fails! Contact the developer or ask in the support group for help.
> * The device must have an unlocked bootloader and latest [Platform Tools](https://developer.android.com/tools/releases/platform-tools) installed on PC.
> * Make a backup of your important data and files.

### Prerequisites:
- Device must be running OxygenOS/ColorOS version 16.x.x or higher
- Bootloader Unlock [Guide](https://wiki.lineageos.org/devices/avalon/install/#unlocking-the-bootloader)
- Flash the current stock build again using local install to ensure both slots have the same firmware. (Failing to do so may brick your device)

---

## Clean Flash
- Reboot to bootloader
```
adb reboot bootloader
```
- Flash boot, init_boot, vendor_boot and recovery images
```
fastboot flash boot <drag-&-drop-boot.img>
```
```
fastboot flash init_boot <drag-&-drop-init_boot.img>
```
```
fastboot flash vendor_boot <drag-&-drop-vendor_boot.img>
```
```
fastboot flash recovery <drag-&-drop-recovery.img>
```
- Reboot to recovery
```
fastboot reboot recovery
```
- Sideload ROM zip
```
adb sideload <drag-&-drop-ROM.zip>
```
- After sideload completes:
  - Select YES if you have extra packages to flash
  - Select NO if you have none
- Format data after sideload
- Reboot and voila!

---

## Updating to a Newer Build (Dirty Flash)

> [!NOTE]
> Dirty flashing across major Android version upgrades is not supported.
>
> Example: **1.x → 2.x** requires clean flash.

### Method 1: OTA Update

- Go to **Settings → System → System Updates**
- Download the latest available build
- You can also use Local Update to select a manually downloaded ROM zip
- Tap **Reboot / Install** once download finishes
- Device will reboot to recovery and install the update automatically
- Reboot and voila!

---

### Method 2: Recovery Flash

- Sideload ROM zip
```
adb sideload <drag-&-drop-ROM.zip>
```
- After sideload completes:
  - Select YES if you have extra packages to flash
  - Select NO if you have none
- Reboot and voila!

---

> [!NOTE]
> **If sideloading ROM gives Error 7:**
>
> Reboot to fastbootd (enter fastboot option on recovery) and wipe the super partition using:
```
fastboot wipe-super <drag-&-drop-super_empty.img>
```
- Enter recovery
- Sideload the ROM zip
```
adb sideload <drag-&-drop-ROM.zip>
```
- After sideload completes:
  - Select YES if you have extra packages to flash
  - Select NO if you have none
- Format data
- Reboot

---

### If after sideloading ROM, device boots to bootloader:
- Do clean flash steps again
- When it asks for Yes/No prompt for installing additional packages, select Yes
- After device reboots to recovery, sideload again
- This time when it asks for Yes/No prompt for installing additional packages, select No
- Format data and reboot

---

## Support / Updates

📢 [Telegram Group](https://t.me/eternal_builds)
