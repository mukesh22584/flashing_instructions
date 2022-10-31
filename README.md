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

### Update your device to OOS12 First. So follow instructions carefully.</b>
1. Backup all your Phone data.
2. Download your respective device Oxygenos zip.
  Fastboot rom & OxygenOS 12.1 zip (Both) [**FromHere**](https://mega.nz/folder/ehwFXDgI#kxkU48zVlBE7i3-UkyLwkg)
3. Extract Fastboot ROM zip.
4. Reboot your device to fastbootD & connect to PC.
5. Connect your phone to PC.
6. Go to Extracted Fastboot rom folder.
7. double click on 7Tand7TPro_A11_OOS_flash_all.bat file.
8. It'll take a little time.
9. After completed above process Reboot to recovery.
10. Factory Reset & reboot.
11. Now you're on OxygenOS 11.
12. Now Copy Oxygenos 12.1 Zip to your phone.
13. Go to System > update > Local update & select OxygenOS 12.1 zip.
14. Update to OxygenOS12.
15. After update reboot to bootloader.
16. flash recovery.img 
17. Reboot to recovery > Apply update > Apply from ADB
18. Download & Sideload copy-partition zip [**HERE**](https://sourceforge.net/projects/my-builds/files/Project-Xtended/XT/copy-partitions-20220613-signed.zip/download)
~~~
adb sideload copy-partitions-20220613-signed.zip
~~~
19. After complete Factory reset & reboot to recovery > Apply update > Apply from ADB
20. Now Sideload Xtended ROM zip.
~~~
adb sideload <rom_filename>.zip
~~~
21. Now reboot to system.

### Notes: 
- <b>Confused ?</b> So in easy words.<b>Update your device to OxygenOS 12</b>
- Now follow Step 15-20

### Be careful:
- Before Download Check folder name for your Device
- Fastboot flash bat files only for Windows users
- Linux user open that file & execute commands manually
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
