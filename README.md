~~~
// Disclaimer:
- We're not responsible for bricked devices, dead SD card or anything happens with your device.
- Flash on your own risk/knowledge.
- Take your data backup before proceed.
~~~
<b>Flashing Instructions for OnePlus 7t (hotdogb) and OnePlus 7tPro (hotdog):</b>
<details>
<br>
<summary>Click Here to Expand</summary>

### Follow instructions carefully.
1. Backup all your Phone data.
2. Update to OxygenOS12.
3. Unlock bootloader & enable **USB debuging**
4. Reboot to bootloader.
5. Download Xtended recovery package for your device [HERE](https://sourceforge.net/projects/my-builds/files/Project-Xtended/XT/)
6. flash recovery.img 
7. Reboot to recovery
8. Download & Sideload copy-partition zip [**HERE**](https://sourceforge.net/projects/my-builds/files/Project-Xtended/XT/copy-partitions-20220613-signed.zip/download)
9. Sideload copy-partition zip
~~~
adb sideload copy-partitions-20220613-signed.zip
~~~
10. After complete, Factory reset & again go to **Apply update > Apply from ADB**
11. Now Sideload Xtended ROM zip.
~~~
adb sideload <rom_filename>.zip
~~~
12. Now reboot to system.

### Be careful:
- Backup all your Data
- Gapps included so no need to flash/sideload GApps
</details>

----

<b>Flashing Instructions for OnePlus 9 (lemonade) & 9Pro (lemonadep):</b>
<details>
<br>
<summary>Click Here to expand</summary>

### Follow instructions carefully.
1. Download Xtended recovery package for your device [HERE](https://sourceforge.net/projects/my-builds/files/Project-Xtended/XT/)
   * Extract recovery package zip
   * Reboot to bootloader & connect your phone to PC
   * Double click on <b>flash.bat</b> file
2. Now reboot to recovery > advance > fastboot
3. Download C66 firmware [HERE](https://sourceforge.net/projects/my-builds/files/Project-Xtended/XT/)
   * Extract zip, Go to fastbootD mode & execute flash.bat
4. Back to recovery main page tap > Apply update > Apply from ADB
5. Now sideload ROM.zip using command.
~~~
adb sideload <rom_filename>.zip
~~~
6. Now reboot to system.

### Be careful:
- If coming from Oxygenos or any other AOSP based A13 ROM <b>Clean Flash is Mandatory</b>
- Gapps included so no need to flash/sideload GApps
- Flash recovery in bootloader mode & firmware into FastbootD mode
</details>

----

<b>To update ROM :</b>
<details>
<br>
<summary>Already on Xtended and want to update new version:</summary>

1. Reboot to recovery > Apply update > Apply from ADB
2. Now sideload ROM.zip using command.
~~~
adb sideload <rom_filename>.zip
~~~
3. Now reboot to system.
### Notes:
- Every version isn't upgradable. It depends on system changes, So please follow release post first.
</details>

----

**Get recovery for your device:** [**HERE**](https://sourceforge.net/projects/my-builds/files/Project-Xtended/XT/)
