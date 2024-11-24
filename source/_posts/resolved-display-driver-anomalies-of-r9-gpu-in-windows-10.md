---
title: Resolved Display Driver Anomalies of R9 GPU in Windows 10
date: 2024-11-21T20:21:22.015Z
updated: 2024-11-24T06:25:53.812Z
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
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-hitch-free-methods-igtv-and-story-sharing/"><u>[Updated] 2024 Approved Hitch-Free Methods IGTV and Story Sharing</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-cutting-edge-tips-for-live-rl-broadcasting-for-2024/"><u>[Updated] Cutting-Edge Tips for Live RL Broadcasting for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-from-capture-to-creation-discover-the-best-montage-apps-for-smartphones/"><u>[Updated] From Capture to Creation Discover the Best Montage Apps for Smartphones</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-photoshop-wizardry-for-bending-photos-for-2024/"><u>[Updated] Photoshop Wizardry for Bending Photos for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/clear-white-screen-in-create-a-family/"><u>Clear White Screen in Create-A-Family</u></a></li>
<li><a href="https://article-helps.techidaily.com/creative-text-amplification-tips-for-2024/"><u>Creative Text Amplification Tips for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/develop-your-bespoke-version-of-chatgpt-strategies-and-tips/"><u>Develop Your Bespoke Version of ChatGPT: Strategies and Tips</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/effortlessly-enjoy-dual-gpu-performance-in-win10-via-nvidia-and-intel/"><u>Effortlessly Enjoy Dual-GPU Performance in Win10 via Nvidia & Intel</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/guide-to-resolve-critical-error-code-c1900101-on-pc/"><u>Guide to Resolve Critical Error Code C1900101 on PC</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-phone-number-from-your-apple-id-from-your-iphone-15-pro-max-by-drfone-ios/"><u>How To Remove Phone Number From Your Apple ID from Your iPhone 15 Pro Max?</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/invisible-display-driver-released/"><u>Invisible Display: Driver Released</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/revitalize-computing-power-refreshing-intels-graphics-drivers/"><u>Revitalize Computing Power: Refreshing Intel's Graphics Drivers</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/securing-stability-addressing-lenovo-screenshake/"><u>Securing Stability: Addressing Lenovo Screenshake</u></a></li>
<li><a href="https://some-guidance.techidaily.com/streamlining-media-playback-with-vlc-mac-for-2024/"><u>Streamlining Media Playback with VLC (Mac) for 2024</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshoot-apple-idevice-wi-fi-woes-with-these-8-effective-tips/"><u>Troubleshoot Apple iDevice Wi-Fi Woes with These 8 Effective Tips</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/troubleshooting-intells-driver-under-strict-specs/"><u>Troubleshooting Intell's Driver Under Strict Specs</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/win10-update-no-more-video-troubles/"><u>Win10 Update - No More Video Troubles</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15TKQ-BOENI?si=Ri4B2AuxAdi0Bglz&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

