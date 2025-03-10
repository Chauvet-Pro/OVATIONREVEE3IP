# OVATIONREVEE3IP

## Software Versions

[V1.3.1 - Ovation Reve E-3 IP](https://github.com/Chauvet-Pro/OVATIONREVEE3IP/blob/main/firmware/V1.3.1.zip)
- Internal Housekeeping -Non-critical update, no visible performance upgrade

[V1.3.0 - Ovation Reve E-3 IP](https://github.com/Chauvet-Pro/OVATIONREVEE3IP/blob/e7b12de815c1c9e63b00f9520439dea0227020a8/firmware/V1.3.0_06-03-24.zip)
- Improved low-end dimming performance

[V1.230112 - Ovation Reve E-3 IP](https://github.com/Chauvet-Pro/OVATIONREVEE3IP/blob/e7b12de815c1c9e63b00f9520439dea0227020a8/firmware/V1.230112.zip)
- Opened up usability with onAir Producer

[V1.220827 - Ovation Reve E-3 IP](https://github.com/Chauvet-Pro/OVATIONREVEE3IP/blob/e7b12de815c1c9e63b00f9520439dea0227020a8/firmware/V1.220827.zip)
- Released software version

&nbsp; 

## USB Software Update Instructions
1. Power on the product and plug the flash drive into the USB port.
2. Once the flash drive has been detected, the message "**Upgrade Firmware**" will be displayed. Press **< ENTER >**.
   >If a different message appears on the display, search for the updated software in the main menu (**Update Firmware**) and select from ***Only This Fixture***, ***Multiple Fixture***, or ***Other Fixture Type***. A list of the updated software files will be displayed.
   >The ***Other Fixture Type*** option under **Upgrade Firmware** can only be selected for connected products compatible with the Upload 03 (the first 2 digits of the item code must be 03).
3. Select the file that needs to be uploaded. The message **"Are you sure?"** will be displayed. Press **< ENTER >**.
   >**If the selected file is incorrect, the upgrade will fail, and the display will go back to the main interface.**
   >**Repeat steps 1-3 using the correct file**.
4. If the selected file is correct, the upgrade will start. DO NOT turn off the power or disconnect the USB during the process. USB update can take several minutes to complete.
5. When the update is complete, the fixture will automatically reboot.
6. Go to Fixture Information on the product’s menu map and confirm the firmware revision.
7. When the boot-up process is finished, restart the product.

### Special Notes
* Place the .chl file in the root directory of the USB drive.
* The product's USB port supports up to 32GB capacity and only works with FAT32 file format.
* Turning off the power or removing the USB while still blinking during the update will cause partial or total firmware failure in the targeted fixture(s). A force upload will be needed to fix firmware failure issues.


&nbsp;  

## Force Upload

1.	Link the target fixture to the main fixture via a DMX 5-pin connection. Ensure that the target fixture is turned off.
2.	Turn on the main fixture and set its protocol to DMX512.
3.	Plug the flash drive into the USB-C port of the main fixture.
4.	Go to **Upgrade Firmware** on the menu map.
5.	Choose between **Multiple Fixture** and **Other Fixture Type**. Press **< ENTER >**.
      * **Multiple Fixture** : Both the target fixture and main fixture are from the same product line (e.g., 2 Color STRIKE M fixtures).
      * **Other Fixture Type**: The target fixture and main fixture are from different product series (e.g., a Color STRIKE M as the target fixture and a Maverick Silens 2 Profile as the main fixture).
6.	Select the file that needs to be uploaded. The message ***“Are you sure?”*** will appear on the screen. Press **< ENTER >**. Turn on the target fixture within 1–2 seconds of pressing **< ENTER >**. The display on the target fixture should remain off.
   >a. The main fixture will show the update progress (0–100%).

   >b. The target fixture’s display will turn on, and a notification ***“< UPDATE >”*** will appear on the screen.
7.	DO NOT turn off power or remove the USB flash drive. Once the software is done uploading, the target fixture will automatically reboot.
8.	Go to the target fixture’s main menu and confirm that the firmware version has been updated.
9.	Reboot the target fixture.

### Special Notes
* A Force Upload process requires a target fixture (the fixture that needs a Force Upload and a main fixture (the fixture that controls the upload process).
* The Force Upload process can only be done one target fixture at a time.


