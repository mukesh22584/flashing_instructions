~~~
// Disclaimer:
- We're not responsible for bricked devices, dead SD card or anything happens with your device.
- Flash on your own risk/knowledge.
- Take your data backup before proceed.
~~~

### Flashing Instructions for OnePlus 7t (hotdogb) and OnePlus 7tPro (hotdog):
<details>
<summary>Click Here to Expand</summary>
 
**If coming from OOS A11:**

1- Flash Xtended recovery ( Link in bottom of this page).
~~~                                                                                                                  
fastboot flash recovery <recovery_filename>.img
~~~
2- Download copy-partition zip from [**HERE**](https://sourceforge.net/projects/my-builds/files/Misc/Project-Xtended/copy-partitions-20220613-signed.zip/download)
 
3- Sideload copy-partition zip.
 
4- Reboot to recovery & factory reset
 
5- Back to recovery main page tap **Apply update** then **Apply from ADB**.

6- Now sideload ROM.zip using command.
~~~
adb sideload <rom_filename>.zip
~~~
7- Once again reboot to recovery

>__Warning__
~~~diff
- Don't reboot to system.
~~~

8- Now sideload Gapps.zip using command.
~~~
adb sideload <Gapps_filename>.zip
~~~

9- Now reboot to system.

>__Note__

If coming from AOSP based A13 ROM Just **Skip Step 2 & 3**

</details>

-----------------

### Flashing Instructions for OnePlus 9Pro (lemonadep):
<details>
<summary>Click Here to expand</summary>
 
**Make sure you're using c63 Firmware:**

1- Flash Xtended recovery package ( Link in bottom of this page).
~~~                                                                                                                  
fastboot flash dtbo dtbo.img
fastboot flash vendor_boot vendor_boot.img
fastboot flash boot boot.img
~~~
2- Download copy-partition zip from [**HERE**](https://sourceforge.net/projects/my-builds/files/Misc/Project-Xtended/copy-partitions-20220613-signed.zip/download)
 
3- Sideload copy-partition zip.
 
4- Reboot to recovery & factory reset
 
5- Back to recovery main page tap **Apply update** then **Apply from ADB**.

6- Now sideload ROM.zip using command.
~~~
adb sideload <rom_filename>.zip
~~~
7- Once again reboot to recovery

>__Warning__
~~~diff
- Don't reboot to system.
~~~

8- Now sideload Gapps.zip using command.
~~~
adb sideload <Gapps_filename>.zip
~~~

9- Now reboot to system.

>__Note__

If coming from AOSP based A13 ROM Just **Skip Step 2 & 3**

</details>

---------------------
### To update ROM :
<details>
<summary>Already on Xtended and want to update new version:</summary>

1- Reboot to recovery

2- Now sideload ROM.zip using command.
~~~
adb sideload <rom_filename>.zip
~~~
3- Once again reboot to recovery

>__Warning__
~~~diff
- Don't reboot to system.
~~~

4- Now sideload Gapps.zip using command.
~~~
adb sideload <Gapps_filename>.zip
~~~
</details>

------
**Get recovery for your device:** [**HERE**](https://sourceforge.net/projects/my-builds/files/Misc/Project-Xtended/)
