## Flashing instructions for 7Pro, 7t & 7tPro:

**Disclaimer:**
* We're not responsible for bricked devices, dead SD card or anything happens with your device
* Flash on your own risk/knowledge.
* Take your data backup before proceed.
----------------------------------------

<details>
<summary><b>Flashing Instructions for 7pro(guacamole)</b></summary>


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

<details>
<summary><b>Flashing Instructions for 7t(hotdogb)</b></summary>


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

<details>
<summary><b>Flashing Instructions for 7tpro(hotdog)</b></summary>


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

Get recovery for your device: [**HERE**](https://sourceforge.net/projects/my-builds/files/Misc/A12/)
---------------------------------------------------------------------------------------------------
