~~~diff
- // Disclaimer:
- We're not responsible for bricked devices, dead SD card or anything happens with your device.
- Flash on your own risk/knowledge.
- Take your data backup before proceed.
~~~
<a href="#"><img src="assets/oneplus7.png" height="60" /></a> 
<details>
<br>
<summary>Click Here to Expand :arrow_down: </summary>

:point_right: **Download required packages**
- Recovery package [**HERE**](https://sourceforge.net/projects/my-builds/files/Project-Xtended/XT/)
- Sideload copy-partition zip: [**HERE**](https://sourceforge.net/projects/my-builds/files/Project-Xtended/XT/copy-partitions-20220613-signed.zip/download)

:point_right: **If comming from OxygenOS or from anyother ROM, Required clean flash, So...** 
- Backup all your data to any external source. 
- Required OxygenOS 12 in both slot, If already then skip step 3 & 4 if not **must follow all steps**
- Gapps included so no need to flash/sideload GApps

:point_right: **Now start Flashing**
1. Reboot to bootloader & connect your phone to PC
2. flash recovery.img. (Extract recovery package to get recovery.img)
3. Reboot to recovery > Apply update > Apply from ADB
4. Sideload copy-partition zip by using command ```adb sideload copy-partitions-20220613-signed.zip```
5. After complete, Back to recovery home page & tap Factory reset > Format data/factory reset
6. Back to recovery home page & tap > Apply update > Apply from ADB
7. Now sideload rom using command ```adb sideload <rom_filename>.zip```
8. Now reboot to system.

</details>

----

<a href="#"><img src="assets/oneplus9.png" height="60" /></a> 
<details>
<br>
<summary>Click Here to expand :arrow_down: </summary>

:point_right: **Download required packages**
- Recovery package [**HERE**](https://sourceforge.net/projects/my-builds/files/Project-Xtended/XT/)

:point_right: **If comming from OxygenOS or from anyother ROM, Required clean flash, So...**
- Backup all your data to any external source. 
- Update your device to OOS 13
- Firmware already included
- Gapps included so no need to flash/sideload GApps

:point_right: **Now start Flashing**
1. Extract recovery package zip
2. Reboot to bootloader & connect your phone to PC
3. Double click on __flash.bat__
4. Reboot to recovery & Factory reset > Format data/factory reset
5. Back to recovery home page & tap > Apply update > Apply from ADB
5. Now sideload rom using command ```adb sideload <rom_filename>.zip```
7. Now reboot to system.

</details>

----
<a href="#"><img src="assets/spacewar.png" height="60" /></a>
<details>
<br>
<summary>Click Here to expand :arrow_down: </summary>

:point_right: **Download required packages**
- Recovery package [**HERE**](https://sourceforge.net/projects/my-builds/files/Project-Xtended/XT/)

:point_right: **If comming from NothingOS or from anyother ROM, Required clean flash, So...**
- Backup all your data to any external source. 
- Gapps included so no need to flash/sideload GApps

:point_right: **Now start Flashing**
1. Reboot to bootloader & connect your phone to PC
2. Extract above recovery package.zip
3. Double click on __flash.bat__
4. Reboot to recovery & Factory reset > Format data/factory reset
5. Back to recovery home page & Apply update > Apply from ADB
6. Now sideload rom using command ```adb sideload <rom_filename>.zip```
7. Now reboot to system.

</details>

----

<b>To update ROM :</b>
<details>
<br>
<summary>Already on Xtended and want to update new version: :arrow_down: </summary>

1. Reboot to recovery
2. Apply update > Apply from ADB
3. Open command prompt & sideload rom using command ```adb sideload <rom_filename>.zip```
4. Reboot

<b>Notes:</b>
- Every version isn't upgradable. It depends on system changes, So please follow release post first.
</details>

----

**Get recovery or firmware for your device:** [**HERE**](https://sourceforge.net/projects/my-builds/files/Project-Xtended/XT/)
