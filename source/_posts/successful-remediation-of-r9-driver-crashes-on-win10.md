---
title: Successful Remediation of R9 Driver Crashes on Win10
date: 2024-07-11T17:53:03.356Z
updated: 2024-07-12T17:53:03.356Z
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
<li><a href="https://graphic-issues.techidaily.com/uninterrupted-videos-at-your-fingertips/"><u>Uninterrupted Videos at Your Fingertips</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-2024-approved-best-12-ai-video-generators-to-pick/"><u>Updated 2024 Approved Best 12 AI Video Generators to Pick</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/dell-device-visual-stability-no-more-flickering-issues/"><u>Dell Device Visual Stability: No More Flickering Issues</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/activate-gpu-on-laptop-windows-1011-fixes/"><u>Activate GPU on Laptop: Windows 10/11 Fixes</u></a></li>
<li><a href="https://howto.techidaily.com/reasons-for-google-pixel-8-pro-stuck-on-startup-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Google Pixel 8 Pro Stuck on Startup Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/the-complete-guide-to-implementing-siri-speech-on-tiktok-platforms/"><u>The Complete Guide to Implementing Siri Speech on TikTok Platforms</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-unveiling-the-hidden-potential-of-screen-recording-on-mi-11-devices/"><u>2024 Approved  Unveiling the Hidden Potential of Screen Recording on Mi 11 Devices</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/graphics-absent-system-error/"><u>Graphics Absent: System Error</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/solved-nvidia-display-driver-stopped-working-and-has-recovered/"><u>[Solved] Nvidia Display Driver Stopped Working and Has Recovered</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/winerror-unhandled-exception-wdf-blue-screen/"><u>WinError: Unhandled Exception, WDF Blue Screen</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/a-dormant-screen-at-work-steps-for-revival/"><u>A Dormant Screen at Work: Steps for Revival</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/ensuring-geforce-7025-works-with-windows-11/"><u>Ensuring GeForce 7025 Works with Windows 11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/vanishing-polaris-video-card-fixed/"><u>Vanishing Polaris Video Card Fixed</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-device-entry-guide-to-googles-video-conferencing-for-2024/"><u>[Updated] Device Entry Guide to Google's Video Conferencing for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/steps-to-correct-error-code-c1900101-when-installing-windows-11/"><u>Steps to Correct Error Code C1900101 When Installing Windows 11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-1011-re-enabling-graphics-card-functions/"><u>Windows 10/11: Re-Enabling Graphics Card Functions</u></a></li>
<li><a href="https://facebook.techidaily.com/chatting-with-flair-the-power-of-textual-variation/"><u>Chatting with Flair: The Power of Textual Variation</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-unleashing-connectivity-setting-up-a-zoom-call-on-android/"><u>2024 Approved  Unleashing Connectivity  Setting Up a Zoom Call on Android</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-truth-in-frames-how-to-validate-yourselfies-on-instagram/"><u>2024 Approved  Truth in Frames  How to Validate Yourselfies on Instagram</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-big-sur-tech-requirements-a-quick-reference-guide/"><u>[New] Big Sur Tech Requirements  A Quick Reference Guide</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/disabled-gpu-how-to-turn-it-on-for-windows-1011/"><u>Disabled GPU - How to Turn It On for Windows 10/11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolved-graphics-hurdles-with-direct3d-achieved-max-gpu-speed/"><u>Resolved Graphics Hurdles with Direct3D, Achieved Max GPU Speed</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-9-secrets-to-unlocking-the-full-potential-of-window-11/"><u>In 2024, 9 Secrets to Unlocking the Full Potential of WINDOW 11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/god-of-war-polishing-combat-intuition/"><u>'God of War': Polishing Combat Intuition</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/streamline-your-gameplay-in-anthem/"><u>Streamline Your Gameplay in Anthem</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-quality-improvement-for-skype-video-calls/"><u>[New] In 2024, Quality Improvement for Skype Video Calls</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-boosting-brand-presence-with-innovative-snapads/"><u>[Updated] Boosting Brand Presence with Innovative SnapAds</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/stream-problems-solved-in-windows-10-update/"><u>Stream Problems Solved in Windows 10 Update</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/your-clear-vision-free-of-flickers-intrusion/"><u>Your Clear Vision, Free of Flicker's Intrusion</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/clear-bright-winscreen/"><u>Clear, Bright WinScreen</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/solved-nvidia-installer-cannot-continue/"><u>[Solved] NVIDIA Installer Cannot Continue</u></a></li>
<li><a href="https://android-location.techidaily.com/10-fake-gps-location-apps-on-android-of-your-vivo-s17t-drfone-by-drfone-virtual/"><u>10 Fake GPS Location Apps on Android Of your Vivo S17t | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/swap-screen-positioning-on-windowed-pcs/"><u>Swap Screen Positioning on Windowed PCs</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-beyond-the-lens-the-complete-selfie-confirmation-on-ig/"><u>[Updated] Beyond the Lens  The Complete Selfie Confirmation on IG</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/bad-video-card-drivers-crash-minecraft-on-windows-solved/"><u>Bad Video Card Drivers Crash Minecraft on Windows [Solved]</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/steady-screen-stable-workflows/"><u>Steady Screen, Stable Workflows</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/eliminate-video-card-errors-from-minecraft/"><u>Eliminate Video Card Errors From Minecraft</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/zoom-perfectionists-manual-reviving-faulty-cameras/"><u>Zoom Perfectionist's Manual - Reviving Faulty Cameras</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-unlocking-the-secrets-to-effective-screen-capturing-with-apeaksoft/"><u>[Updated] In 2024, Unlocking the Secrets to Effective Screen Capturing with Apeaksoft</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-disable-auto-record-with-one-click-on-quicktime-for-2024/"><u>[New] Disable Auto-Record with One Click on QuickTime for 2024</u></a></li>
</ul></div>
