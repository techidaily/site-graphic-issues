---
title: Solving R9 Driver Issues on Windows 10 Platform
date: 2024-09-27T11:55:07.850Z
updated: 2024-10-01T10:35:51.230Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: This Article Describes Solving R9 Driver Issues on Windows 10 Platform
excerpt: This Article Describes Solving R9 Driver Issues on Windows 10 Platform
keywords: Windows 10 Radeon Graphics Fixes,R9 Chipset Troubleshooting Guide,Win10 Driver Update Assistance,AMD GPU R9 Error Resolution,Solving Windows PC Graphics Problems,Optimize Radeon Performance on 10,R9 Driver Compatibility for Windows 10
thumbnail: https://thmb.techidaily.com/4b1d432d185a9307d4c64d844f91526f6a3048c24d149908b382d0c549a92a65.jpg
---

## Solving R9 Driver Issues on Windows 10 Platform

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
<li><a href="https://facebook-video-recording.techidaily.com/new-the-mysterious-virtual-trove-anonymitys-hidden-gems-of-2023-for-2024/"><u>[New] The Mysterious Virtual Trove - Anonymity's Hidden Gems of 2023 for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-premium-web-outlets-for-gift-boxes-that-speak-to-you/"><u>[Updated] Premium Web Outlets for Gift Boxes That Speak to You</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-androids-superior-hd-vids-discover-the-best-apps/"><u>2024 Approved Android's Superior HD Vids Discover the Best Apps</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/asymmetric-screen-aligned-on-notebooks/"><u>Asymmetric Screen Aligned on Notebooks</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/banishing-blue-screen-solve-wdf-crashes-on-winos/"><u>Banishing Blue Screen: Solve WDF Crashes on WinOS</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/clearing-up-unresponsive-black-screen-cursor/"><u>Clearing Up Unresponsive Black Screen, Cursor</u></a></li>
<li><a href="https://some-guidance.techidaily.com/convertidor-online-gratuito-de-webm-a-swf-movavi/"><u>Convertidor Online Gratuito De WEBM a SWF - Movavi</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/eradicating-plex-streaming-faults-in-windows-11/"><u>Eradicating Plex Streaming Faults in Windows 11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/flickering-screen-follow-this-quick-asus-guide-to-solve-it/"><u>Flickering Screen? Follow This Quick ASUS Guide to Solve It</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-do-you-get-sun-stone-evolutions-in-pokemon-for-realme-v30t-drfone-by-drfone-virtual-android/"><u>How Do You Get Sun Stone Evolutions in Pokémon For Realme V30T? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-lost-data-from-infinix-by-fonelab-android-recover-data/"><u>How to recover lost data from Infinix ?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-icloud-on-iphone-6-plus-smoothly-by-drfone-ios/"><u>How To Remove iCloud On iPhone 6 Plus Smoothly</u></a></li>
<li><a href="https://driver-install.techidaily.com/install-amped-80211n-usb-wireless-adapter-netgear/"><u>Install Amped 802.11N USB Wireless Adapter - NETGEAR</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/instant-restoration-busting-displayport-silence/"><u>Instant Restoration: Busting DisplayPort Silence</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/instruction-manual-for-launching-safe-mode-in-windows-8-graphics-driver-expulsion/"><u>Instruction Manual for Launching Safe Mode in Windows 8, Graphics Driver Expulsion</u></a></li>
<li><a href="https://sound-issues.techidaily.com/nvidia-hd-audio-not-working-heres-how-to-restore-your-sound/"><u>NVIDIA HD Audio Not Working? Here’s How to Restore Your Sound</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-obscured-views-in-twitch-video/"><u>Overcoming Obscured Views in Twitch Video</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/quick-fix-guide-graphics-cards-with-nvidia-gpu/"><u>Quick-Fix Guide: Graphics Cards with NVIDIA GPU</u></a></li>
<li><a href="https://techtrends.techidaily.com/troubleshooting-tips-for-when-mfcdll-is-not-detected-or-lost/"><u>Troubleshooting Tips for When mfc지오.dll Is Not Detected or Lost</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1006793/11832" target="_top" id="1006793">
  <img src="//a.impactradius-go.com/display-ad/11832-1006793" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1006793/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

