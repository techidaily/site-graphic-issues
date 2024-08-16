---
title: Fixing R9 Graphics Drivers for Windows 10 Users
date: 2024-08-15T07:19:53.552Z
updated: 2024-08-16T07:19:53.552Z
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
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-clearing-photos-expert-background-takedown-in-photopea/"><u>[New] 2024 Approved  Clearing Photos  Expert Background Takedown in Photopea</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-humor-hacks-techniques-for-parody-filmmaking/"><u>[New] 2024 Approved  Humor Hacks  Techniques for Parody Filmmaking</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-depth-screen-capturing-a-resourceful-guide-for-dell-users/"><u>[New] In-Depth Screen Capturing  A Resourceful Guide for Dell Users</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-ultimate-guide-5-top-earning-instagram-strategies/"><u>[New] Ultimate Guide  5 Top-Earning Instagram Strategies</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/solved-laptop-not-using-gpu-windows-1111/"><u>[SOLVED] Laptop Not Using GPU Windows 11/11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-igtv-video-sharing-to-facebook-explained-in-3-ways-for-2024/"><u>[Updated] IGTV Video Sharing to Facebook Explained in 3 Ways for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-8-best-popular-instagram-after-effects-templates/"><u>[Updated] In 2024, 8 Best Popular Instagram After Effects Templates</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-streamline-your-gameplay-professional-ps4-recording-tips/"><u>[Updated] In 2024, Streamline Your Gameplay  Professional PS4 Recording Tips</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-from-amateur-to-expert-15-must-knows-in-tiktok-video-edits/"><u>2024 Approved  From Amateur to Expert  15 Must-Knows in TikTok Video Edits</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-seamless-integration-vimeo-uploads-with-windows-media-center/"><u>2024 Approved  Seamless Integration  Vimeo Uploads with Windows Media Center</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/adjusting-aspect-ratios-for-a-balanced-display-on-windows-10/"><u>Adjusting Aspect Ratios for a Balanced Display on Windows 10</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/advantages-in-god-of-war-a-closer-look/"><u>Advantages in 'God of War': A Closer Look</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/bluelight-on-win-dxgkrnlsys-issue-tackled/"><u>BlueLight on Win - dxgkrnl.sys Issue Tackled</u></a></li>
<li><a href="https://techtrends.techidaily.com/choosing-the-right-stereo-speakers-a-guide-to-making-wise-purchases/"><u>Choosing the Right Stereo Speakers: A Guide to Making Wise Purchases</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/comprehensively-addressing-r9-driver-issues-on-w10/"><u>Comprehensively Addressing R9 Driver Issues on W10</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/dispel-darkness-of-dazzling-displays/"><u>Dispel Darkness of Dazzling Displays</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-pictures-from-a2-by-fonelab-android-recover-pictures/"><u>Easy steps to recover deleted pictures from A2.</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/effortlessly-upgrade-intel-graphics-plus-windows-11-drivers/"><u>Effortlessly Upgrade: Intel Graphics + Windows 11 Drivers</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/eliminated-visual-glitches-in-dell-ultrabook/"><u>Eliminated Visual Glitches in Dell Ultrabook</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/enhanced-system-response-fixed-comfailure-windows-based/"><u>Enhanced System Response: Fixed COMFailure Windows-Based</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/essential-guide-to-taming-lenovo-screen-flicker/"><u>Essential Guide to Taming Lenovo Screen Flicker</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/fast-fortnite-cover-art-techniques/"><u>Fast Fortnite Cover Art Techniques</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixing-flip-in-windows-11-display-settings/"><u>Fixing Flip in Windows 11 Display Settings</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-apple-iphone-14-data-from-ios-itunes-backup-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How to Recover Apple iPhone 14 Data From iOS iTunes Backup? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-remove-iphone-8-sim-lock-by-drfone-ios/"><u>How to Remove iPhone 8 SIM Lock?</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-revisiting-old-photos-sending-them-as-snaps-on-snapchat/"><u>In 2024, Revisiting Old Photos  Sending Them as Snaps on Snapchat</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unleash-your-contents-potential-for-1m-views-on-youtube/"><u>In 2024, Unleash Your Content's Potential for 1M Views on YouTube</u></a></li>
<li><a href="https://facebook.techidaily.com/is-confidential-communication-on-fb-reliable/"><u>Is Confidential Communication on FB Reliable?</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/lenovo-smarttouch-repair-completed-successfully/"><u>Lenovo SmartTouch Repair Completed Successfully</u></a></li>
<li><a href="https://youtube-help.techidaily.com/mastering-youtube-studio-ultimate-video-edits-techniques-for-2024/"><u>Mastering YouTube Studio  Ultimate Video Edits Techniques for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-unavailable-screen-options-barrier/"><u>Overcoming Unavailable Screen Options Barrier</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/solving-bug-spikes-on-civilization-v/"><u>Solving Bug Spikes on Civilization V</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-falsifying-gps-coordinates-on-smartphones-made-simple/"><u>Step-by-Step: Falsifying GPS Coordinates on Smartphones Made Simple</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/straightening-visual-horizon-lines/"><u>Straightening Visual Horizon Lines</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/successful-driver-installation-for-amd-in-windows-10/"><u>Successful Driver Installation for AMD in Windows 10</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/troubleshooting-lenovo-screen-refresh-rates/"><u>Troubleshooting Lenovo Screen Refresh Rates</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/win-gfx-issues-solved-interface-functioning-normal/"><u>Win GFX Issues Solved: Interface Functioning Normal</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/win11-powered-by-updated-nvidia-geforce-210-drivers/"><u>Win11 Powered by Updated NVIDIA GeForce 210 Drivers</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/win11-stabilize-your-vision/"><u>Win11: Stabilize Your Vision</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->