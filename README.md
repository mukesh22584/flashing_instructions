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
5. flash recovery.img 
6. Reboot to recovery
7. Download & Sideload copy-partition zip [**HERE**](https://sourceforge.net/projects/my-builds/files/Project-Xtended/XT/copy-partitions-20220613-signed.zip/download)
8. Sideload copy-partition zip
~~~
adb sideload copy-partitions-20220613-signed.zip
~~~
9. After complete, Factory reset & again go to **Apply update > Apply from ADB**
10. Now Sideload Xtended ROM zip.
~~~
adb sideload <rom_filename>.zip
~~~
11. Now reboot to system.

### Be careful:
- Backup all your Data
- Gapps included so no need to flash/sideload GApps

</details>

----

<b>Flashing Instructions for OnePlus 9Pro (lemonadep):</b>
<details>
<br>
<summary>Click Here to expand</summary>

### Firmware C63 already included:
1. Download Xtended recovery package [HERE](https://sourceforge.net/projects/my-builds/files/Project-Xtended/XT/OnePlus_9Pro-lemonadep/)
2. Extract recovery package
3. Reboot to bootloader & connect your phone to PC
4. double click on <b>flash.bat</b> file
5. Now reboot to recovery & factory reset
6. Back to recovery main page tap > Apply update > Apply from ADB
7. Now sideload ROM.zip using command.
~~~
adb sideload <rom_filename>.zip
~~~
8. Now reboot to system.

### Be careful:
- If coming from Oxygenos or any other AOSP based A13 ROM <b>Clean Flash is Mandatory</b>
- Gapps included so no need to flash/sideload GApps
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
