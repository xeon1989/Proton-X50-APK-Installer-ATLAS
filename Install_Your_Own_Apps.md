# Before you start
- This guide meant for advance user.
- You do not need to run standard script beforehand, you can just install your APK with this script. 
- Some apps might not works on IHU, please test on your own. I can't tell why it's not working...
- Strictly follow the steps. In case you break your IHU (although almost impossible if you adhere to the guide), I can't fix for you. :)


# What it does
- You prepare your own app and the script install it for you.
- Script also disables OTA functionality and QDLink. 

# Prepare the tools
- [7-Zip](https://www.7-zip.org/)
- [APK-Info 1.35](https://github.com/Enyby/APK-Info/releases/download/1.35/APK-Info-1.35-03.07.2019.zip)
- [Custom App Script](https://drive.google.com/file/d/1yJ_W9X9XQjLes67SkI6Z7iP9fYo7Bms3/view?usp=share_link)


# Prepare your list of apps
1. Search your app in trusted source. For eg: [APKPure](https://m.apkpure.com/).
2. Scroll to "Additional Information", make sure "Required Android" is less or equal to Android 5.0+ (Lollipop).  

![image](https://user-images.githubusercontent.com/17538895/223180936-b6607edf-aa41-4772-ad62-490c2769a96d.png)

3. Download APK. Make sure it's a single .apk file and NOT Split / App Bundle3.
4. Once downloaded, you can check the details by drag and drop .apk file to APK-Info. Take note the Min / Max SDK should be Lollipop or lower.

![image](https://user-images.githubusercontent.com/17538895/223182905-1ddd6a67-56cc-4386-9987-81ccf0602842.png)

![image](https://user-images.githubusercontent.com/17538895/223182951-cbc47790-7b81-49be-80a3-cfe581e886b3.png)

5. Download and unzip Custom App Script "Custom App.zip".
6. Copy + Paste your APK file in /Custom App/install/app folder.

![image](https://user-images.githubusercontent.com/17538895/223184711-a59a8a8e-5f4f-4d83-ab79-9178584c5257.png)

7. Rename APK file with the package name.

![image](https://user-images.githubusercontent.com/17538895/223184967-fbdbfff4-02df-4044-a452-3d7d46413b25.png)

![image](https://user-images.githubusercontent.com/17538895/223185186-1c87b3d6-db2e-4821-a0be-aa3041c71c59.png)

8. Create a folder with name "hutroops." + package name. Place the APK file in newly created folder. 

![image](https://user-images.githubusercontent.com/17538895/223185464-9a03b09a-ed8f-4a83-8ceb-f33f5cbe7e1f.png)

![image](https://user-images.githubusercontent.com/17538895/223185492-4736ee8a-5684-4959-a275-3571a9445904.png)

9. Right click APK file - 7-Zip - Open Archive

![image](https://user-images.githubusercontent.com/17538895/223185603-252626d5-d8e2-415c-965a-c1d605e620e5.png)

10. If you see the folder "lib" in 7-Zip, drag and drop it to same folder as APK file. (skip step 10 - 11 if no "lib" folder)

![image](https://user-images.githubusercontent.com/17538895/223185769-915e0cad-9fec-4975-bb3c-5b3803269749.png)

![image](https://user-images.githubusercontent.com/17538895/223186050-6974e98f-216a-4825-91ab-2e1918aa240e.png)

11. Open "lib" folder, rename as follow. For other folder such as x86*, delete it. 
| If you see | Rename to: |
|------------|------------|
| armeabi-*  | arm        |
| arm64-*    | arm64      |

12. Repeat Step 6 - 11 for all downloaded APK file.
13. Now you have prepared your USB! Place content inside "install" in FAT32 formatted USB and plug to USB. Rest of steps are the same as standard installation.
14. If you want to reuse the USB after executing files, rename folder "b832bc61472727635baffcf25dd28e9f239273e2_done" to "b832bc61472727635baffcf25dd28e9f239273e2". 

# Uninstall app custom app

1. Delete or move files in your USB drive, then copy content of /Custom App/uninstall/ to USB drive.
2. Plug it in IHU and wait for reboot. 



