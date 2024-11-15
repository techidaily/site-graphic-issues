---
title: Overcome Installation Obstacle for Nvidia Driver
date: 2024-11-10T21:59:44.359Z
updated: 2024-11-14T16:40:13.279Z
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

<!-- affiliate ads begin -->
<span id="1498635">
					<video width="320" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1498635.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/17326-1498635">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1498635.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:200px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fancheer.sjv.io%2Fc%2F5597632%2F1498635%2F17326'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1498635/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## **Check if the Graphics Card is Disabled**

 If your graphics card is disabled, you won’t be able to install the driver, which is likely to be what’s causing the error. You can check this setting in Device Manager:

 1) Go to [Device Manager,](https://tools.techidaily.com/drivereasy/download/)  if you see a small down arrow next to the device, as shown in the picture below, it’s been disabled. All you need to do is right-click the device and click **Enable** .

![](https://images.drivereasy.com/wp-content/uploads/2016/11/img_581c50591ccf5.png)

2) Restart your PC if it asks you to. Then reinstall the driver.

## **Check if the Graphics Card is Detected Incorrectly**

 Under category the “ **Display adapters**  “, if you can’t see your graphics card listed, it’s probably not being detected properly. It could be listed under “Other devices” or somewhere else, or coming up as another device name.

 To check if this is happening, locate the devices with yellow marks on them. One of these devices may be your NVIDIA graphics card. If you’re not sure how to figure out which one is your graphics card, you can follow the steps below:

 1) Right-click on a device with a yellow mark on it and click **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2016/11/img_581c568d597b7.png)

 2) Go to the **Details** tab, select**Hardware Ids** from the drop-down menu under **Property** .

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_5785de836c928.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885947/19272" target="_top" id="1885947">
  <img src="//a.impactradius-go.com/display-ad/19272-1885947" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885947/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) The Hardware Id Value should be similar to the below screenshot. The VEN code means vendor and the DEV code means device. In the example below, the VEN code is 15AD and the device is 0740.

![](https://images.drivereasy.com/wp-content/uploads/2016/07/img_5785df1376590.png)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139122/17108" target="_top" id="2139122">
  <img src="//a.impactradius-go.com/display-ad/17108-2139122" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139122/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) Go to [https://pci-ids.ucw.cz/](https://pci-ids.ucw.cz/) . You use the VEN code and the DEV code you got from Step 3) to find the device.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b56e6603c4e9.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136614/26400" target="_top" id="2136614">
  <img src="//a.impactradius-go.com/display-ad/26400-2136614" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136614/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://instagram-video-files.techidaily.com/new-cutting-edge-tactics-for-polishing-your-social-media-vids-on-instagram-for-2024/"><u>[New] Cutting-Edge Tactics for Polishing Your Social Media Vids on Instagram for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-how-to-clear-your-default-podcast-listings-on-spotify/"><u>[New] How to Clear Your Default Podcast Listings on Spotify</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/tep-by-step-guide-to-analyzing-youtube-engagement-for-2024/"><u>[New] Step-by-Step Guide to Analyzing YouTube Engagement for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-share-your-latest-audio-exploration/"><u>2024 Approved Share Your Latest Audio Exploration</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/cured-directx-12-frame-timing-error/"><u>Cured DirectX 12 Frame Timing Error</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-and-install-the-latest-synaptics-driver-for-your-windows-tabletlaptop/"><u>Download & Install the Latest Synaptics Driver for Your Windows Tablet/Laptop</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/tial-guide-the-top-10-inexpensive-youtube-channels-for-visual-creators-for-2024/"><u>Essential Guide The Top 10 Inexpensive YouTube Channels for Visual Creators for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/how-to-get-asus-camera-operating-again/"><u>How to Get Asus Camera Operating Again</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-track-imei-number-of-honor-100-through-google-earth-by-drfone-android/"><u>How To Track IMEI Number Of Honor 100 Through Google Earth?</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolved-amd-radeon-r9-display-problems-on-win10/"><u>Resolved AMD Radeon R9 Display Problems on Win10</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-6-best-sim-unlock-services-that-actually-work-on-your-asus-device-by-drfone-android/"><u>The 6 Best SIM Unlock Services That Actually Work On Your Asus Device</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-10-black-screen-after-fall-creators-update-solved/"><u>Windows 10 Black Screen After Fall Creators Update [Solved]</u></a></li>
</ul></div>

