# Important Updates:


**17-Dec-2023:**

TeamNewPipe stops supporting NewPipe Legacy, therefore the Installation script has been updated with standard NewPipe. In case you want to reinstall NewPipe only, use [this Reinstaller to Uninstall and Reinstall to NewPipe version 0.25.2](https://drive.google.com/file/d/112xlbLuzMN0xytWAPEN6jmsa0y-YkRfQ/view?usp=sharing). <br><br>

**15-Apr-2023:**

If you updated to ATLAS version 617 / 618 from 2-Mar-2023 onwards and really wanted to install apps in IHU, you can [flash ATLAS version 617v1 / 618v1 with following guide](https://github.com/xeon1989/Proton-X50-IHU-Upgrade-Downgrade/blob/main/README.md). <br><br>

**13-Apr-2023:**

If you want to avoid applying changes on IHU, you may use this [Modded QDLink](https://github.com/xeon1989/QDLink-Unlocked) for less restricted experience. <br><br>

**7-Apr-2023:**

Youtube seems having issue, so I replaced it with NewPipe.

Additionally added Youtube Vanced Music, feel free to feedback in case of issues. 

Added [Optimization](https://github.com/xeon1989/Proton-X50-APK-Installer-ATLAS/blob/main/Optimization.md). 
<br><br>

**6-Mar-2023:**

ACO patched it in latest Firmware version. 

If you updated to ATLAS version 617 / 618 from 2-Mar-2023 onwards, most probably this won't works for you.

There are no way to install app at the moment. 

---

If the script helps you, feel free to support me at Ko-Fi. https://ko-fi.com/xeon1989

# What is this?

The script only works in newer ATLAS verion 617 / 618, you will need to update if you are running on older ATLAS version. GKUI see [here](https://github.com/xeon1989/Proton-X50-APK-Installer-GKUI).

The script to install set of frequently used apps on Proton X50 IHU running on ATLAS for all model.

If you want to add your own selection of app, [click here.](https://github.com/xeon1989/Proton-X50-APK-Installer-ATLAS/blob/main/Install_Your_Own_Apps.md)

Following apps are included.

-	Android Auto (Head Unit Reloaded) ([Make sure you purchase HUR to show your support!](https://www.b3itlabs.com/prod.php?id=1))
-	Autokit 2022 (Carlinkit required)
-	Back button
-	Google Maps
-	Open Hidden Settings  
-	Spotify
-	VLC for Android
-	Waze
-	~~Youtube Premium +~~ MicroG
- Youtube Vanced Music<sup>new</sup>
- Newpipe<sup>new</sup>

## Before you start
- If you updating from GKUI to ATLAS and you sideloaded in GKUI, to be on safe side, it's recommended to uninstall before proceed.


## Install Apps
1.	Download installation script with following link and unzip the file.


https://drive.google.com/file/d/1uZto1aHv4jV8OL-WlCwo-ppYibdvGDya/view?usp=sharing


2.	Backup your file in USB, then format USB drive to file system FAT32.
3.	Paste all files to root of USB drive in step 1 to USB.

![image](https://user-images.githubusercontent.com/17538895/218324330-7ab4f1ad-6b5f-4bd5-b807-13af0861069b.png)

4.	Eject USB from PC, plug it in IHU’s USB port. 
5.	When the script start executing, IHU shows “Wireless Charging” screen. Wait patiently for around 5 min. 
6.	Once script ended, IHU shows Settings app and restart IHU.
7.	IHU optimizing apps after restart. This might take up to 15-20min. Make sure you do not turn off IHU.  
8.	After IHU started, apps should be installed.


## Uninstall Apps
1.	Delete all files in USB drive. 
2.	Download uninstallation script with following link and unzip the file.


https://drive.google.com/file/d/1-Bm6H5dBCYvpLrAVeWJcQXEXnoMQVE1U/view?usp=share_link



3.	Backup your file in USB, then format USB drive to file system FAT32. (can skip if done earlier)
4.	Paste all files to root of USB drive in step 1 to USB.

![image](https://user-images.githubusercontent.com/17538895/218324348-5969656e-2330-40fb-a38b-ea5d5092a2c3.png)

5.	Eject USB from PC, plug it in IHU’s USB port. 
6.	When the script start executing, IHU shows “Wireless Charging” screen. Wait patiently for around 1 min. 
7.	Once script ended, IHU shows Settings app. Apps is now uninstalled.

## Known Issue
1. Steering wheel button are not working. See [this docs](SteeringButtonWorkaroundAA.md) for the workaround. 
2. Intermediate issue with Autokit 2022.06.27.1555. 

## Important Notes
1. If you are working with MacOS, read [this additional steps](https://github.com/xeon1989/Proton-X50-APK-Installer-ATLAS/issues/5) by fevernova90.
2. QDLink will be disabled as it clashes with Android Auto wired. In case you need QDLink, Uninstall script will re-enable it. 
3. It is recommended to disable notification of some apps such as Android Auto and Spotify. 
4. If you installed apps with any method other than this Installation Script, please DO NOT PROCEED with this scripts. The Installation / Uninstallation script WILL NOT WORK as it is not compatible.

## TODO
- [Instruction for Optimization of ATLAS](https://github.com/xeon1989/Proton-X50-APK-Installer-ATLAS/blob/main/Optimization.md)<sup>done</sup>
- ~~Instruction for Android Auto to use with wheel buttons (next/prev) and disable notification.~~ [Instruction available here](https://github.com/xeon1989/Proton-X50-APK-Installer-ATLAS/blob/main/SteeringButtonWorkaroundAA.md))<sup>done</sup>
