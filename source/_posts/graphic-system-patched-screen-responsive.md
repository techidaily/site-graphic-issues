---
title: "Graphic System Patched: Screen Responsive"
date: 2025-02-13T16:06:15.239Z
updated: 2025-02-19T20:46:00.975Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: "This Article Describes Graphic System Patched: Screen Responsive"
excerpt: "This Article Describes Graphic System Patched: Screen Responsive"
keywords: Responsive Display Technology,Graphic System Updates,Screen Adaptability Features,Graphical User Interface Responsiveness,Adaptive Screen Technology,Dynamic Display System Patches,Flexible Screen Technology Updates
thumbnail: https://thmb.techidaily.com/f5fc965758dead74b06c9dd7514fff9b2e384059ddee924706920d8dd594b0c4.jpg
---

## Graphic System Patched: Screen Responsive

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
<li><a href="https://screen-activity-recording.techidaily.com/new-29-how-to-record-free-webinars-with-ease-and-precision/"><u>[New] 29 How-To Record Free Webinars with Ease and Precision</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-how-to-duplicate-your-instagram-posts-for-2024/"><u>[Updated] How to Duplicate Your Instagram Posts for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-the-video-sharing-triad-vimeo-vs-youtube-and-dailymotion-showdown/"><u>2024 Approved The Video Sharing Triad Vimeo vs YouTube & Dailymotion Showdown</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/apple-watch-ultra-2-review-tailor-made-for-me-and-a-100-off-celebration-on-labor-day/"><u>Apple Watch Ultra 2 Review: Tailor-Made for Me and a $100 Off Celebration on Labor Day</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-lava-yuva-3-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your Lava Yuva 3? Heres A Full Solution | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/elevate-your-pc-experience-with-new-intel-graphics-driver/"><u>Elevate Your PC Experience with New Intel Graphics Driver</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fix-unstable-lcd-on-dell-ultrabook-resolved/"><u>Fix: Unstable LCD on Dell Ultrabook Resolved</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-reset-a-locked-nokia-c32-phone-by-drfone-android/"><u>How to Reset a Locked Nokia C32 Phone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-elevate-your-videos-with-free-sound-effects-a-final-cut-pro-tutorial/"><u>In 2024, Elevate Your Videos with Free Sound Effects A Final Cut Pro Tutorial</u></a></li>
<li><a href="https://extra-resources.techidaily.com/master-tips-securing-audio-for-unboxing-vids/"><u>Master Tips Securing Audio for Unboxing Vids</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/no-light-after-driver-rollout/"><u>No Light After Driver Rollout</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/quick-remedies-keep-fallout-4-playing-smoothly-on-windows/"><u>Quick Remedies: Keep Fallout 4 Playing Smoothly on Windows</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/refinement-of-greenscreen-footage-a-video-editors-mantra/"><u>Refinement of Greenscreen Footage: A Video Editor’s Mantra</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/restored-flawless-operation-for-r9-drivers-in-w10/"><u>Restored Flawless Operation for R9 Drivers in W10</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/revitalized-gameplay-in-apex-legends/"><u>Revitalized Gameplay in Apex Legends</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/tips-to-avoid-gpu-fires-sustain-system-operation/"><u>Tips to Avoid GPU Fires: Sustain System Operation</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/to-upgrade-or-not-expert-advice-on-why-you-should-consider-the-latest-iphone-n-16-a-comprehensive-guide-editors/"><u>To Upgrade or Not: Expert Advice on Why You Should Consider the Latest iPhone N [16] - A Comprehensive Guide Editors</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/winos-stability-fixed-end-bluescreen-via-wdf-compliance/"><u>WinOS Stability Fixed: End BlueScreen via WDF Compliance</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/youtubes-erased-memories-how-to-revisit-them-online-for-2024/"><u>Youtube's Erased Memories How to Revisit Them Online for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6Wfzj6YNDM?si=WRZQD9zCdQ1_tW1b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

