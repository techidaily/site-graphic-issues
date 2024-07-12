---
title: "Video System Repaired: Driver Running Well"
date: 2024-07-11T16:54:07.347Z
updated: 2024-07-12T16:54:07.347Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: "This Article Describes Video System Repaired: Driver Running Well"
excerpt: "This Article Describes Video System Repaired: Driver Running Well"
keywords: Repaired Video Systems,Driver Performance Testing,Vehicle Audio System Repair,Video System Diagnostics,Professional Video System Fixes,Enhanced Vehicle Sound Quality,Expert Video System Repairs
thumbnail: https://thmb.techidaily.com/9768937f48cf302572d982e26e42ee65fe0cea8c30a424b4cbbdbad231eaae46.png
---

## Video System Repaired: Driver Running Well

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
<li><a href="https://graphic-issues.techidaily.com/speedy-driver-update-intel-graphics-3000-win11-style/"><u>Speedy Driver Update - Intel Graphics 3000, Win11 Style</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-the-aiff-converter-checklist-essential-features-to-look-for-for-2024/"><u>New The AIFF Converter Checklist Essential Features to Look For for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-check-if-your-honor-magic5-ultimate-is-unlocked-by-drfone-android/"><u>How To Check if Your Honor Magic5 Ultimate Is Unlocked</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/the-cloaked-direct-x-error-lols-solution-revealed/"><u>The Cloaked Direct X Error: LoL's Solution Revealed</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-elite-editing-selection-quality-software-for-youtubers/"><u>In 2024, Elite Editing Selection  Quality Software for YouTubers</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/ended-flickering-issue-in-dell-ultrabook-display/"><u>Ended Flickering Issue in Dell Ultrabook Display</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/efficient-utilization-of-whiteboard-features-in-zoom-meetings-for-2024/"><u>Efficient Utilization of Whiteboard Features in Zoom Meetings for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-poco-c55-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Poco C55 | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/rtx-3080-game-stability-tips/"><u>RTX 3080 Game Stability Tips</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-ways-to-track-xiaomi-redmi-note-12t-pro-without-them-knowing-drfone-by-drfone-virtual-android/"><u>3 Ways to Track Xiaomi Redmi Note 12T Pro without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/amd-radeon-r9-no-more-woes-on-windows-10/"><u>AMD Radeon R9 No More Woes on Windows 10</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-do-you-remove-restricted-mode-on-iphone-13-pro-max-by-drfone-ios/"><u>In 2024, How Do You Remove Restricted Mode on iPhone 13 Pro Max</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/strategies-to-overcome-youtubes-bluish-background-blues/"><u>Strategies to Overcome YouTube's Bluish Background Blues</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-raspberry-router-image-maker/"><u>In 2024, Raspberry Router  Image Maker</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-androids-low-cost-video-call-app-selection/"><u>[New] Android's Low Cost Video Call App Selection</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/1719817977189-unified-graphics-experience-achieved-nvidiaintel-for-win10/"><u>Unified Graphics Experience Achieved - Nvidia/Intel for Win10!</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixed-graphics-card-not-detected-issues/"><u>FIXED: Graphics Card Not Detected Issues</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/silent-screen-after-gfx-update/"><u>Silent Screen After GFX Update</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/how-to-fix-lenovo-laptop-screen-dim-issue/"><u>How to Fix Lenovo Laptop Screen Dim Issue</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-stolen-apple-iphone-xs-in-different-conditionsin-drfone-by-drfone-ios/"><u>In 2024, How To Unlock Stolen Apple iPhone XS In Different Conditionsin | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/adjusting-surface-pro-7s-visual-flux/"><u>Adjusting Surface Pro 7'S Visual Flux</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/new-laptop-gpu-works-smoothly-on-win11-os/"><u>New Laptop GPU Works Smoothly on Win11 OS</u></a></li>
<li><a href="https://some-guidance.techidaily.com/unveiling-8-premium-mp3-extraction-software-android-for-2024/"><u>Unveiling 8 Premium MP3 Extraction Software (Android) for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/dxgkrnlsys-freeze-in-windows-triumph/"><u>dxgkrnl.sys Freeze in Windows - Triumph</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/reverse-screen-angle-for-win7/"><u>Reverse Screen Angle for Win7</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-elite-lockpicking-games-for-thrill-seekers/"><u>2024 Approved  Elite Lockpicking Games for Thrill Seekers</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-quiet-browsing-of-fb-narratives-for-2024/"><u>[New] Quiet Browsing of FB Narratives for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/full-guide-to-fix-itoolab-anygo-not-working-on-samsung-galaxy-s21-fe-5g-2023-drfone-by-drfone-virtual-android/"><u>Full Guide to Fix iToolab AnyGO Not Working On Samsung Galaxy S21 FE 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/free-msnbc-live-online-stream-for-the-latest-shows-for-all-devices/"><u>Free MSNBC Live Online Stream for the Latest Shows for All Devices</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-2024-approved-no-download-zone-10-top-free-online-video-compressors/"><u>Updated 2024 Approved No-Download Zone 10 Top Free Online Video Compressors</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/gpu-drivers-issue-22-resolved/"><u>GPU Drivers: Issue #22 Resolved</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-flight-pioneers-face-off-dji-vs-gopro/"><u>[New] Flight Pioneers Face Off  DJI vs GoPro</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/restored-clear-screen-view-on-dell-notebook-pcs/"><u>Restored Clear Screen View on Dell Notebook PCs</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolving-windows-11-screen-reversal/"><u>Resolving Windows 11 Screen Reversal</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcome-split-screen-glitches-on-pcs/"><u>Overcome Split-Screen Glitches on PCs</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/2024-approved-the-ultimate-guide-to-creating-a-ken-burns-effect-in-software/"><u>2024 Approved The Ultimate Guide to Creating a Ken Burns Effect in Software</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-capturing-chats-complete-fbm-conversation-history/"><u>[New] In 2024, Capturing Chats  Complete FBM Conversation History</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/successfully-installed-nvidia-drivers-again/"><u>Successfully Installed NVIDIA Drivers Again</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixing-aspect-ratio-error-on-wide-windows-10-displays/"><u>Fixing Aspect Ratio Error on Wide Windows 10 Displays</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-selecting-optimal-frame-rate-30fps-vs-60fps-for-quality-recording/"><u>In 2024, Selecting Optimal Frame Rate  30Fps Vs. 60Fps for Quality Recording</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/soothe-no-more-flaring-screen-win11/"><u>Soothe: No More Flaring Screen Win11</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-complete-annihilation-of-youtube-shorts-accessibility/"><u>[Updated] In 2024, Complete Annihilation of YouTube Shorts Accessibility</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/bluescreen-fix-correcting-windows-wdf-issues/"><u>BlueScreen Fix: Correcting Windows WDF Issues</u></a></li>
<li><a href="https://printer-issues.techidaily.com/resolve-duplicate-documents-in-w11-printer-spool/"><u>Resolve Duplicate Documents in W11 Printer Spool</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolved-mhw-crash-code-12-graphics-armageddon-ended/"><u>[Resolved] MHW Crash Code 12 - Graphics Armageddon Ended</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-in-2024-7-best-daw-for-guitar-recording-and-players-perfect-solution/"><u>Updated In 2024, 7 Best DAW for Guitar Recording and Players (Perfect Solution)</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/swift-victory-in-apex-game-overhaul-complete/"><u>Swift Victory in Apex: Game Overhaul Complete!</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-saving-your-itunes-media-three-simple-steps/"><u>[New] In 2024, Saving Your iTunes Media  Three Simple Steps</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/shedding-light-on-fall-update-fixes-for-win10/"><u>Shedding Light on Fall Update Fixes for Win10</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/undetected-graphics-card-problem/"><u>Undetected Graphics Card Problem</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/tackling-intelnvidia-graphic-swapping-issue/"><u>Tackling Intel/Nvidia Graphic Swapping Issue</u></a></li>
</ul></div>
