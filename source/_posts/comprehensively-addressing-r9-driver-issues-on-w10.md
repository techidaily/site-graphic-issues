---
title: Comprehensively Addressing R9 Driver Issues on W10
date: 2024-10-30T18:03:43.593Z
updated: 2024-11-04T17:49:38.740Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: This Article Describes Comprehensively Addressing R9 Driver Issues on W10
excerpt: This Article Describes Comprehensively Addressing R9 Driver Issues on W10
keywords: R9 Graphics Driver,W10 Graphics Troubleshooting,NVIDIA W10 Driver Fixes,R9 Graphics Errors in Windows 10,Graphics Driver Installation on W10,W10 R9 Graphics Compatibility Guide,R9 Driver Update for W10
thumbnail: https://thmb.techidaily.com/88fe982f8ab0af867f1f236b151f6e7396d26757691ab451f3dce8ae4b3a818b.jpg
---

## Comprehensively Addressing R9 Driver Issues on W10

![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_58647de6a91e7.jpg)

AMD Radeon R9 series of graphics card is one of the perfect choices for gamers. Windows 10 users have reported that they are having some problem with their AMD Radeon R9 series of graphics card.  
  
For example, some users reported that the screen would go blank after 5 to 20 minutes into the games and the only thing left to do was to restart. And that the screen flickered when they are playing games and the screen brightness could not be adjusted.
  
In such case, you might need to consider getting your graphics card driver checked and fix any problem it has by yourself.
  
In this post, we will show you exactly how to do it. So, just read along and follow the instructions to get your graphics card back to normal.
  
[**Step one: Run DISM command**](#1)
[**Step two: Run SFC command**](#2)
[**Step three: Clean install AMD Radeon R9 display driver**](#3)
  
Before we proceed with the following resolutions, please make sure that you have done the following things:
  
1) Check to see if you have installed the latest patches and fixes updates provided by Windows.In Windows, most patches and fixes are available through**Windows Update**. It is suggested that you check whether your computer has installed the latest released patches in**Settings > Updates & security.**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/settings-updates-security.jpg)

2) Make sure you have installed the latest version of the Microsoft .Net Framework. For more information as to how to install the latest version of Microsoft .Net Framework, please visit this [**post here**](https://tools.techidaily.com/drivereasy/download/).
  
 **Step one: Run DISM command**
  
 DISM stands for Deployment Image Servicing and Management, which is a tool that helps you scan the integrity of your Windows image.
  
 1) Press**Windows key** and**X** at the same time, then choose**Command Prompt (Run as administrator)** .
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_586482f8af0b5.png)
  
 When prompted with administrator permission, press**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_586483a425d5a.jpg)
  
 2) In the command prompt window, type in the following command:

DISM /Online /Cleanup-Image /RestoreHealth

 Make sure that you have made no typo, and hit**Enter** .
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_58648713723c7.jpg)

 3) You need to wait for a while with patience for the process to finish, especially when it reaches 20%. The operation will finish in a few minutes.  
  
 **Step two: Run SFC command**
  
 SFC stands for system file checker, which is another tool that helps you scan for all protected system files and will replace the corrupted, damaged and/or incorrect versions with correct Microsoft versions.
  
 1) Press**Windows key** and**X** at the same time, then choose**Command Prompt (Run as administrator)** .
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_586482f8af0b5.png)
  
 When prompted with administrator permission, press**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_586483a425d5a.jpg)
  
2) In the command prompt window, type in command:**SFC /SCANNOW**. Make sure that you have made no typo and hit**Enter**.
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_58648e300e3c1.jpg)

3) Wait for a while for the process to finish. If no problem is found here, please move on to the next step.
  
 **Step three: Clean install AMD Radeon R9 display driver**
  
**Note**: Before proceeding with the steps below, it is highly suggested that you **[create a restore point first](https://tools.techidaily.com/drivereasy/download/) .**
  
1) Follow the path:**Start**button**\> Control Panel > Uninstall a program**(View by**Category**).  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_58648e5733e51.jpg)

2) If you are with AMD processors, select**Catalyst Control Center**and choose**Uninstall**.
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_58648f8f4dd21.jpg)
  
 If you are with Intel processors, select to uninstall **ALL** AMD software that you can see in this window.  
  
 3) Press**Windows key** and**X** at the same time, then choose**Device Manager** .

