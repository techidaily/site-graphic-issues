---
title: Resolved Display Driver Anomalies of R9 GPU in Windows 10
date: 2024-07-11T16:56:52.416Z
updated: 2024-07-12T16:56:52.416Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: This Article Describes Resolved Display Driver Anomalies of R9 GPU in Windows 10
excerpt: This Article Describes Resolved Display Driver Anomalies of R9 GPU in Windows 10
keywords: R9 GPU Troubleshooting,Display Driver Anomalies Fix,R9 GPU Issues Windows 10,Windows 10 GPU Display Driver Fixes,R9 Graphics Resolution Problems,Windows Update Display Driver Anomalies,R9 GPU Firmware Updates
thumbnail: https://thmb.techidaily.com/c45afa71b37443a1f59fe90234d68b3b0e50e4c51b39e47e7a2ccf645d397043.PNG
---

## Resolved Display Driver Anomalies of R9 GPU in Windows 10

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
<li><a href="https://graphic-issues.techidaily.com/overhauled-graphics-card-error-43/"><u>Overhauled Graphics Card Error 43</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/banishing-screenscape-disturbances-in-pro-7/"><u>Banishing Screenscape Disturbances in Pro 7</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/troubleshooting-stop-asus-laptop-screen-flashes/"><u>Troubleshooting: Stop ASUS Laptop Screen Flashes</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/completed-navigating-through-installer-snags/"><u>Completed: Navigating Through Installer Snags</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-premier-video-editing-choices-for-online-sessions/"><u>[Updated] Premier Video Editing Choices for Online Sessions</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/unexplained-geforce-gtx-absence/"><u>Unexplained GeForce GTX Absence</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/nd-android-youtube-autoplay-tricks/"><u>IOS & Android  YouTube AutoPlay Tricks</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-10-screen-flashing-or-flickering-solved/"><u>Windows 10 Screen Flashing Or Flickering [SOLVED]</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-slowing-down-the-action-vlc-video-playback-tips/"><u>Updated 2024 Approved Slowing Down the Action VLC Video Playback Tips</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/anatomie-universelle-en-francais-partes-du-corps/"><u>Anatomie Universelle en Français (Partes Du Corps)</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcome-nvidiaintel-gpu-conflict-on-windows-11/"><u>Overcome NVIDIA/Intel GPU Conflict on Windows 11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/strategies-for-effective-video-markup-on-youtube-for-2024/"><u>Strategies for Effective Video Markup on YouTube for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/hasten-installing-intel-gfx-3000-on-windows-10/"><u>Hasten Installing Intel GFX 3000 on Windows 10</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-a-perfect-guide-to-remove-or-disable-google-smart-lock-on-poco-c65-by-drfone-android/"><u>In 2024, A Perfect Guide To Remove or Disable Google Smart Lock On Poco C65</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-simplify-your-workflow-top-video-editors-with-reframe/"><u>Updated Simplify Your Workflow Top Video Editors with Reframe</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/end-pc-freezes-enjoy-uninterrupted-fallout-4-play/"><u>End PC Freezes, Enjoy Uninterrupted Fallout 4 Play</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/hurdles-halved-display-settings-saved-successfully/"><u>Hurdles Halved: Display Settings Saved Successfully</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/visual-victory-displays-preserved-after-fix/"><u>Visual Victory: Displays Preserved After Fix</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fix-apcs-disregard-for-internal-video-cards/"><u>Fix: APC's Disregard for Internal Video Cards</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/1719817906327-solved-nvidia-code-43-windows-has-stopped-this-device-because-it-has-reported-problems/"><u>[Solved] NVIDIA Code 43: Windows Has Stopped This Device because It Has Reported Problems</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/how-to-address-gpu-anomalies-in-pcs/"><u>How to Address GPU Anomalies in PCs</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/error-rectified-in-monitor-driver/"><u>Error Rectified in Monitor Driver</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/solved-windows-10-display-too-big/"><u>[SOLVED] Windows 10 Display Too Big</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/lenovo-shadows-be-gone/"><u>Lenovo Shadows Be Gone!</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/invertingscreenview-solution/"><u>InvertingScreenView Solution</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-unlocking-potential-creating-your-youtube-identity/"><u>[Updated] In 2024, Unlocking Potential  Creating Your YouTube Identity</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/graphic-rendering-system-errored-on-start/"><u>Graphic Rendering System Errored On-Start</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/steps-to-improve-lenovo-monitor-luminosity/"><u>Steps to Improve Lenovo Monitor Luminosity</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-the-ultimate-voice-transformation-handbook-for-gamers/"><u>New In 2024, The Ultimate Voice Transformation Handbook for Gamers</u></a></li>
<li><a href="https://android-location.techidaily.com/easy-ways-to-manage-your-lava-storm-5g-location-settings-drfone-by-drfone-virtual/"><u>Easy Ways to Manage Your Lava Storm 5G Location Settings | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/new-update-all-graphics-hardware-compatible-with-overwatch/"><u>New Update: All Graphics Hardware Compatible with Overwatch</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-expert-tips-for-lut-integration-in-premiere-projects/"><u>[Updated] 2024 Approved  Expert Tips for LUT Integration in Premiere Projects</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/seamless-windows-10-experience-fix-for-intel-and-nvidia-switchable-graphics/"><u>Seamless Windows 10 Experience: Fix for Intel & NVIDIA Switchable Graphics</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/win10-update-no-more-video-glitches-or-buffering/"><u>Win10 Update: No More Video Glitches or Buffering</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixing-upside-down-screen-on-windows-11/"><u>Fixing Upside Down Screen on Windows 11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/how-to-increase-screen-brightness-on-lenovo-laptops/"><u>How to Increase Screen Brightness on Lenovo Laptops</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/quick-cure-for-lags-and-interruptions/"><u>Quick Cure for Lags & Interruptions</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/soundscape-synthesis-techniques-for-customizing-timestamps-and-soundscapes-in-final-cut-pro-x/"><u>Soundscape Synthesis Techniques for Customizing Timestamps and Soundscapes in Final Cut Pro X</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/halted-dx12-error-in-new-halo-infinites-release/"><u>Halted: DX12 Error in New Halo Infinite's Release</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-zte-blade-a73-5g-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset ZTE Blade A73 5G without Losing Data | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/techniques-for-clearing-smudge-filled-displays/"><u>Techniques for Clearing Smudge-Filled Displays</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/no-graphic-support-detected/"><u>No Graphic Support Detected</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-crossing-over-attending-tiktok-live-gigs-easily/"><u>[New] Crossing Over  Attending TikTok Live Gigs Easily</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/enhance-performance-install-new-gpu-drivers/"><u>Enhance Performance: Install New GPU Drivers</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/expert-video-edits-how-to-masterly-modify-and-shorten-videos-on-vimeo-online-for-2024/"><u>Expert Video Edits  How to Masterly Modify and Shorten Videos on Vimeo Online for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/how-i-reconnected-my-laptop-and-tv-with-hdmi/"><u>How I Reconnected My Laptop and TV with HDMI</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/detailed-guide-of-ispoofer-for-pogo-installation-on-apple-iphone-12-pro-max-drfone-by-drfone-virtual-ios/"><u>Detailed guide of ispoofer for pogo installation On Apple iPhone 12 Pro Max | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/keeping-intel-gpus-updated-on-windows-platform/"><u>Keeping Intel GPUs Updated on Windows Platform</u></a></li>
</ul></div>
