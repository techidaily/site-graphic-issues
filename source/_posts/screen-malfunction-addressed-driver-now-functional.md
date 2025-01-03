---
title: "Screen Malfunction Addressed: Driver Now Functional"
date: 2025-01-02T10:38:37.632Z
updated: 2025-01-03T10:19:14.431Z
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
<li><a href="https://youtube-lab.techidaily.com/-comprehensive-overview-recording-saving-and-sharing-youtube-videos-for-free-for-2024/"><u>[New] A Comprehensive Overview Recording, Saving & Sharing YouTube Videos for Free for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/issecting-mr-beasts-fortune-portfolio-for-2024/"><u>[New] Dissecting Mr. Beast's Fortune Portfolio for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-how-to-master-every-feature-of-periscope/"><u>[New] How to Master Every Feature of Periscope</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-efficient-methods-for-sharing-powerful-ppt-in-google-meet-sessions/"><u>[Updated] In 2024, Efficient Methods for Sharing Powerful PPT in Google Meet Sessions</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unlock-the-power-of-podcasts-15-tips-for-multitasking-and-growth/"><u>2024 Approved Unlock the Power of Podcasts 15 Tips for Multitasking and Growth</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/breathe-life-into-your-gpu-fans/"><u>Breathe Life Into Your GPU Fans</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/game-on-amds-hd-6950-drivers-now-available-for-w11/"><u>Game On! AMD's HD 6950 Drivers Now Available for W11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/gpu-fan-awakening-step-by-step-guide/"><u>GPU Fan Awakening: Step-by-Step Guide</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/graphics-disruption-device-unavailable/"><u>Graphics Disruption: Device Unavailable</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/graphics-system-stabilized-after-error-handling/"><u>Graphics System Stabilized After Error Handling</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/graphics-ui-down-in-windows-now-repaired/"><u>Graphics UI Down in Windows, Now Repaired</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/jumpstart-your-apex-playtime-with-precision-fixes/"><u>Jumpstart Your Apex Playtime with Precision Fixes</u></a></li>
<li><a href="https://win-studio.techidaily.com/lengel-elizabeth-2006-unlikely-heroes-the-women-who-changed-world-war-ii-public-affairs/"><u>Lengel, Elizabeth (2006). Unlikely Heroes: The Women Who Changed World War II. Public Affairs.</u></a></li>
<li><a href="https://fake-location.techidaily.com/looking-for-a-location-changer-on-vivo-y78t-look-no-further-drfone-by-drfone-virtual-android/"><u>Looking For A Location Changer On Vivo Y78t? Look No Further | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/precision-adjustment-fix-screen-horizontal-lines/"><u>Precision Adjustment - Fix Screen Horizontal Lines</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/tailored-tunes-creating-custom-youtube-playlists-for-2024/"><u>Tailored Tunes Creating Custom Youtube Playlists for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/ustream-examination-other-options-compared/"><u>Ustream Examination Other Options Compared</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