![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_586490d260746.png)

4) Locate**Display adapters**category, then double click the**AMD Radeon R9**series of display driver that you have.
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_5864a9af8c728.jpg)

5) Under**Driver**tab, choose**Uninstall**.
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_5864a9dcb005b.jpg)
  
 Tick the box for**Delete the driver software for this device** option and click**OK** to continue.
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_5864ab747efcd.png)

 6) Reboot your PC.
  
 7) Then**download** the AMD Clean Uninstall Utility from its support website. Then double click the**AMDCleanUtility.exe** icon to run the application.  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_5864ac776f616.png)
  
 Then just follow the instructions on screen to get all your AMD driver and application components removed.  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_5864acd59401a.jpg)
  
 Your computer will restart when the whole process if finished.
  
**Note** : If you already have a trusted application or driver remover, you can use it to do the full uninstall too.
  
 8) When your computer restart again, download the latest version of the AMD Radeon R9 series driver from AMD website and then install it manually.  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_5864b2625647d.png)

 If you want to save yourself more time and energy for other things, you can leave your driver problems to [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) . It automatically help you detects, downloads and updates device drivers that are missing or outdated on your computer. And, there are only two steps you take to do it:
  
 Step one: press the**Scan Now** button so [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) can help you detect for needed drivers.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58e894bc3e848.png)
  
 Step two: press the**Update** button so [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) can help you download the setup file for the device driver that you need.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58e897add407d.jpg)
  
 If you want to enjoy more features such as driver backup and driver restore, as well as professional tech support waiting to solve your driver problems, you can have a try at the [**professional version of Driver Easy**](https://tools.techidaily.com/drivereasy/download/) . If you are not satisfied with it, you can always ask for a refund thirty days within the purchase. Guaranteed.
  
 What’s with the waiting, come on and have a try at [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) now!

* [AMD](https://tools.techidaily.com/drivereasy/download/)

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-clips.techidaily.com/new-enhancing-instagram-presence-with-picture-borders/"><u>[New] Enhancing Instagram Presence with Picture Borders</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/n-2024-free-explore-youtubes-9-premium-full-length-christmas-flicks/"><u>[New] In 2024, Free Explore YouTube's 9 Premium Full-Length Christmas Flicks</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/eviving-retro-film-techniques-detailed-instructions-for-2024/"><u>[New] Reviving Retro Film Techniques Detailed Instructions for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/solved-lenovo-laptop-black-screen-issues/"><u>[SOLVED] Lenovo Laptop Black Screen Issues</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-starting-strong-with-the-best-studio-tech-for-novices/"><u>2024 Approved Starting Strong with the Best Studio Tech for Novices</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/amazon-echo-show-10-3rd-gen-review/"><u>Amazon Echo Show 10 (3Rd Gen) Review</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/failed-to-create-a-graphics-device-on-windows-fixed/"><u>Failed to Create a Graphics Device on Windows [Fixed]</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/improving-extended-screen-resolution-within-windows-10-environment/"><u>Improving Extended Screen Resolution Within Windows 10 Environment</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-after-switching-from-honor-magic-6-pro-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data After Switching From Honor Magic 6 Pro to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-methods-to-change-gps-location-on-tecno-camon-20-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Methods to Change GPS Location On Tecno Camon 20 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://screen-recording.techidaily.com/key-approaches-to-mute-motion-capture-for-2024/"><u>Key Approaches to Mute Motion Capture for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/missing-hdmi-interface-for-gpus/"><u>Missing HDMI Interface for GPUs</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/streamlined-gaming-install-updated-geforce-gtx-1060-driver/"><u>Streamlined Gaming: Install Updated GeForce GTX 1060 Driver</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/the-ultimate-trick-to-skip-logon-screen-enable-automatic-login-on-windows-machines/"><u>The Ultimate Trick to Skip Logon Screen: Enable Automatic Login on Windows Machines</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/win11-nvidia-card-conflict-resolved/"><u>Win11-NVIDIA Card: Conflict Resolved</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1982508">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982508.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982508">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982508.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982508%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982508/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

