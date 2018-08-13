# Change-logs

## 15. August 13, 2018
*Release status: beta-v15*
Up-to-date with Linage-OS source code. Update busybox to version 1.29.1 (credits: Lord Boeffla).

## 14. August 06, 2018
*Release status: beta-v14*
Up-to-date with Linage-OS source code.

## 13. August 02, 2018
*Release status: beta-v13*
Changes: Built using the latest GCC 8.2 (Bleeding edge toolchain). Optimizations to work with new toolchain.

## 12. July 27, 2018
*Release status: beta-v12*
Changes: Disabled fake kernel update message from Boeffla-Config (thanks to Lord Boeffla). Up-to-date with Linage-OS source code.

## 11. June 30, 2018
*Release status: beta-v11*
Changes: Added kltedv (common build for SM-G900I/P) to the supported device list. Added Boeffla Generic wakelock blocked v1.1.0. Update busybox to version 1.28.4 (credits: Lord Boeffla). Fixed cpufreq interactive using higher frequencies. Merged recent changes from osm0sis's Anykernel repo. Up-to-date with Linage-OS source code.

## 10. May 27, 2018
*Release status: beta-v10*
Changes: Added kltekdi to the supported device list. Merged recent changes from osm0sis's Anykernel repo. Up-to-date with Linage-OS source code.

## 9. May 18, 2018
*Release status: beta-v9*
Changes: Fixed off-line charging issues in klte and kltekor. Fixed occasional booting issues in kltekor. Added blu_active CPU governor (credits: engstk). Disabled modules, without losing CIFS, NTFS, XBox and OTG-Ethernet (but no NFS) supports. Enabled 268 MHz CPU under-clocked frequency cycle by default. A lot of work to improve the over-all stability and performance.

## 8. May 8, 2018
*Release status: beta-v8*
Changes: Update busybox to version 1.28.3 (credits to Lord Boeffla). Modified charge level a bit to make it compatible with SmartPack-Kernel Manager (and possibly KA in future) without touching the functionality of Boeffla-Config. Up-to-date with Linage-OS source code.

## 7. May 1, 2018
*Release status: beta-v7*
Changes: Added 268 MHz CPU under-clocked frequency cycle (and added proper configuration in Boeffla-Config). Modified headphone and speaker gain in boeffla sound a bit to make it compatible with SmartPack-Kernel Manager (and possibly KA in future) without touching the functionality of Boeffla-Config. Up-to-date with Linage-OS source code.

## 6. April 22, 2018
*Release status: beta-v6*
Changes: Up-to-date with Linage-OS source code.

## 5. April 11, 2018
*Release status: beta-v5*
Changes: Some modifications into Interactive cpufreq gov (from the mainstream Linux). Added klteduos support. Up-to-date with Linage-OS source code.

## 4. March 30, 2018
*Release status: beta-v4*
Changes: Removed wake-up gestures (Exp). Up-to-date with Linage-OS source code. Ext4 tweaks and dynamic fsync are disabled by default.

## 3. March 24, 2018
*Release status: beta-v3*
Changes: Up-to-date with Linage-OS source code.

## 2. March 19, 2018
*Release status: beta-v2*
Changes: Switch to UBERTC-8.x (latest) toolchain. Properly enabled modules according to new android requirements (should be accessible in the config app).

## 1. March 17, 2018
*Release status: beta-v1*
The very first release for Android 8.1.0.
Based on Boeffla-Kernel for [LOS-14.1](https://github.com/andip71/boeffla-kernel-cm-s5/tree/boeffla_cm14) and stock [Lineage-OS 15.1](https://github.com/LineageOS/android_kernel_samsung_msm8974/tree/lineage-15.1) kernel.
