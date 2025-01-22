---
title: "Screen Malfunction Addressed: Driver Now Functional"
date: 2025-01-15T22:31:12.068Z
updated: 2025-01-22T06:35:57.699Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: "This Article Describes Screen Malfunction Addressed: Driver Now Functional"
excerpt: "This Article Describes Screen Malfunction Addressed: Driver Now Functional"
keywords: Driver Replacement Guide,Car Screen Fix Solutions,Automotive Display Repair,Mobile Infotainment System Troubleshooting,Vehicle Display Replacement Parts,Car Screen Malfunction Resolution,Faulty Car Display Services
thumbnail: https://thmb.techidaily.com/e300204a9c5c4ef99d0dbdbfe019e1c08c97d2c1f2aff2ef7a7d48de12972255.jpg
---

## Screen Malfunction Addressed: Driver Now Functional

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
<li><a href="https://screen-capture.techidaily.com/new-image-recording-assistant-for-2024/"><u>[New] Image Recording Assistant for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-revolutionize-live-streaming-top-4-approaches-to-record-on-fb/"><u>[Updated] 2024 Approved Revolutionize Live Streaming Top 4 Approaches to Record on FB</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-rotating-the-ripple-effect-mastering-instagrams-video-manipulation-art/"><u>[Updated] 2024 Approved Rotating the Ripple Effect Mastering Instagram's Video Manipulation Art</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-professional-video-finishing-touches-device-based-filters/"><u>2024 Approved Professional Video Finishing Touches Device-Based Filters</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/approved-youtube-tv-everything-you-need-to-know/"><u>2024 Approved YouTube TV - Everything You Need to Know</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/dispel-sims-invisible-launching/"><u>Dispel Sims' Invisible Launching</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/how-do-i-fix-0xc1900101-error-when-installing-windows-10/"><u>How Do I Fix 0xC1900101 Error When Installing Windows 10</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-elite-alternative-edits-skip-youtube-not-just-content/"><u>In 2024, Elite Alternative Edits Skip Youtube, Not Just Content</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/labor-day-alert-grab-your-ipad-for-a-steal-at-199-on-amazon-sale-as-featured-by-zdnet/"><u>Labor Day Alert: Grab Your iPad for a Steal at $199 on Amazon Sale, as Featured by ZDNET</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolve-tear-free-display-technology/"><u>Resolve Tear-Free Display Technology</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/solve-anthem-lags-quickly/"><u>Solve Anthem Lags Quickly</u></a></li>
<li><a href="https://win-amazing.techidaily.com/step-by-step-guide-for-downloading-and-installing-broadcom-bluetooth-driver-on-win1187/"><u>Step-by-Step Guide for Downloading and Installing Broadcom Bluetooth Driver on Win11/8/7</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/updated-in-2024-6-must-have-tools-for-successful-game-streaming/"><u>Updated In 2024, 6 Must-Have Tools for Successful Game Streaming</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-11-laptop-now-using-latest-gpu-feature/"><u>Windows 11 Laptop Now Using Latest GPU Feature</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/q4-YQ9Wjtfg?si=6afn1fydg_Wb9B8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

