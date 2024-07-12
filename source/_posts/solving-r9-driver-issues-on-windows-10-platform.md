---
title: Solving R9 Driver Issues on Windows 10 Platform
date: 2024-07-11T17:56:10.332Z
updated: 2024-07-12T17:56:10.332Z
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
<li><a href="https://graphic-issues.techidaily.com/tackling-apex-glitches-head-on/"><u>Tackling Apex Glitches Head-On</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/reviving-silent-gpu-fans-to-life/"><u>Reviving Silent GPU Fans to Life</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-tracking-apps-to-track-lava-yuva-2-without-them-knowing-drfone-by-drfone-virtual-android/"><u>Top 5 Tracking Apps to Track Lava Yuva 2 without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/in-2024-maximizing-soundcloud-music-tips-for-mp3-conversion/"><u>In 2024, Maximizing Soundcloud Music Tips for MP3 Conversion</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-optimizing-youtube-content-for-higher-visibility/"><u>[Updated] Optimizing YouTube Content for Higher Visibility</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-extensive-review-gecata-recording-device-analysis/"><u>[Updated] 2024 Approved  Extensive Review  Gecata Recording Device Analysis</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-streamline-your-day-multitask-mastery-for-the-podcast-aficionado/"><u>[New] Streamline Your Day  Multitask Mastery for the Podcast Aficionado</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolving-netflix-stutter-after-upgraded-windows/"><u>Resolving Netflix Stutter After Upgraded Windows</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/no-light-after-driver-rollout/"><u>No Light After Driver Rollout</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/rectifying-radeon-r9-driver-errors-in-windows-11/"><u>Rectifying Radeon R9 Driver Errors in Windows 11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/optimizing-media-player-functionality-for-new-win11/"><u>Optimizing Media Player Functionality for New Win11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/refinement-of-greenscreen-footage-a-video-editors-mantra/"><u>Refinement of Greenscreen Footage: A Video Editor’s Mantra</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/charting-new-horizons-in-digital-clarity-4k-resolution/"><u>Charting New Horizons in Digital Clarity: 4K Resolution</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-revel-in-history-reactivating-deleted-reddit-articles/"><u>In 2024, Revel in History  Reactivating Deleted Reddit Articles</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/ending-windows-10-screen-flip-mishap/"><u>Ending Windows 10 Screen Flip Mishap</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-make-viral-reaction-videos-with-these-top-mobile-apps/"><u>Updated 2024 Approved Make Viral Reaction Videos with These Top Mobile Apps</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-10-black-screen-after-fall-creators-update-solved/"><u>Windows 10 Black Screen After Fall Creators Update [Solved]</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-pictures-from-edge-40-pro-by-fonelab-android-recover-pictures/"><u>How to Rescue Lost Pictures from Edge 40 Pro?</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/integrating-the-latest-intel-gpu-software-on-windows/"><u>Integrating the Latest Intel GPU Software on Windows</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/cured-directx-12-frame-timing-error/"><u>Cured DirectX 12 Frame Timing Error</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-error-code-963-on-google-play-of-xiaomi-14-ultra-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Error Code 963 on Google Play Of Xiaomi 14 Ultra | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-webcam-buying-simplified-the-best-10-options/"><u>[New] Webcam Buying Simplified  The Best 10 Options</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/saving-display-options-fix-in-win-7-and-10-solved/"><u>Saving Display Options: Fix in Win 7 & 10 [Solved]</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-expert-methods-for-win10-game-screen-recording-for-2024/"><u>[Updated] Expert Methods for Win10 Game Screen Recording for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolved-amd-radeon-r9-display-problems-on-win10/"><u>Resolved AMD Radeon R9 Display Problems on Win10</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/trim-oversized-display-settings-in-win-10/"><u>Trim Oversized Display Settings in WIN 10</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-remedies-to-address-instantaneous-failure-when-adding-a-folder-in-the-windows-onedrive-environment/"><u>Efficient Remedies to Address Instantaneous Failure when Adding a Folder in the Windows OneDrive Environment</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolved-unconventional-laptop-display-setting/"><u>Resolved Unconventional Laptop Display Setting</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-webm-video-compressors-the-best-online-webm-video-compressors/"><u>Updated 2024 Approved WebM Video Compressors The Best Online WebM Video Compressors</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/in-2024-amplify-your-tiktok-impact-precision-video-editing-with-pro-tools-on-mac/"><u>In 2024, Amplify Your TikTok Impact  Precision Video Editing with Pro Tools on Mac</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/how-to-fix-missing-windows-11-full-screen-on-monitor/"><u>How to Fix Missing Windows 11 Full Screen on Monitor</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-enhance-your-discord-interaction-mastering-the-art-of-pins/"><u>[Updated] In 2024, Enhance Your Discord Interaction  Mastering the Art of Pins</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-attract-more-viewers-boosting-your-youtube-following/"><u>[New] 2024 Approved  Attract More Viewers  Boosting Your YouTube Following</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/effortless-intel-3000-driver-fix-for-windows-10-users/"><u>Effortless Intel 3000 Driver Fix for Windows 10 Users</u></a></li>
<li><a href="https://vp-tips.techidaily.com/optimal-energy-kits-for-gopro-hero5-genuine-and-third-party-brands-for-2024/"><u>Optimal Energy Kits for GoPro Hero5 – Genuine and Third-Party Brands for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-free-video-looper-apps-for-desktop-and-mobile/"><u>2024 Approved Free Video Looper Apps for Desktop and Mobile</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-step-by-step-guide-to-creating-fb-slideshows/"><u>[New] Step-by-Step Guide to Creating FB Slideshows</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/how-to-get-asus-camera-operating-again/"><u>How to Get Asus Camera Operating Again</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/shrink-windows-interface-in-win-10/"><u>Shrink Windows Interface in WIN 10</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/troublesome-unsupported-graphics-cards-by-winoses/"><u>[TROUBLESOME] Unsupported Graphics Cards by WinOSes</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/solving-black-screen-issue-after-win11-fall-update/"><u>Solving Black Screen Issue After Win11 Fall Update</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-unveiling-the-top-8-instagram-ae-design-choices/"><u>In 2024, Unveiling the Top 8 Instagram AE Design Choices</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-pinnacletrack-audio-editor-comprehensive-mp3-tagging-capabilities-for-windows-and-mac/"><u>New 2024 Approved PinnacleTrack Audio Editor Comprehensive MP3 Tagging Capabilities for Windows & Mac</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/elevate-your-pc-experience-with-new-intel-graphics-driver/"><u>Elevate Your PC Experience with New Intel Graphics Driver</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/monitor-not-recognizing-fullscreen-windows-on-win10/"><u>Monitor Not Recognizing Fullscreen Windows on Win10</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-efficiently-recording-your-xbox-adventures-for-2024/"><u>[New] Efficiently Recording Your Xbox Adventures for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/switch-clash-top-10-intense-battles-to-play/"><u>Switch Clash  Top 10 Intense Battles to Play</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/get-the-newest-drivers-for-nvidias-gtx-1060/"><u>Get the Newest Drivers for Nvidia's GTX 1060</u></a></li>
<li><a href="https://article-tips.techidaily.com/from-battery-life-to-final-cut-a-drone-editors-journey/"><u>From Battery Life to Final Cut  A Drone Editor's Journey</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/quick-remedies-keep-fallout-4-playing-smoothly-on-windows/"><u>Quick Remedies: Keep Fallout 4 Playing Smoothly on Windows</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-no-cost-split-screen-video-editing-online-and-offline-tools-compared/"><u>New 2024 Approved No-Cost Split Screen Video Editing Online and Offline Tools Compared</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/enhance-performance-upgrade-intel-3000-on-windows-11/"><u>Enhance Performance: Upgrade Intel 3000 on Windows 11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/revitalized-gameplay-in-apex-legends/"><u>Revitalized Gameplay in Apex Legends</u></a></li>
<li><a href="https://win11.techidaily.com/stopping-user-initiated-windows-screen-shift/"><u>Stopping User-Initiated Windows Screen Shift</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-innovative-frameworks-for-efficient-iptv-recording-for-2024/"><u>[Updated] Innovative Frameworks for Efficient IPTV Recording for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-windows-arp-cache-how-to-empty-it/"><u>Decoding Windows ARP Cache: How to Empty It?</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-ishowu-audio-capture-review-for-2024/"><u>[Updated] IShowU Audio Capture Review for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/real-time-fix-for-jittery-videos/"><u>Real-Time Fix for Jittery Videos</u></a></li>
<li><a href="https://screen-recording.techidaily.com/effortless-and-accurate-how-to-capture-every-hulu-playback/"><u>Effortless and Accurate  How To Capture Every Hulu Playback</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/tips-to-avoid-gpu-fires-sustain-system-operation/"><u>Tips to Avoid GPU Fires: Sustain System Operation</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/reating-professional-edits-using-youtube-studio-editor-for-2024/"><u>[New] Creating Professional Edits Using YouTube Studio Editor for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-the-right-way-to-close-a-long-term-but-unneeded-linkedin-account/"><u>In 2024, The Right Way to Close a Long-Term but Unneeded LinkedIn Account</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/remediation-of-cominterface-error-windows-edition/"><u>Remediation of COMInterface Error, Windows Edition</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-vivo-x100-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>In 2024, How to Unlock Vivo X100 Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/released-camera-error-43-resolution/"><u>Released: Camera Error 43 Resolution</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixing-flash-freezing-onescreen-problems/"><u>Fixing Flash-Freezing Onescreen Problems</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/winos-stability-fixed-end-bluescreen-via-wdf-compliance/"><u>WinOS Stability Fixed: End BlueScreen via WDF Compliance</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-from-standard-to-spectacular-your-guide-to-selecting-a-stellar-4k-display/"><u>2024 Approved  From Standard to Spectacular  Your Guide to Selecting a Stellar 4K Display</u></a></li>
</ul></div>
