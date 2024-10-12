---
title: "Navigated: Resolving NVIDIA Installation Failure"
date: 2024-10-07T22:07:34.060Z
updated: 2024-10-11T16:23:34.148Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: "This Article Describes Navigated: Resolving NVIDIA Installation Failure"
excerpt: "This Article Describes Navigated: Resolving NVIDIA Installation Failure"
keywords: Nvidia Driver Troubleshooting,Installing NVIDIA Graphics Cards,Fix Nvidia Install Failure,Resolving Graphics Driver Errors,Nvidia Installation Guide,Tips for Successful NVIDIA Setup,Troubleshooting NVIDIA Installation
thumbnail: https://thmb.techidaily.com/5c9cbb5d30907fc5a8d3f1782668978fcf6f103cacbe9ad11043aa91ad5ce8d7.jpg
---

## Navigated: Resolving NVIDIA Installation Failure

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

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148633/16836" target="_top" id="2148633">
  <img src="//a.impactradius-go.com/display-ad/16836-2148633" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148633/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## **Check if the Graphics Card is Disabled**

 If your graphics card is disabled, you won’t be able to install the driver, which is likely to be what’s causing the error. You can check this setting in Device Manager:

 1) Go to [Device Manager,](https://tools.techidaily.com/drivereasy/download/)  if you see a small down arrow next to the device, as shown in the picture below, it’s been disabled. All you need to do is right-click the device and click **Enable** .

![](https://images.drivereasy.com/wp-content/uploads/2016/11/img_581c50591ccf5.png)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148774/18498" target="_top" id="2148774">
  <img src="//a.impactradius-go.com/display-ad/18498-2148774" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148774/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

2) Restart your PC if it asks you to. Then reinstall the driver.

## **Check if the Graphics Card is Detected Incorrectly**

 Under category the “ **Display adapters**  “, if you can’t see your graphics card listed, it’s probably not being detected properly. It could be listed under “Other devices” or somewhere else, or coming up as another device name.

 To check if this is happening, locate the devices with yellow marks on them. One of these devices may be your NVIDIA graphics card. If you’re not sure how to figure out which one is your graphics card, you can follow the steps below:

 1) Right-click on a device with a yellow mark on it and click **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2016/11/img_581c568d597b7.png)

 2) Go to the **Details** tab, select**Hardware Ids** from the drop-down menu under **Property** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_5785de836c928.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948949/19272" target="_top" id="1948949">
  <img src="//a.impactradius-go.com/display-ad/19272-1948949" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948949/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) The Hardware Id Value should be similar to the below screenshot. The VEN code means vendor and the DEV code means device. In the example below, the VEN code is 15AD and the device is 0740.

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_5785df1376590.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118312/7443" target="_top" id="2118312">
  <img src="//a.impactradius-go.com/display-ad/7443-2118312" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118312/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-navigating-illness-with-immersive-systems/"><u>[New] 2024 Approved Navigating Illness with Immersive Systems</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolved-advanced-graphics-tuning-for-windows-11/"><u>[Resolved] Advanced Graphics Tuning for Windows 11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-leading-hd-video-capture-technology/"><u>[Updated] Leading HD Video Capture Technology</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-professional-tricks-for-youtube-audio-amplification/"><u>[Updated] Professional Tricks for YouTube Audio Amplification</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-what-is-the-meaning-and-functionality-of-a-blue-emoji-in-messenger/"><u>[Updated] What Is the Meaning and Functionality of a Blue Emoji in Messenger?</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/boosting-screen-definition-and-precision/"><u>Boosting Screen Definition and Precision</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/capturing-counter-strike-global-offensive-play-seamlessly-for-2024/"><u>Capturing Counter-Strike Global Offensive Play Seamlessly for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/cured-hyperz-compatibility-fault/"><u>Cured HyperZ Compatibility Fault</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-guide-how-to-restore-connection-to-a-disconnected-external-hardware-on-windows/"><u>Expert Guide: How to Restore Connection to a Disconnected External Hardware on Windows</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-bridging-platforms-loop-ready-setups-for-youtube-and-tv/"><u>In 2024, Bridging Platforms Loop-Ready Setups for YouTube and TV</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-twitter-vids-to-mp3-easy-extraction-techniques/"><u>In 2024, Twitter Vids to MP3 Easy Extraction Techniques</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overhaul-black-screen-in-win11-after-update-fall/"><u>Overhaul Black Screen in Win11 After Update Fall</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolve-civ-5-pc-glitches/"><u>Resolve CIV 5 PC Glitches</u></a></li>
</ul></div>

