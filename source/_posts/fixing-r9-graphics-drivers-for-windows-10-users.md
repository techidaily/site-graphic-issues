---
title: Fixing R9 Graphics Drivers for Windows 10 Users
date: 2024-10-15T11:30:51.002Z
updated: 2024-10-17T18:18:54.798Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: This Article Describes Fixing R9 Graphics Drivers for Windows 10 Users
excerpt: This Article Describes Fixing R9 Graphics Drivers for Windows 10 Users
keywords: Fix R9 Graphics Driver,Windows 10 R9 Graphics,Update NVIDIA Drivers,GeForce R9 Driver Troubleshooting,Windows 10 Graphics Drivers Upgrade Guide,NVIDIA Driver Installation Steps,R9 Graphics Drivers Compatibility with Windows 10
thumbnail: https://thmb.techidaily.com/b432bdff253fde3d555eb0e4e70a3a08238022a0a92405de9a612b975012aa5f.jpg
---

## Fixing R9 Graphics Drivers for Windows 10 Users

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
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-mastering-facebook-cover-videos-tips-and-configuration-guide/"><u>[New] 2024 Approved Mastering Facebook Cover Videos Tips & Configuration Guide</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-overview-fb-video-dimension-categories-for-2024/"><u>[New] Overview FB Video Dimension Categories for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-pivoting-passions-into-profits-your-vlogs-revenue-roadmap/"><u>[Updated] In 2024, Pivoting Passions Into Profits Your Vlog's Revenue Roadmap</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-pro-choice-top-picks-of-10-premium-vimeo-video-download-tools/"><u>[Updated] Pro Choice Top Picks of 10 Premium Vimeo Video Download Tools</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-uniting-zooms-power-with-facebook-live-streaming-for-2024/"><u>[Updated] Uniting Zoom's Power with Facebook LIVE Streaming for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/altering-windows-10-display-mode/"><u>Altering Windows 10 Display Mode</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/create-dramatic-effects-top-strategies-for-epic-gopro-videos/"><u>Create Dramatic Effects Top Strategies for Epic GoPro Videos</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/display-system-init-issues/"><u>Display System Init Issues</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-successfully-bypass-icloud-activation-lock-from-apple-iphone-13-pro-by-drfone-ios/"><u>In 2024, How to Successfully Bypass iCloud Activation Lock from Apple iPhone 13 Pro</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/instant-recovery-from-apex-glitches/"><u>Instant Recovery From Apex Glitches</u></a></li>
<li><a href="https://win-tutorials.techidaily.com/schnelle-und-effiziente-datentransfermoglichkeiten-von-ihrem-pc-zu-einem-usb-stick-entdecken-der-4-besten-wege/"><u>Schnelle Und Effiziente Datentransfermöglichkeiten Von Ihrem PC Zu Einem USB-Stick – Entdecken Der 4 Besten Wege!</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/screen-calibration-in-win10-successful/"><u>Screen Calibration in Win10 Successful</u></a></li>
<li><a href="https://location-social.techidaily.com/simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-oneplus-nord-n30-5g-drfone-by-drfone-virtual-android/"><u>Simple and Effective Ways to Change Your Country on YouTube App Of your OnePlus Nord N30 5G | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/stop-drivers-from-triggering-minecraft-collapse/"><u>Stop Drivers From Triggering Minecraft Collapse</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/the-hidden-glitch-dispelled-legions-direct-x-solution-found/"><u>The Hidden Glitch Dispelled: Legion's Direct X Solution Found</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082520/7443" target="_top" id="2082520">
  <img src="//a.impactradius-go.com/display-ad/7443-2082520" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082520/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

