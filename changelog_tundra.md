WARNING!!!
警告!!!
- If you wanna keep root with Magisk, please reinstall Magisk to inactive slot after OTA before rebooting device. 
- 如果您安装了Magisk，请在更新完成后不要重启，并重新安装Magisk到另一个未使用的槽位后再重启。


Changelog:

- Dec 05,2023:
1. Update blobs from tundra 13 T1SJS33.117-30-3-5
2. Enable vibrator effects on common qti vibrator HAL
3. Cleanup and update some stuff

- Nov 25,2023:
1. November Security Patch
2. Update kernel with clo tag 'LA.UM.9.14.r1-23300-LAHAINA.QSSI14.0'

- Nov 15,2023:
1. Enable Quick Tap
2. Enable display burn-in-protection in Ambient Display
3. Update kernel with 'ASB-2023-11-05_11-5.4' tag

- Oct 29,2023:
1. Add doze display state supported
2. Revert some stuff as before
3. Update kernel with linux upstream to 5.4.259

- Oct 22,2023:
1. Update blobs from tundra 13 T1SJS33.117-30-3-4
2. Update kernel with clo tag 'LA.UM.9.14.r1-23100-LAHAINA.QSSI14.0'
3. Other stuff.

- Oct 10,2023:
1. Update CarrierConfig from rtwo_retcn T1TR33.4-30-77.
2. Finally fixup HighTouchPollingRate switching in Settings.(No need to flash the kernel additionally.)
3. Update kernel with minor fixes.
4. Other stuff.

- Oct 4,2023:
1. Sync radio and ims props with stock
2. Sync misc props stuff with stock
3. Use CarrierConfig from motorola and remove moto stuff
4. Sync more media and audio feature props with stock
5. Cleanup GameSpace notification modes
6. Update blobs from MMI-T1SJS33.117-30-3-2

- Sep 25,2023:
1. rebase on new kernel sources "MMI-T1SJS33.117-30-3-2" from motorola with LA.UM.9.14.r1-22400-LAHAINA.QSSI13.0 tag merged and features.
2. September Security Patch.
3. cleanup and fixes.

- Sep 10,2023:
1. Adjust autobrightness
2. Adjust high brightness mode (HBM) level
3. add more vibration patterns
4. Update kernel for FOD brightness level

- Aug 26,2023:
1. cleanup and update
2. add ssg I/O scheduler(need update kernel)

- Aug 19,2023:
1. August Security Patch
2. A13base


- May 14,2023:
1. Fix slow motion, there is a problem with 960 frames, it cannot be saved but it has been saved successfully
2. Add ifaa support(Now Alipay fingerprint payment works well)

- May 7,2023:
1. fix unlocking fps 120Hz of 'Honor of Kings'
2. remove Aperture

- May 5,2023:
1. May security patch
2. Auto brightness adjustment
3. Update display blobs
4. Adjust some CPU scheduling
5. Switch to clang17 compiler to build kernel
6. Other adjustments
7. OTA is only for testing at present, do not update it for now.

- April 25,2023:
1. mirror tweaks.

- April 24,2023:
1. first build.

