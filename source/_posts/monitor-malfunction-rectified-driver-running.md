---
title: "Monitor Malfunction Rectified: Driver Running"
date: 2024-07-11T17:28:45.034Z
updated: 2024-07-12T17:28:45.034Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: "This Article Describes Monitor Malfunction Rectified: Driver Running"
excerpt: "This Article Describes Monitor Malfunction Rectified: Driver Running"
keywords: Malfunctioning Device Repair,Computer System Diagnostics,Automotive Computer Repair Services,Faulty Hardware Troubleshooting,Software Glitch Resolution,Computer Boot Problems,Driver Error Fixes
thumbnail: https://thmb.techidaily.com/b458df85a4bb141857a3c4d2de6e35b07f50e405e5e03af8173f938324bb194b.png
---

## Monitor Malfunction Rectified: Driver Running

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
<li><a href="https://screen-sharing-recording.techidaily.com/exclusive-choice-of-cost-free-chat-apps-plus-desktop-viewing-for-2024/"><u>Exclusive Choice of Cost-Free Chat Apps + Desktop Viewing for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-gaming-gains-total-earnings-for-pewdiepie/"><u>[Updated] Gaming Gains  Total Earnings for PewDiePie</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-enhance-visuals-with-better-obs-settings-for-2024/"><u>[New] Enhance Visuals with Better OBS Settings for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-xiaomi-redmi-k70-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Xiaomi Redmi K70 Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/dismantle-the-flashy-monitor-myth/"><u>Dismantle the Flashy Monitor Myth</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/solved-rejuvenate-fallout-4-on-windows/"><u>Solved: Rejuvenate Fallout 4 on Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/enabling-duplex-print-for-office-hp-devices/"><u>Enabling Duplex Print for Office HP Devices</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolving-smudgy-graphics-in-fc6/"><u>Resolving Smudgy Graphics in FC6</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-efficient-audio-extraction-from-youtube-top-picks-for-your-favorite-free-crackers-for-2024/"><u>[New] Efficient Audio Extraction From YouTube  Top Picks for Your Favorite Free Crackers for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/expert-tips-for-stopping-squirm-in-asus-lcds/"><u>Expert Tips for Stopping Squirm in ASUS LCDs</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-oneplus-nord-3-5g-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your OnePlus Nord 3 5G? | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/ghostly-quadro-displayed-now-listed/"><u>Ghostly Quadro Displayed, Now Listed</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-unlocking-visual-clarity-bypassing-background-in-photopea/"><u>[Updated] Unlocking Visual Clarity  Bypassing Background in Photopea</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/effortless-troubleshooting-for-graphics-cards/"><u>Effortless Troubleshooting for Graphics Cards</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcome-latency-for-uninterrupted-videos/"><u>Overcome Latency for Uninterrupted Videos</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/maximizing-impact-with-googles-podcast-platform/"><u>Maximizing Impact with Google’s Podcast Platform</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/how-to-enable-laptop-graphics-on-windows-1011/"><u>How To Enable Laptop Graphics On Windows 10/11?</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/optimizing-god-of-war-difficulty-levels/"><u>Optimizing 'God of War' Difficulty Levels</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/no-amd-video-driver-found-in-windows-systems/"><u>No AMD Video Driver Found in Windows Systems</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-enhancing-lighting-and-shadows-in-obs-video/"><u>[New] 2024 Approved  Enhancing Lighting and Shadows in OBS Video</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-mastering-tiktok-aspect-ratios-a-step-by-step-guide-for-2024/"><u>Updated Mastering TikTok Aspect Ratios A Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-discover-the-best-6-apps-to-supercharge-your-instagram-reels-for-2024/"><u>[Updated] Discover the Best 6 Apps to Supercharge Your Instagram Reels for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/laptop-to-tv-connection-repair-via-hdmi/"><u>Laptop to TV Connection Repair via HDMI</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/enhancing-vr-experience-with-functional-freesync/"><u>Enhancing VR Experience with Functional FreeSync</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/successfully-addressed-and-resolved-comexception-issue/"><u>Successfully Addressed and Resolved COMException Issue</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-top-8-android-visionaries-for-speedy-videos/"><u>In 2024, Top 8 Android Visionaries for Speedy Videos</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/ensuring-smooth-performance-updating-your-pcs-graphics-driver/"><u>Ensuring Smooth Performance: Updating Your PC's Graphics Driver</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/addressing-script-failures-civilization-v-edition/"><u>Addressing Script Failures, Civilization V Edition</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/effortless-clear-uninterrupted-videos/"><u>Effortless Clear, Uninterrupted Videos</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-laugh-ledger-pinpointing-prime-meme-generators/"><u>[New] Laugh Ledger  Pinpointing Prime Meme Generators</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/dell-monitors-no-longer-flicker-successful-troubleshooting/"><u>Dell Monitors No Longer Flicker: Successful Troubleshooting</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resetting-asus-webcam-to-work-forward/"><u>Resetting ASUS Webcam To Work Forward</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-the-best-of-both-worlds-free-and-paid-3d-animation-software-solutions-for-2024/"><u>Updated The Best of Both Worlds Free and Paid 3D Animation Software Solutions for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/saving-the-day-resurrected-hdmi-connection/"><u>Saving the Day: Resurrected HDMI Connection</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/prime-steadicams-to-elevate-uav-video-production-quality-for-2024/"><u>Prime Steadicams to Elevate UAV Video Production Quality for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/curing-laptop-screen-flickers-in-lenovo-models/"><u>Curing Laptop Screen Flickers in Lenovo Models</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fix-for-flickering-keeping-your-display-steady/"><u>Fix for Flickering: Keeping Your Display Steady</u></a></li>
</ul></div>
