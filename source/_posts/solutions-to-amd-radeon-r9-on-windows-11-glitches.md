---
title: Solutions to AMD Radeon R9 on Windows 11 Glitches
date: 2024-06-30T11:17:29.019Z
updated: 2024-07-01T11:17:29.019Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: This Article Describes Solutions to AMD Radeon R9 on Windows 11 Glitches
excerpt: This Article Describes Solutions to AMD Radeon R9 on Windows 11 Glitches
keywords: AMD Radeon,R9 Series Fixes,Windows 11 Radeon Glitches,GPU Troubleshooting Windows 11,Radeon R9 Performance Tips,AMD Graphics Windows Solutions,Glitch Resolution for Radeon Users
thumbnail: https://thmb.techidaily.com/4cde13e35fb005f35b03fe575a760700ef2f31716bcebcb3bdb2d428b2778fad.jpg
---

## Solutions to AMD Radeon R9 on Windows 11 Glitches

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
<li><a href="https://graphic-issues.techidaily.com/nvidia-driver-back-online-after-hiccup/"><u>Nvidia Driver: Back Online After Hiccup</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/aligning-screen-borders-uniformly/"><u>Aligning Screen Borders Uniformly</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/revitalizing-your-pcs-intel-video-with-win7/"><u>Revitalizing Your PC’s Intel Video with Win7</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/addressed-overwatchs-graphics-error/"><u>Addressed Overwatch's Graphics Error</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixed-the-flashing-problems-for-good/"><u>Fixed the Flashing Problems for Good</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/screen-inactive-graphics-card-not-found/"><u>Screen Inactive: Graphics Card Not Found</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/power-up-displayport-with-a-click/"><u>Power Up DisplayPort with a Click</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/display-chip-functionality-restored-after-interruption/"><u>Display Chip Functionality Restored After Interruption</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-amplify-your-content-reach-with-twitters-visual-stories-to-insta/"><u>[Updated] In 2024, Amplify Your Content Reach with Twitter's Visual Stories to Insta</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-oneplus-11-5g-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on OnePlus 11 5G Phones with/without a PC</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/quick-and-convenient-video-edits-in-windows-11-photos-for-2024/"><u>Quick & Convenient Video Edits in Windows 11 Photos for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-preparation-to-beat-giovani-in-pokemon-go-for-poco-c51-drfone-by-drfone-virtual-android/"><u>In 2024, Preparation to Beat Giovani in Pokemon Go For Poco C51 | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-motorola-moto-g84-5g-to-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Motorola Moto G84 5G To Phone | Dr.fone</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-in-2024-framed-in-perfection-the-1-10-camera-lens-list-for-stunning-photography/"><u>[Updated] In 2024, Framed in Perfection  The #1-10 Camera Lens List for Stunning Photography</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-perfect-pairing-sound-and-imagery-in-media-production/"><u>In 2024, Perfect Pairing  Sound & Imagery in Media Production</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-experts-blueprint-revolutionizing-your-screencasting-experience-with-mobizen/"><u>[Updated] In 2024, Expert's Blueprint  Revolutionizing Your Screencasting Experience with Mobizen</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-blending-apple-music-with-cinematic-content/"><u>[New] Blending Apple Music with Cinematic Content</u></a></li>
</ul></div>
