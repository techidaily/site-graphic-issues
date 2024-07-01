---
title: Overcoming R9 Display Problems on Windows 10
date: 2024-06-30T11:15:02.948Z
updated: 2024-07-01T11:15:02.948Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: This Article Describes Overcoming R9 Display Problems on Windows 10
excerpt: This Article Describes Overcoming R9 Display Problems on Windows 10
keywords: Overcoming R9 Display Problems,Windows 10 Display Issues Fix,Solutions for R9 Screen Errors,Troubleshooting Windows 10 Graphics,Resolving R9 Display Glitches on PC,Fixing Windows 10 LCD Display Problems,Addressing R9 Screen Flickering Issue
thumbnail: https://thmb.techidaily.com/7c8eb4a6751ebbb720d8baa15eb6264cc6e760acb0b1ed4fef37387dcca189b5.jpg
---

## Overcoming R9 Display Problems on Windows 10

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
<li><a href="https://graphic-issues.techidaily.com/unleash-system-potential-by-excising-graphics-drivers/"><u>Unleash System Potential by Excising Graphics Drivers</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/accelerate-visuals-upgrade-intel-3000-in-windows-11/"><u>Accelerate Visuals: Upgrade Intel 3000 in Windows 11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/lenovo-monitor-glitches-stabilize-screens/"><u>Lenovo Monitor Glitches: Stabilize Screens</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-710-screen-settings-preservation-how-to-fix-fixing-done/"><u>Windows 7/10 Screen Settings Preservation - How to Fix [Fixing Done]</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolve-tear-free-display-technology/"><u>Resolve Tear-Free Display Technology</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-10-invisible-fullscreen-window/"><u>Windows 10: Invisible Fullscreen Window?</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolved-amd-radeon-r9-display-problems-on-win10/"><u>Resolved AMD Radeon R9 Display Problems on Win10</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/tidying-up-win-os-graphics-render-with-fixes/"><u>Tidying up Win OS Graphics Render with Fixes</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/stop-screen-blunders-in-systems-pc/"><u>Stop Screen Blunders in Systems (PC)</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/enhanced-rendering-on-windows-with-latest-nvidia-geforce-drivers/"><u>Enhanced Rendering on Windows with Latest Nvidia GeForce Drivers</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-melody-meets-momentum-harmonizing-sound-with-imagery/"><u>[New] 2024 Approved  Melody Meets Momentum  Harmonizing Sound with Imagery</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-the-comprehensive-tutorial-on-detaching-audible-elements-from-video-clips-for-2024/"><u>Updated The Comprehensive Tutorial on Detaching Audible Elements From Video Clips for 2024</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-the-complete-handbook-to-converting-audio-files-like-a-pro/"><u>New 2024 Approved The Complete Handbook to Converting Audio Files Like a Pro</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-vivo-y78plus-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Vivo Y78+ Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/ae-presets-unleashed-10-essential-design-principles/"><u>AE Presets Unleashed  10 Essential Design Principles</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-simplified-mac-imaging-mastering-5-easy-screenshot-methods/"><u>[Updated] In 2024, Simplified Mac Imaging  Mastering 5 Easy Screenshot Methods</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-4-ways-to-unlock-iphone-12-to-use-usb-accessories-without-passcode-drfone-by-drfone-ios/"><u>In 2024, 4 Ways to Unlock iPhone 12 to Use USB Accessories Without Passcode | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-fast-track-to-using-ez-grabber-effectively-and-efficiently/"><u>[New] In 2024, Fast Track to Using EZ Grabber Effectively & Efficiently</u></a></li>
<li><a href="https://extra-resources.techidaily.com/tips-on-using-uavs-creatively-in-filmmaking/"><u>Tips on Using UAVs Creatively in Filmmaking</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-masterful-approach-to-creating-attractive-yt-summaries/"><u>[Updated] 2024 Approved  Masterful Approach to Creating Attractive YT Summaries</u></a></li>
</ul></div>
