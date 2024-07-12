---
title: Fixing R9 Graphics Drivers for Windows 10 Users
date: 2024-07-11T17:56:40.419Z
updated: 2024-07-12T17:56:40.419Z
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
<li><a href="https://graphic-issues.techidaily.com/lenovo-touch-screen-not-working-solved/"><u>Lenovo Touch Screen Not Working [SOLVED]</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/successful-direct3d-deployment/"><u>Successful Direct3D Deployment</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/the-elite-list-of-win11s-screen-recording-apps/"><u>The Elite List of Win11's Screen Recording Apps</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-free-top-10-best-online-video-editors-without-watermark/"><u>New FREE Top 10 Best Online Video Editors without Watermark</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/righted-portable-computer-orientation/"><u>Righted Portable Computer Orientation</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/firmware-update-blackened-vision/"><u>Firmware Update: Blackened Vision</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-instagram-video-size-matters-understanding-aspect-ratios-for-better-engagement/"><u>Updated 2024 Approved Instagram Video Size Matters Understanding Aspect Ratios for Better Engagement</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-the-ultimate-roundup-best-budget-friendly-virtual-calls-for-2024/"><u>[New] The Ultimate Roundup  Best Budget-Friendly Virtual Calls for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/leveraging-built-in-recorders-on-mate-1020-and-p2010-series-to-screen-capture/"><u>Leveraging Built-In Recorders on Mate 10/20 & P20/10 Series to Screen Capture</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-windows-10-advanced-screen-recorder-software/"><u>In 2024, Windows 10 Advanced Screen Recorder Software</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/non-fullscreen-windows-on-monitor-win11/"><u>Non-Fullscreen Windows on Monitor, Win11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/pc-peace-of-mind-with-fixed-fallout-4-issues/"><u>PC Peace of Mind with Fixed Fallout 4 Issues</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-7-and-intel-graphics-upgrade-a-user-friendly-guide/"><u>Windows 7 and Intel Graphics Upgrade: A User-Friendly Guide</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-android-screen-capture-kings-the-ultimate-8-free-guide-for-2024/"><u>[Updated] Android Screen Capture Kings  The Ultimate 8-Free Guide for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/permanently-put-a-stop-to-screen-shimmer/"><u>Permanently Put a Stop to Screen Shimmer</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/tailoring-god-of-war-for-exciting-gameplay/"><u>Tailoring 'God of War' For Exciting Gameplay</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolving-lenovo-non-responding-touch-interface/"><u>Resolving Lenovo Non-Responding Touch Interface</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/crystal-clear-windows-no-more-fuzz/"><u>Crystal-Clear Windows, No More Fuzz</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/cutting-edge-visuals-updated-nvidia-geforce-for-windows-10/"><u>Cutting-Edge Visuals: Updated NVIDIA GeForce for Windows 10</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/new-graphics-horizon-radeon-hd-6950-updates-for-windows-10-users/"><u>New Graphics Horizon: Radeon HD 6950 Updates for Windows 10 Users</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/regulating-window-size-for-win11/"><u>Regulating Window Size for Win11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/how-to-reclaim-color-on-stuck-asus-displays/"><u>How to Reclaim Color on Stuck-Asus Displays</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-a-working-guide-for-pachirisu-pokemon-go-map-on-motorola-moto-g04-drfone-by-drfone-virtual-android/"><u>In 2024, A Working Guide For Pachirisu Pokemon Go Map On Motorola Moto G04 | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/transform-pc-performance-with-latest-geforce-210-drivers/"><u>Transform PC Performance with Latest GeForce 210 Drivers</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/solving-the-vanished-gddr6x-issue/"><u>Solving the Vanished GDDR6x Issue</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-premier-picture-preservation-websites/"><u>[Updated] Premier Picture Preservation Websites</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/addressing-reflective-window-issue-in-windows-11/"><u>Addressing Reflective Window Issue in Windows 11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/laptop-displays-when-not-to-panic-but-fixes/"><u>Laptop Displays: When Not to Panic, But Fixes</u></a></li>
<li><a href="https://extra-information.techidaily.com/discover-top-online-rhythm-trackers-today-free/"><u>Discover Top Online Rhythm Trackers Today! (FREE)</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/geforce-1060-get-new-nvidia-drivers-now/"><u>GeForce 1060: Get New Nvidia Drivers Now</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-secrets-to-subtle-sound-diminishment-in-lumafusion/"><u>2024 Approved  The Secrets to Subtle Sound Diminishment in Lumafusion</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolving-crash-keep-fallout-4-running-smoothly-on-windows/"><u>Resolving Crash: Keep Fallout 4 Running Smoothly on Windows</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/pixels-perfection-achieved-display-settings-saved/"><u>Pixels Perfection Achieved: Display Settings Saved</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-10-telegram-spy-tools-on-xiaomi-13-ultra-for-parents-drfone-by-drfone-virtual-android/"><u>In 2024, Top 10 Telegram Spy Tools On Xiaomi 13 Ultra for Parents | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-top-5-tecno-spark-20c-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>In 2024, Top 5 Tecno Spark 20C Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-premiering-popularity-amazon-prime-tweets-of-23/"><u>[New] In 2024, Premiering Popularity  Amazon Prime Tweets of '23</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/flat-screen-fix-for-asymmetrical-use/"><u>Flat-Screen Fix for Asymmetrical Use</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/full-screen-window-problem-monitor-with-win11/"><u>Full-Screen Window Problem: Monitor with Win11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-youtubes-copyright-landscape-decoded-a-complete-analysis/"><u>[New] YouTube's Copyright Landscape Decoded  A Complete Analysis</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-in-2024-the-ultimate-camtasia-shortcut-speeding-up-and-slowing-down-videos/"><u>New In 2024, The Ultimate Camtasia Shortcut Speeding Up and Slowing Down Videos</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/reversescreenposition-advice/"><u>ReverseScreenPosition Advice</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-is-inshot-a-game-changer-in-video-editing-tools/"><u>2024 Approved  Is InShot a Game Changer in Video Editing Tools?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-find-my-iphone-without-apple-id-on-your-iphone-7-by-drfone-ios/"><u>How to Remove Find My iPhone without Apple ID On your iPhone 7?</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-samsung-galaxy-f04-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Your Samsung Galaxy F04 Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-poco-x6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Poco X6 Pro | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixed-monitor-not-displaying-full-screen-windows-11/"><u>Fixed: Monitor Not Displaying Full Screen Windows 11</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-edit-video-tags-with-ease-best-tools-for-windows-and-mac/"><u>New Edit Video Tags with Ease Best Tools for Windows and Mac</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/bringing-alive-the-idle-gpu-fan/"><u>Bringing Alive the Idle GPU Fan</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-az-video-grabber-in-depth-app-analysis-and-diversions-for-2024/"><u>[New] AZ Video Grabber  In-Depth App Analysis & Diversions for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolved-laptop-display-flashes-unstably/"><u>Resolved: Laptop Display Flashes Unstably</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/immediate-solution-tidy-up-screen-ghosting/"><u>Immediate Solution: Tidy Up Screen Ghosting</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/how-to-correctly-use-your-graphics-card-on-windows-1011/"><u>How to Correctly Use Your Graphics Card on Windows 10/11</u></a></li>
</ul></div>
