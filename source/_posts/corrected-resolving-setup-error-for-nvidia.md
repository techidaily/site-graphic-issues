---
title: "Corrected: Resolving Setup Error for NVIDIA"
date: 2024-11-06T22:59:40.482Z
updated: 2024-11-13T20:47:37.352Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: "This Article Describes Corrected: Resolving Setup Error for NVIDIA"
excerpt: "This Article Describes Corrected: Resolving Setup Error for NVIDIA"
keywords: NVIDIA Setup Troubleshooting,Fix NVIDIA Configuration Errors,NVIDIA Installation Tips,Resolve NVIDIA Errors During Setup,NVIDIA Hardware Compatibility Issues,Error Fixing NVIDIA Software,NVIDIA Driver Update Guide
thumbnail: https://thmb.techidaily.com/4be59755ae7994bb626513b3614a3ec947be3b56430323187fb64d462d24a601.jpg
---

## Corrected: Resolving Setup Error for NVIDIA

 Do you get this error message when installing your NVIDIA Graphics driver?:

“   **NVIDIA Installer cannot continue. This graphics driver could not find compatible graphics hardware.”**

![](https://images.drivereasy.com/wp-content/uploads/2019/08/image-608.png)

 If so, don’t worry. It’s a really common issue and one you can usually fix yourself. You can install the driver successfully by following the instructions we’ve put together in this article.

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136625/26400" target="_top" id="2136625">
  <img src="//a.impactradius-go.com/display-ad/26400-2136625" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136625/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

2) Restart your PC if it asks you to. Then reinstall the driver.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151865/7443" target="_top" id="2151865">
  <img src="//a.impactradius-go.com/display-ad/7443-2151865" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151865/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## **Check if the Graphics Card is Detected Incorrectly**

 Under category the “ **Display adapters**  “, if you can’t see your graphics card listed, it’s probably not being detected properly. It could be listed under “Other devices” or somewhere else, or coming up as another device name.

 To check if this is happening, locate the devices with yellow marks on them. One of these devices may be your NVIDIA graphics card. If you’re not sure how to figure out which one is your graphics card, you can follow the steps below:

 1) Right-click on a device with a yellow mark on it and click **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2016/11/img_581c568d597b7.png)

 2) Go to the **Details** tab, select**Hardware Ids** from the drop-down menu under **Property** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_5785de836c928.png)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2145009/26400" target="_top" id="2145009">
  <img src="//a.impactradius-go.com/display-ad/26400-2145009" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2145009/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) The Hardware Id Value should be similar to the below screenshot. The VEN code means vendor and the DEV code means device. In the example below, the VEN code is 15AD and the device is 0740.

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_5785df1376590.png)

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/1943750/22993" target="_top" id="1943750">
  <img src="//a.impactradius-go.com/display-ad/22993-1943750" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://homestyler.sjv.io/i/5597632/1943750/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://youtube-tips.techidaily.com/024-approved-getting-the-most-out-of-your-youtube-videos-thumbnails-extraction/"><u>[New] 2024 Approved Getting the Most Out of Your Youtube Videos Thumbnails Extraction</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-innovations-in-mobile-photography-a-look-at-iphone-x/"><u>[New] Innovations in Mobile Photography A Look at iPhone X</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-4-top-choices-for-seamless-pcmac-video-capture/"><u>[Updated] 4 Top Choices for Seamless PC/Mac Video Capture</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/a-step-by-step-guide-to-amplify-your-content-through-spotlighting-for-2024/"><u>A Step-by-Step Guide to Amplify Your Content Through Spotlighting for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/banish-screen-flicker-in-workstations/"><u>Banish Screen Flicker in Workstations</u></a></li>
<li><a href="https://solve-helper.techidaily.com/cookiebot-enabled-enhancing-your-websites-user-experience-and-tracking/"><u>Cookiebot-Enabled: Enhancing Your Website's User Experience and Tracking</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-pause-life360-location-sharing-for-motorola-edge-40-neo-drfone-by-drfone-virtual-android/"><u>In 2024, How To Pause Life360 Location Sharing For Motorola Edge 40 Neo | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/is-your-nubia-red-magic-9-proplus-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Nubia Red Magic 9 Pro+ working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/1719817695526-opengl-and-gpu-hiccup-no-more-thanks-to-nvidia-fixes/"><u>OpenGL & GPU Hiccup - No More Thanks to Nvidia Fixes</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolved-unsupported-graphics-in-overwatch-patch/"><u>Resolved Unsupported Graphics in Overwatch Patch</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/restoring-unlocked-graphics-preferences-for-nvidia/"><u>Restoring Unlocked Graphics Preferences for Nvidia</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/safe-mode-savior-efficiently-uninstalling-graphics-drivers-on-win8/"><u>Safe Mode Savior: Efficiently Uninstalling Graphics Drivers on WIN8</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/solve-white-screen-in-sims-life-events/"><u>Solve White Screen in Sims Life Events</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/streaming-on-windows-10-after-upgrade-secured/"><u>Streaming on Windows 10 After Upgrade Secured</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/unveiling-the-latest-in-technology-with-toms-equipment-analysis/"><u>Unveiling the Latest in Technology with Tom’s Equipment Analysis</u></a></li>
</ul></div>

