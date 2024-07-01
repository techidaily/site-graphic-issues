---
title: Successful Remediation of R9 Driver Crashes on Win10
date: 2024-06-30T11:30:37.983Z
updated: 2024-07-01T11:30:37.983Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: This Article Describes Successful Remediation of R9 Driver Crashes on Win10
excerpt: This Article Describes Successful Remediation of R9 Driver Crashes on Win10
keywords: Win10 Recovery Tools,R9 Driver Troubleshooting Win10,Win10 Crash Fix Methods,NVIDIA Drivers Win10 Restoration,Driver Recovery Steps Win10,Stable NVIDIA Drivers on Windows 10,R9 Win10 Compatibility Troubleshooting
thumbnail: https://thmb.techidaily.com/ce2c767b4ea66790422350863194f4cca1e1e1f1b31e78a51ee237f509439d21.jpg
---

## Successful Remediation of R9 Driver Crashes on Win10

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
<li><a href="https://graphic-issues.techidaily.com/video-output-stabilized-22-resolved/"><u>Video Output Stabilized: #22 Resolved</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/graphics-module-doesnt-start-up/"><u>Graphics Module Doesn't Start Up</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/nvidia-card-not-compatible-with-windows-11-fix/"><u>Nvidia Card Not Compatible with Windows 11 [Fix]</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/troubleshooting-c1900101-error-on-windows-11-setup/"><u>Troubleshooting C1900101 Error on Windows 11 Setup</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/critical-card-detection-failure/"><u>Critical: Card Detection Failure</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/win11-shadowed-cursor-reclaimed/"><u>Win11 Shadowed, Cursor Reclaimed</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/quench-flickering-in-windows-11-screens/"><u>Quench Flickering in Windows 11 Screens</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/1719817588692-flash-free-visual-experience-now/"><u>Flash-Free Visual Experience Now!</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-worlds-finest-screen-recording-software-no-deadline/"><u>[New] World's Finest Screen Recording Software (No Deadline)</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-pursuit-for-full-viewable-content-from-friends-on-direct-chat-platforms/"><u>[Updated] In 2024, Pursuit for Full Viewable Content From Friends on Direct Chat Platforms</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-remove-google-frp-lock-on-realme-narzo-60x-5g-by-drfone-android-unlock-remove-google-frp/"><u>How to remove Google FRP Lock on Realme Narzo 60x 5G</u></a></li>
<li><a href="https://some-skills.techidaily.com/top-tier-affordable-photo-enhancement-software-online-for-2024/"><u>Top-Tier Affordable Photo Enhancement Software Online for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-entering-the-world-of-content-creation-sign-up-tutorial/"><u>2024 Approved  Entering the World of Content Creation  Sign Up Tutorial</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/ideal-steadicams-for-captivating-high-quality-shoots-on-your-dslr-camera/"><u>Ideal Steadicams for Captivating, High-Quality Shoots on Your DSLR Camera</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ring-the-art-of-vlogging-your-ultimate-journey-begins-here-for-2024/"><u>Mastering The Art of Vlogging  Your Ultimate Journey Begins Here for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-top-8-sites-to-get-free-green-screen-backgrounds-and-footage/"><u>2024 Approved  Top 8 Sites to Get Free Green Screen Backgrounds and Footage</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-country-calm-a-curated-list-of-soothing-tunes-to-dance-and-unwind-on-tiktok/"><u>[New] In 2024, Country Calm  A Curated List of Soothing Tunes to Dance & Unwind On TikTok</u></a></li>
</ul></div>
