    // Disclaimer:
    - We're not responsible for bricked devices, dead SD card or anything happens with your device.
    - Flash on your own risk/knowledge.
    - Take your data backup before proceed.
--------------------------------------------------------------------------------------------------
## Flashing Instructions for 7pro (guacamole):
<details>
<summary>Click to expand !</summary>


 -Reboot to fastboot & flash recovery in both slot using command:

                                                                                                                  
    fastboot flash boot_a <recovery_filename>.img
    fastboot flash boot_b <recovery_filename>.img

 -Now reboot to recovery & factory reset.

 -Back to recovery main page tap **Apply update** then **Apply from ADB**.

 -Now sideload ROM.zip using command.

                                                                                                                  
    adb sideload <rom_filename>.zip

 -If getting message **Signature verification failed** click **yes**.

 -You'll see process stuck on 47%, Don't worry you'll get **Success** message just wait.

 -Now once again do a **Factory reset** & reboot.
</details>

-------------------------------------------------------------
## Flashing Instructions for 7t (hotdogb) and 7tPro (hotdog):
<details>
<summary>Click to expand !</summary>


 -Reboot to fastboot & flash recovery in both slot using command:

                                                                                                                  
    fastboot flash recovery_a <recovery_filename>.img
    fastboot flash recovery_b <recovery_filename>.img

 -Now reboot to recovery & factory reset.

 -Back to recovery main page tap **Apply update** then **Apply from ADB**.

 -Now sideload ROM.zip using command.

                                                                                                                  
    adb sideload <rom_filename>.zip

 -If getting message **Signature verification failed** click **yes**.

 -You'll see process stuck on 47%, Don't worry you'll get **Success** message just wait.

 -Now once again do a **Factory reset** & reboot.
</details>

-------------------------------------------------------------------------------
## Flashing Instructions for OnePlus 9 (lemonade) and OnePlus 9Pro (lemonadep):
<details>
<summary>If coming from OOS A12, Downgrade to OOS 11:</summary>
 
 -Flash Xtended recovery ( Link in bottom of this page).
                                                                                                                  
    fastboot flash boot <recovery_filename>.img

 -Download copy-partition zip from [**HERE**](https://androidfilehost.com/?fid=2188818919693768129)
 
 -Sideload copy-partition zip.
 
 -Reboot to recovery & factory reset
 
 -Back to recovery main page tap **Apply update** then **Apply from ADB**.

 -Now sideload ROM.zip using command.

                                                                                                                  
    adb sideload <rom_filename>.zip

 -If getting message **Signature verification failed** click **yes**.

 -You'll see process stuck on 47%, Don't worry you'll get **Success** message just wait.

 -Now once again do a **Factory reset** & reboot.
 </details>
 
 <details>
<summary>If coming from OOS A11 or any AOSP based A11/A12 ROM then proceed:</summary>
 
 -Flash Xtended recovery ( Link in bottom of this page).
                                                                                                                  
    fastboot flash boot <recovery_filename>.img

 -Now reboot to recovery & factory reset.

 -Back to recovery main page tap **Apply update** then **Apply from ADB**.

 -Now sideload ROM.zip using command.

                                                                                                                  
    adb sideload <rom_filename>.zip

 -If getting message **Signature verification failed** click **yes**.

 -You'll see process stuck on 47%, Don't worry you'll get **Success** message just wait.

 -Now once again do a **Factory reset** & reboot.
</details>

--------------------------------------------------------------------------------------------------------------------
**Get recovery for your device:** [**HERE**](https://sourceforge.net/projects/my-builds/files/Misc/Project-Xtended/)


