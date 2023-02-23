The script only works in newer ATLAS verion 617 / 618, you will need to update if you are running on older ATLAS version. GKUI see [here](https://github.com/xeon1989/Proton-X50-APK-Installer-GKUI).

If the script helps you, feel free to support me at Ko-Fi. https://ko-fi.com/xeon1989

# What is this?

The script to install apps on Proton X50 IHU running on ATLAS version 617 / 618 for all model.

Following apps are included.

-	Android Auto (Head Unit Reloaded) ([Make sure you purchase HUR to show your support!](https://www.b3itlabs.com/prod.php?id=1))
-	Autokit 2022 (Carlinkit required)
-	Back button
-	Google Maps
-	Open Hidden Settings  
-	Spotify
-	VLC for Android
-	Waze
-	Youtube Premium + MicroG

|  |  |  |
| :------: | :------: | :------: |
| ![image](https://user-images.githubusercontent.com/17538895/218326292-b72d3841-f7c3-4295-83b9-865408cc607a.png) | ![image](https://user-images.githubusercontent.com/17538895/218326308-1be8bc9d-ca98-4576-a5e9-106017b4e8b1.png) | ![image](https://user-images.githubusercontent.com/17538895/218326316-45a299ac-ad9e-436a-90df-93d85fdb2449.png) |
| ![image](https://user-images.githubusercontent.com/17538895/218326449-0580d6c7-3a98-437d-9980-97e274c4e449.png) | ![image](https://user-images.githubusercontent.com/17538895/218326454-d9c33978-267c-454d-a15e-a1deb5468311.png) | ![image](https://user-images.githubusercontent.com/17538895/218326463-5e182ceb-91c1-4408-b438-6c5525decc9c.png) |
| ![image](https://user-images.githubusercontent.com/17538895/218326482-b29cbf4f-8e1b-406a-aca5-ad3add5380e3.png) | ![image](https://user-images.githubusercontent.com/17538895/218326490-bfe4528c-2785-4f91-ae0a-28bd946f81b8.png) | ![image](https://user-images.githubusercontent.com/17538895/218326496-bfb7f8fa-bf9a-4fd2-a0b1-e09ba039585b.png) |


## Before you start
- If you updating from GKUI to ATLAS and you sideloaded in GKUI, to be on safe side, it's recommended to uninstall before proceed.


## Install Apps
1.	Download installation script with following link and unzip the file.


https://we.tl/t-0Fyl8miy59


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


https://we.tl/t-t1CaMUn3a8



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
- Optimization of ATLAS
- ~~Instruction for Android Auto to use with wheel buttons (next/prev) and disable notification.~~ [Instruction available here](https://github.com/xeon1989/Proton-X50-APK-Installer-ATLAS/blob/main/SteeringButtonWorkaroundAA.md)
- Search for better replacement of YT Premium
