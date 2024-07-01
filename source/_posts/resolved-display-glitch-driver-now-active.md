---
title: "Resolved Display Glitch: Driver Now Active"
date: 2024-06-30T11:23:38.613Z
updated: 2024-07-01T11:23:38.613Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: "This Article Describes Resolved Display Glitch: Driver Now Active"
excerpt: "This Article Describes Resolved Display Glitch: Driver Now Active"
keywords: Display Glitch Resolution,Active Driver Software Update,Display Issue Fix,Software Bug Remediation,Driver Status Update,Software Glitch Resolution Tips,resolved display glitch driver now active
thumbnail: https://thmb.techidaily.com/db6e8bb5b9330de241494205e28fd162607bcee64226c4e5f87f88fc35435d44.jpg
---

## Resolved Display Glitch: Driver Now Active

![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58fd77e68afed.jpg)
 _Display driver nvlddmkm stopped responding and has successfully recovered_
  
 Error “Display driver stopped responding and has successfully recovered” usually occurs when playing games. If you have this problem, you should see the black screen appear randomly. This is very frustrating. But don’t worry. You can use solutions below to fix the problem .  
  
**Solution 1: Change Power Supply**
  
 The problem can be caused by lower power to the video card. So make sure the power supply are on high performance. Follow steps below to check and change the settings if necessary.  
  
 1\. Open [Control Panel](https://tools.techidaily.com/drivereasy/download/) .  
  
 2\. View by Large icons and select**Power Options** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58fdc56193bee.jpg)
  
 3\. Click**Change plan settings** in the “High performance plan” **.**
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58fdc6095a244.jpg)
  
 4\. Click**Change advanced power settings** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58fdc662f10a7.png)
  
 5\. Expand**PCI Express** then**Link State Power Management** . Ensure the Setting is turned **Off** . If not, set it to Off.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58fdc6a8bb61b.png)
  
 **Solution 2: Fix Faulty Graphics Card Driver**
  
 The error may be caused by faulty Nvidia graphics driver. So the first thing you can do is uninstall the graphics driver then update the driver to the latest version.  
  
 **Uninstall the Nvidia Driver**
  
 Follow steps below to uninstall the driver.  
 1\. Open [Device Manager](https://tools.techidaily.com/drivereasy/download/) .  
  
 2\. Expand category “Display adapters”. Right-click on the Nvidia graphics card device name and select**Uninstall** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58fd7f5175ab6.jpg)

 3\. When prompted for continue, click the box next to “Delete the driver software for this device” (if you see this), then click**OK**  button.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58fd7f69c729a.png)
  
 4\. Restart your PC for the change to take effect.  
  
 After computer restarts, Windows will install the graphics card driver automatically. Then the problem may resolve. If not, try updating the driver.  
  
**Update the Nvidia Graphics Card Driver**
  
 You can go to the PC manufacturer’s website to check for and download the latest graphics card driver. Alternatively, you can go to Nvidia’s website to download the driver according to the graphics card model. Before you get started, ensure that you know the PC model or the graphics card model and the operating system that you are using (See [How to Get Operating System Version](https://tools.techidaily.com/drivereasy/download/) ).  
  
 Alternatively, download [Driver Easy](https://tools.techidaily.com/drivereasy/download/) and use it to update the driver automatically. Driver Easy will scan your computer in a few seconds and detect all problem drivers. After that, you will get a list of new drivers. Driver Easy has Free version and Pro version. With [Driver Easy PRO version](https://tools.techidaily.com/drivereasy/download/) , you can even update all drivers including the Nvidia graphics card driver with just one-click. What’s more, you will enjoy free tech support guarantee and 30-day money back guarantee. Just contact us for further assistance regarding the graphics card crashing issue.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58fda0c612fb9.png)

**Solution 3: Add Two Related Registry Keys**
  
 If neither of Solution 1 and Solution 2 doesn’t work for you, try adding two related registry keys to the this location:  HKEY\_LOCAL\_MACHINE/SYSTEM/CurrentControlSet/Control/GraphicsDrivers.
  
 Before you get started, it is recommended that you back up the registry, so you can restore it if any problem occurs. See [How to Back Up and Restore Registry](https://tools.techidaily.com/drivereasy/download/)
  
 Follow these steps to add the registry keys:  
  
 1\. Press**Win+R** (Windows key and R key) at the same time. A Run dialog box will appear.  
  
 2\. Type**regedit** in the run box then click**OK** button. Then the “Registry” Editor will open.  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/02/img_56d1514256cf9.png)

 3\. Browse to and then click the following registry subkey:

 **HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\GraphicsDrivers**
  
![](https://images.drivereasy.com/wp-content/uploads/2016/02/img_56d15158994b0.png)

  4\. On the**Edit** menu in the right pane, right-click on the blank place. Click**New** , and then select the following registry value from the drop-down menu specific to your version of Windows.

 If your PC is running**32-bit** operating system, follow these steps:  
  
 a. Select**DWORD (32-bit) Value** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/02/img_56d151767ad5b.png)

  b. Type**TdrDelay** as the**Name** and click**Enter** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/02/img_56d15185e69a6.png)

 c. Double-click TdrDelay and add “20” for the Value data and click**OK** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58fdcefb5f556.png)

 Repeat steps above to add a new DWORD named “**TdrDdiDelay** ” and also add “20” for the Value data.  
  
 If your PC is running**64-bit** operating system, follow steps below:

 a. Select**QWORD (64-bit) Value** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/02/img_56d151bc4d971.png)

  b. Type**TdrDelay** as the**Name** and click**Enter** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/02/img_56d151caa9437.png)

  c. Double-click TdrDelay and add “20” for the Value data and click**OK** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58fdd06cb443f.png)

 Repeat steps above to add a new DWORD named “ **TdrDdiDelay** ” and also add  “20” for the Value data.  
  
