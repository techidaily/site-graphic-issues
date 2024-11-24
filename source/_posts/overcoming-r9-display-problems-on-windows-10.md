---
title: Overcoming R9 Display Problems on Windows 10
date: 2024-11-18T09:00:34.622Z
updated: 2024-11-24T12:21:14.208Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: This Article Describes Overcoming R9 Display Problems on Windows 10
excerpt: This Article Describes Overcoming R9 Display Problems on Windows 10
keywords: Overcoming R9 Display Problems,Windows 10 Display Issues Fix,Solutions for R9 Screen Errors,Troubleshooting Windows 10 Graphics,Resolving R9 Display Glitches on PC,Fixing Windows 10 LCD Display Problems,Addressing R9 Screen Flickering Issue
thumbnail: https://thmb.techidaily.com/7c8eb4a6751ebbb720d8baa15eb6264cc6e760acb0b1ed4fef37387dcca189b5.jpg
---

## Overcoming R9 Display Problems on Windows 10

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
<li><a href="https://youtube-webster.techidaily.com/n-2024-elevating-your-channel-youtube-backlink-basics/"><u>[New] In 2024, Elevating Your Channel YouTube Backlink Basics</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-the-art-of-crafting-successful-instagram-posts/"><u>[New] In 2024, The Art of Crafting Successful Instagram Posts</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-the-strategists-handbook-for-youtube-ad-profitability/"><u>[New] The Strategist's Handbook for YouTube Ad Profitability</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-top-practices-in-producing-trustworthy-video-product-reviews-for-2024/"><u>[Updated] Top Practices in Producing Trustworthy Video Product Reviews for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-tips-for-creating-a-viral-buzz-on-facebook-that-you-should-know/"><u>2024 Approved Tips for Creating a Viral Buzz on Facebook that You Should Know</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/addressing-windows-10-flash-dilemma/"><u>Addressing Windows 10 Flash Dilemma</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/eliminate-screen-hiccup-in-win11/"><u>Eliminate Screen Hiccup in Win11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixing-hidden-advanced-options-in-win10-display/"><u>Fixing Hidden Advanced Options in Win10 Display</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/gpu-activation-win11-laptop-operational/"><u>GPU Activation: Win11 Laptop Operational</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-the-essential-guide-to-early-success-on-youtube-steer-clear-of-these-top-8-pitfalls/"><u>In 2024, The Essential Guide to Early Success on YouTube Steer Clear of These Top 8 Pitfalls</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/optimal-play-with-less-lag/"><u>Optimal Play with Less Lag</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/radeon-hd-6950-optimized-windows-10-driver-update/"><u>Radeon HD 6950: Optimized Windows 10 Driver Update</u></a></li>
<li><a href="https://tech-revival.techidaily.com/step-by-step-crafting-cover-letters-with-ai-assistance/"><u>Step-by-Step: Crafting Cover Letters with AI Assistance</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/swift-solutions-to-asus-display-dilemmas/"><u>Swift Solutions to Asus Display Dilemmas</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-error-1053-how-to-ensure-services-start-promptly/"><u>Troubleshooting Steps for Error 1053: How to Ensure Services Start Promptly</u></a></li>
<li><a href="https://techtrends.techidaily.com/user-friendly-techniques-for-screen-capture-on-asus-devices/"><u>User-Friendly Techniques for Screen Capture on Asus Devices</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/visual-victory-quick-fix-for-blank-monitors/"><u>Visual Victory: Quick FIX for Blank Monitors</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

