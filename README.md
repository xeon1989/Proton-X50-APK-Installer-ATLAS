# Notices:

**14-Feb-2024:**
<br>(1) Autokit has been updated to [version 2023.12.25.1107](https://cn.carlinkit.com/autokit.html), **now supporting Steering Control (Next / Previous) buttons!**

I have tested it with CCPA on Android Auto, if you are using CarPlay, please let me know if it runs well with CarPlay.<br><br>


(2) With my newborn joining my family, I will be spending less time maintaining this repo. Nevertheless, feel free to submit an Issue, I will review them whenever I can sneak in some time. <br><br>

All past notices have been [archived here](https://github.com/xeon1989/Proton-X50-APK-Installer-ATLAS/blob/main/%5BArchived%5D%20Notice.md). 


---

If the script helps you, feel free to support me at Ko-Fi. https://ko-fi.com/xeon1989

# What is this?

A script installing a set of apps that is currently working only in Proton X50 IHU running on ATLAS version 617 / 618. For GKUI, see [here](https://github.com/xeon1989/Proton-X50-APK-Installer-GKUI).

To customize your own set of apps, [see here.](https://github.com/xeon1989/Proton-X50-APK-Installer-ATLAS/blob/main/Install_Your_Own_Apps.md)

Following apps are included.

-	Android Auto (Head Unit Reloaded) ([Modded from HUR, be sure to show your support!](https://www.b3itlabs.com/prod.php?id=1))
-	Autokit 2023.12.25.1107 (Carlinkit required)
-	Back button
-	Google Maps
-	Open Hidden Settings  
-	Spotify
-	VLC for Android
-	Waze
-	MicroG
- YouTube Vanced Music
- Newpipe

## Install Apps
1.	Download installation script with following link and unzip the file.


https://drive.google.com/file/d/1uZto1aHv4jV8OL-WlCwo-ppYibdvGDya/view?usp=sharing


2.	Backup your file in USB, then format USB drive to file system FAT32.
3.	Paste all files to root of USB drive in step 1 to USB.

![image](https://user-images.githubusercontent.com/17538895/218324330-7ab4f1ad-6b5f-4bd5-b807-13af0861069b.png)

4.	Eject USB from PC, plug it in IHU’s USB port. 
5.	When the script starts executing, IHU shows “Wireless Charging” screen. Wait patiently for around 5 min. 
6.	Once the script has ended, IHU shows Settings app and restart IHU.
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
6.	When the script starts executing, IHU shows “Wireless Charging” screen. Wait patiently for around 1 min. 
7.	Once script has ended, IHU shows Settings app. Apps are now uninstalled.

## Known Issue
1. Steering wheel buttons are not working. See [this docs](SteeringButtonWorkaroundAA.md) for the workaround, or use AA/CP with Carlinkit. 

## Important Notes
1. If you are working with MacOS, read [this additional steps](https://github.com/xeon1989/Proton-X50-APK-Installer-ATLAS/issues/5) by fevernova90.
2. QDLink will be disabled as it clashes with Android Auto wired. In case you need QDLink, Uninstall script will re-enable it. 
3. It is recommended to disable notification of some apps such as Android Auto and Spotify. 
4. If you installed apps with any method other than this Installation Script, please DO NOT PROCEED with this scripts. The Installation / Uninstallation script WILL NOT WORK as it is not compatible.