4\. Restart your PC for the changes to take effect.

**Solution 4 : Take out the Graphics Card and Put it back in**
  
 If the graphics card is not seated well in the PCI-E slot, the problem may occur. So take out the graphics card and put it back in the slot. It is recommended that you use a soft cloth to clean the slot before you put it back in.  
  
 Hope you can solve the problem with all solutions here.  
  
 If you are not comfortable with some of these solutions, you can take your computer to the repair store to have it checked.

* [Windows](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://graphic-issues.techidaily.com/fixed-resolving-installer-snags-for-nvidia/"><u>Fixed: Resolving Installer Snags for Nvidia</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/1719818160725-opengl-glitch-spotted-nvidia-gpu-fixed-up/"><u>OpenGL Glitch Spotted - Nvidia GPU Fixed Up</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/harmonizing-frame-rates-fixes-for-flaky-amd-freesync/"><u>Harmonizing Frame Rates: Fixes for Flaky AMD FreeSync</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/enhancing-lenovo-laptop-vision-clarity/"><u>Enhancing Lenovo Laptop Vision Clarity</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/upend-pc-monitor-for-win7/"><u>Upend PC Monitor for Win7</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/how-to-fix-gpu-crashes-but-pc-stays-on/"><u>How to Fix GPU Crashes But PC Stays On</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/enhanced-screen-resolution-controls-in-win11/"><u>Enhanced Screen Resolution Controls in Win11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/system-affected-by-graphics-driver-crash-repaired/"><u>System Affected by Graphics Driver Crash Repaired</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-rev-up-with-these-top-10-srt-power-up-tools-for-pc-and-mac/"><u>[Updated] Rev Up with These Top 10 SRT Power-Up Tools for PC and Mac</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlocking-made-easy-the-best-10-apps-for-unlocking-your-samsung-galaxy-s24plus-device-by-drfone-android/"><u>In 2024, Unlocking Made Easy The Best 10 Apps for Unlocking Your Samsung Galaxy S24+ Device</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-unlocking-facebook-freedom-the-ultimate-avoidance-blueprint-for-2024/"><u>[Updated] Unlocking Facebook Freedom  The Ultimate Avoidance Blueprint for 2024</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/best-action-hunting-cameras-of-2023-for-2024/"><u>Best Action Hunting Cameras of 2023 for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-techniques-for-reducing-digital-audio-file-sizes/"><u>Updated Techniques for Reducing Digital Audio File Sizes</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-mastering-spotify-promos-your-comprehensive-guide/"><u>[New] Mastering Spotify Promos  Your Comprehensive Guide</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-2024-approved-becoming-a-viral-star-on-tiktok-steps-to-increase-views-and-likes/"><u>[Updated] 2024 Approved  Becoming a Viral Star on TikTok  Steps to Increase Views and Likes</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-from-good-to-great-videos-the-20-essential-shortcuts-for-success/"><u>2024 Approved  From Good to Great Videos  The 20 Essential Shortcuts for Success</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/culinary-crossroads-popular-food-recipes-intersected/"><u>Culinary Crossroads  Popular Food Recipes Intersected</u></a></li>
</ul></div>
