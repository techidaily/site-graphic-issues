---
title: Overcome Installation Obstacle for Nvidia Driver
date: 2024-11-18T22:24:17.645Z
updated: 2024-11-24T06:48:05.026Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: This Article Describes Overcome Installation Obstacle for Nvidia Driver
excerpt: This Article Describes Overcome Installation Obstacle for Nvidia Driver
keywords: Nvidia Driver Setup Guide,Resolve Driver Installation Issues,Installing Nvidia Graphics Drivers Successfully,Nvidia Driver Compatibility Tips,Optimizing Nvidia Drivers Performance,Nvidia Driver Update Instructions,Troubleshooting Nvidia Drivers Installation
thumbnail: https://thmb.techidaily.com/347a25eb4f4bdd698c061d29a22709a4fba3cca9fc17f4dc1dd558be67ab5c6f.jpg
---

## Overcome Installation Obstacle for Nvidia Driver

 Do you get this error message when installing your NVIDIA Graphics driver?:

“   **NVIDIA Installer cannot continue. This graphics driver could not find compatible graphics hardware.”**

![](https://images.drivereasy.com/wp-content/uploads/2019/08/image-608.png)

 If so, don’t worry. It’s a really common issue and one you can usually fix yourself. You can install the driver successfully by following the instructions we’ve put together in this article.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AQn0MYjIfyI?si=rIdjT-qMRpjpJXXa&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Firstly, try to install the driver using Driver Easy

 Installing an incompatible driver can cause this error. Before you try anything else, you should use **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  to install the driver.  It’s as quick and simple as 2 mouse clicks.

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. **But with the Pro version it takes just 2 clicks (and you get full support and a 30-day money back guarantee)** . Here’s what you need to do:

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click **Scan Now** . Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2019/08/image-606.png)

 3) Click the **Update** button next to a flagged Nvidia driver to automatically download the correct version of this driver, then you can manually install it (you can do this with the FREE version).

 Or click **Update All**  to automatically download and install the correct version of _all_   the drivers that are missing or out of date on your system (this requires the Pro version – you’ll be prompted to upgrade when you click Update All).

 In the below example, you can see that NVIDIA GeForce GT 640 needs to be updated. Driver Easy will detect the Nvidia graphics card installed on your computer.

![](https://images.drivereasy.com/wp-content/uploads/2019/08/image-607.png)

 If you can’t install the driver with Driver Easy, the graphics card may be disabled or sending the wrong information.  If this happens to you, follow the instructions below to check.

## **Check if the Graphics Card is Disabled**

 If your graphics card is disabled, you won’t be able to install the driver, which is likely to be what’s causing the error. You can check this setting in Device Manager:

 1) Go to [Device Manager,](https://tools.techidaily.com/drivereasy/download/)  if you see a small down arrow next to the device, as shown in the picture below, it’s been disabled. All you need to do is right-click the device and click **Enable** .

![](https://images.drivereasy.com/wp-content/uploads/2016/11/img_581c50591ccf5.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BR4gsW-J7as?si=9a56UDKZKhREZnwz&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

2) Restart your PC if it asks you to. Then reinstall the driver.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U6lCtLUeROA?si=se6OFuis9JpcTGJf&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **Check if the Graphics Card is Detected Incorrectly**

 Under category the “ **Display adapters**  “, if you can’t see your graphics card listed, it’s probably not being detected properly. It could be listed under “Other devices” or somewhere else, or coming up as another device name.

 To check if this is happening, locate the devices with yellow marks on them. One of these devices may be your NVIDIA graphics card. If you’re not sure how to figure out which one is your graphics card, you can follow the steps below:

 1) Right-click on a device with a yellow mark on it and click **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2016/11/img_581c568d597b7.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gyGoQi7hsZk?si=8OcKcPUj2wSBmVZ1&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 2) Go to the **Details** tab, select**Hardware Ids** from the drop-down menu under **Property** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_5785de836c928.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) The Hardware Id Value should be similar to the below screenshot. The VEN code means vendor and the DEV code means device. In the example below, the VEN code is 15AD and the device is 0740.

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_5785df1376590.png)

 4) Go to [https://pci-ids.ucw.cz/](https://pci-ids.ucw.cz/) . You use the VEN code and the DEV code you got from Step 3) to find the device.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b56e6603c4e9.jpg)

 This will give you the device name and the vendor name (NVIDIA).

 Once you figure out the specific NVIDIA graphics card you have, you should update your driver to the latest version.

 If you’ve tried these solutions and continue to get an error, let us know! Leave a comment below and we’ll do our best to help.

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
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-essential-scripting-instant-stopwatch-integration-in-obs/"><u>[Updated] In 2024, Essential Scripting Instant Stopwatch Integration in OBS</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-multi-user-android-calls-the-top-8-tools-for-2024/"><u>[Updated] Multi-User Android Calls The Top 8 Tools for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unlocking-youtubes-srt-a-three-step-process/"><u>2024 Approved Unlocking YouTube’s SRT A Three-Step Process</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/direct3d-glitch-cleared-giving-you-smooth-performance-boost/"><u>Direct3D Glitch Cleared, Giving You Smooth Performance Boost</u></a></li>
<li><a href="https://extra-tips.techidaily.com/dissecting-haptic-feedback-in-digital-environments/"><u>Dissecting Haptic Feedback in Digital Environments</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/elevate-your-graphics-with-new-nvidia-win11-drivers/"><u>Elevate Your Graphics with New NVIDIA Win11 Drivers</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/elevating-the-television-experience-with-4k-pixels/"><u>Elevating the Television Experience with 4K Pixels</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-3-ways-to-fake-gps-without-root-on-samsung-galaxy-m54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Fake GPS Without Root On Samsung Galaxy M54 5G | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-everything-you-need-to-know-about-unlocked-apple-iphone-se-2020-by-drfone-ios/"><u>In 2024, Everything You Need To Know About Unlocked Apple iPhone SE (2020)</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/revive-and-enhance-zoom-calls-with-this-camera-repair-guide/"><u>Revive and Enhance Zoom Calls with This Camera Repair Guide</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/screeninversionproblem-fixes/"><u>ScreenInversionProblem Fixes</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/system-alert-dealt-with-nvidia-screen-functional/"><u>System Alert Dealt With: Nvidia Screen Functional</u></a></li>
<li><a href="https://ai-topics.techidaily.com/top-10-ai-talking-avatars-revolutionizing-communication-for-2024/"><u>Top 10 AI-Talking Avatars Revolutionizing Communication for 2024</u></a></li>
</ul></div>

