---
title: Overcome Installation Obstacle for Nvidia Driver
date: 2024-09-25T17:49:50.389Z
updated: 2024-10-01T02:39:25.855Z
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

2) Restart your PC if it asks you to. Then reinstall the driver.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148643/16836" target="_top" id="2148643">
  <img src="//a.impactradius-go.com/display-ad/16836-2148643" border="0" alt="https://techidaily.com" width="300" height="75"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148643/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## **Check if the Graphics Card is Detected Incorrectly**

 Under category the “ **Display adapters**  “, if you can’t see your graphics card listed, it’s probably not being detected properly. It could be listed under “Other devices” or somewhere else, or coming up as another device name.

 To check if this is happening, locate the devices with yellow marks on them. One of these devices may be your NVIDIA graphics card. If you’re not sure how to figure out which one is your graphics card, you can follow the steps below:

 1) Right-click on a device with a yellow mark on it and click **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2016/11/img_581c568d597b7.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137413/7443" target="_top" id="2137413">
  <img src="//a.impactradius-go.com/display-ad/7443-2137413" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137413/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) Go to the **Details** tab, select**Hardware Ids** from the drop-down menu under **Property** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_5785de836c928.png)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137203/26400" target="_top" id="2137203">
  <img src="//a.impactradius-go.com/display-ad/26400-2137203" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137203/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) The Hardware Id Value should be similar to the below screenshot. The VEN code means vendor and the DEV code means device. In the example below, the VEN code is 15AD and the device is 0740.

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_5785df1376590.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144298/7443" target="_top" id="2144298">
  <img src="//a.impactradius-go.com/display-ad/7443-2144298" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144298/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-unveiling-the-best-mp4-saving-software/"><u>[New] 2024 Approved Unveiling the Best MP4 Saving Software</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-best-7-multimedia-cameras-for-quality-live-streams-and-video-blogs/"><u>[New] In 2024, Best 7 Multimedia Cameras For Quality Live Streams & Video Blogs</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-rethinking-content-strategy-with-instagrams-new-order/"><u>[New] In 2024, Rethinking Content Strategy with Instagram's New Order</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-profit-from-reddit-easy-style-top-13-beginner-strategies/"><u>[New] Profit From Reddit Easy Style Top 13 Beginner Strategies</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-securely-transforming-youtube-videos-into-mp3-files-3-techniques/"><u>[New] Securely Transforming YouTube Videos Into MP3 Files - 3 Techniques</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/solution-needed-windows-without-amd-driver-available/"><u>[SOLUTION NEEDED]: Windows Without AMD Driver Available</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-fraps-as-a-video-recorder-what-you-need-to-know/"><u>[Updated] 2024 Approved Fraps as a Video Recorder What You Need To Know</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-boosting-your-gaming-footage-on-latest-windows-11/"><u>[Updated] Boosting Your Gaming Footage on Latest Windows 11</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-seamlessly-convert-youtube-videos-to-mp3-on-mac/"><u>2024 Approved Seamlessly Convert YouTube Videos to MP3 on Mac</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/addressing-overlapping-window-issues-in-windows-10/"><u>Addressing Overlapping Window Issues in Windows 10</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/diagonal-adjustment-success-portable-device/"><u>Diagonal Adjustment Success: Portable Device</u></a></li>
<li><a href="https://buynow-help.techidaily.com/elevate-your-digital-experience-insider-look-at-the-versatile-features-of-the-samsung-galaxy-tab-s4/"><u>Elevate Your Digital Experience: Insider Look at the Versatile Features of the Samsung Galaxy Tab S4</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/eliminate-visual-glitches-in-computers/"><u>Eliminate Visual Glitches in Computers</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/1719817910025-fix-vertical-lines-on-laptop-screen-easily/"><u>Fix Vertical Lines on Laptop Screen. Easily!</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-poco-x6-phone-without-google-account-by-drfone-android/"><u>In 2024, How to Unlock Poco X6 Phone without Google Account?</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/restore-brilliance-blackened-lenovo-fixed/"><u>Restore Brilliance - Blackened Lenovo Fixed</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/solving-windows-10-flickering-issue/"><u>Solving Windows 10 Flickering Issue</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/tips-for-correcting-c1900101-on-windows-11-installation/"><u>Tips for Correcting C1900101 on Windows 11 Installation</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/uncover-and-resolve-ignored-graphics-on-your-pc/"><u>Uncover and Resolve Ignored Graphics on Your PC</u></a></li>
</ul></div>

