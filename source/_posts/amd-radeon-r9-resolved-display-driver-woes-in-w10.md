---
title: "AMD Radeon R9: Resolved Display Driver Woes in W10"
date: 2024-07-11T17:47:58.428Z
updated: 2024-07-12T17:47:58.428Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: "This Article Describes AMD Radeon R9: Resolved Display Driver Woes in W10"
excerpt: "This Article Describes AMD Radeon R9: Resolved Display Driver Woes in W10"
keywords: AMD Radeon,R9 Graphics Card,Windows 10 Compatibility,Display Driver Fixes,Resolved Woes,W10 Performance Issues,Radeon R9 Updates
thumbnail: https://thmb.techidaily.com/250855bb01ff5d1f68da39bedfd2fea2571983e53726cd5cc186abc1510baddd.jpg
---

## AMD Radeon R9: Resolved Display Driver Woes in W10

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
<li><a href="https://graphic-issues.techidaily.com/deciphering-digital-enhancement-enter-the-world-of-4k/"><u>Deciphering Digital Enhancement: Enter the World of 4K</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/solved-cominterop-failure-windows-system/"><u>Solved: COMInterop Failure Windows System</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/methodical-approach-to-cease-lenovo-screenshake/"><u>Methodical Approach to Cease Lenovo Screenshake</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/ui-graphics-fix-windows-system-restored/"><u>UI Graphics Fix: Windows System Restored</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/preventing-gpu-crashes-while-preserving-computer-uptime/"><u>Preventing GPU Crashes While Preserving Computer Uptime</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/unlock-apple-iphone-14-plus-without-passcode-easily-by-drfone-ios/"><u>Unlock Apple iPhone 14 Plus Without Passcode Easily</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/tackling-r9-display-issues-on-windows-11-successfully/"><u>Tackling R9 Display Issues on Windows 11 Successfully</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/missing-fullscreen-window-on-monitor-with-win11/"><u>Missing Fullscreen Window on Monitor with Win11</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/windows-audio-enhancement-top-ten-applications-to-transform-your-music-experience/"><u>Windows Audio Enhancement Top Ten Applications to Transform Your Music Experience</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/step-by-step-guide-activating-windows-8-safety-measures-gpu-uninstallation/"><u>Step-by-Step Guide: Activating Windows 8 Safety Measures, GPU Uninstallation</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-part-of-the-touch-screen-not-working-on-honor-play-8t-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Part of the Touch Screen Not Working on Honor Play 8T | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/restoring-right-side-up-display-in-windows-10-fixed/"><u>Restoring Right Side Up Display in Windows 10 [Fixed]</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/realigning-monitor-horizontal-edges/"><u>Realigning Monitor Horizontal Edges</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/mended-display-issue-by-nvidia-driver-resolved/"><u>[Mended] Display Issue by Nvidia Driver Resolved</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/strategies-to-tackle-c1900101-in-windows-setup-process/"><u>Strategies to Tackle C1900101 in Windows Setup Process</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/system-alert-cleared-nvidia-display-responding-anew/"><u>System Alert Cleared: NVidia Display Responding Anew</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fix-for-stuck-windows-11-screen-dpi-dots-per-inch/"><u>Fix for Stuck Windows 11 Screen DPI (Dots Per Inch)</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/how-to-boost-your-lenovo-screens-light/"><u>How To Boost Your Lenovo Screens' Light</u></a></li>
<li><a href="https://audio-editing.techidaily.com/ultimate-tutorial-how-to-record-audio-on-windows-10/"><u>Ultimate Tutorial How to Record Audio on Windows 10</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/introducing-new-amd-hd-6950-drivers-for-w11-os/"><u>Introducing New AMD HD 6950 Drivers for W11 OS</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/win10-screen-problems-missing-fullscreen-mode/"><u>Win10 Screen Problems: Missing Fullscreen Mode</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/dxgkrnlsys-bluescreen-of-death-fixing-in-windows/"><u>dxgkrnl.sys BlueScreen of Death: Fixing in Windows</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-unlock-potential-a-list-of-must-try-bots-in-discord/"><u>[New] Unlock Potential  A List of Must-Try Bots in Discord</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-hardware-hurdles-with-intel-drivers/"><u>Overcoming Hardware Hurdles with Intel Drivers</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/tech-overcoming-windows-bluescreen-dxgkrnlsys/"><u>[Tech] Overcoming Windows BlueScreen dxgkrnl.sys</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/quickly-erase-startup-anomalies/"><u>Quickly Erase Startup Anomalies</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/gpu-error-43-the-solution-found/"><u>GPU Error 43 - The Solution Found</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/nvidia-and-intel-integration-workaround-on-win10-successfully-addressed/"><u>NVIDIA & Intel Integration Workaround on Win10 Successfully Addressed</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-10-refresh-rate-fix/"><u>Windows 10 Refresh Rate Fix</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/enhancing-god-of-war-player-experience/"><u>Enhancing 'God of War' Player Experience</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-a-compreayers-pathway-to-efficient-screen-recording-via-zd-software-for-2024/"><u>[New] A Compreayer's Pathway to Efficient Screen Recording via ZD Software for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/meeting-basic-requirements-running-intel-drivers-on-budget-pc/"><u>Meeting Basic Requirements: Running Intel Drivers on Budget PC</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/controlling-win11-display-extensiveness/"><u>Controlling Win11 Display Extensiveness</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-realme-c67-5g-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Realme C67 5G? | Dr.fone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-the-ultimate-list-10-best-free-and-paid-android-video-editing-apps-2023/"><u>In 2024, The Ultimate List 10 Best Free and Paid Android Video Editing Apps 2023</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/apex-legends-efficient-enjoyable-experience/"><u>Apex Legends: Efficient, Enjoyable Experience</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/save-issue-resolved-screen-preferences-update/"><u>Save Issue: Resolved - Screen Preferences Update</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-producing-channel-trailer-synopses-a-guide/"><u>[Updated] In 2024, Producing Channel Trailer Synopses  A Guide</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/smooth-visual-ui-experience-reinstated-on-win-pc/"><u>Smooth Visual UI Experience Reinstated on Win PC</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-oppo-reno-10-pro-5g-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Oppo Reno 10 Pro 5G If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fix-display-driver-nvlddmkm-stopped-responding-and-has-successfully-recovered/"><u>Fix: Display Driver Nvlddmkm Stopped Responding and Has Successfully Recovered</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/precision-in-security-protocol-safe-mode-entrance-and-graphic-card-drivers-deletion/"><u>Precision in Security Protocol: Safe Mode Entrance & Graphic Card Drivers Deletion</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windowing-fine-tuning-win11-display/"><u>Windowing: Fine-Tuning Win11 Display</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/graphics-fail-device-unrecognized/"><u>Graphics Fail: Device Unrecognized</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/graphics-framework-fails-to-load/"><u>Graphics Framework Fails to Load</u></a></li>
</ul></div>
