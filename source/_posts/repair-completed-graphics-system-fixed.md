---
title: "Repair Completed: Graphics System Fixed"
date: 2024-11-17T23:40:57.526Z
updated: 2024-11-24T07:36:14.966Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: "This Article Describes Repair Completed: Graphics System Fixed"
excerpt: "This Article Describes Repair Completed: Graphics System Fixed"
keywords: Graphics Card Repair,Fix Graphic System Issue,Repaired Graphics Setup,Graphic System Repair Service,Resolved Graphics Problem,Restored Graphic System Functionality,Graphics Repair Technician Expertise
thumbnail: https://thmb.techidaily.com/ee23f258f8acc5ad2795e172a146cef682a3a259b32871693580ae9137133cdf.jpg
---

## Repair Completed: Graphics System Fixed

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
<li><a href="https://fox-access.techidaily.com/new-getting-started-with-periscope-is-it-free-sign-up-process-for-2024/"><u>[New] Getting Started with Periscope Is It Free? Sign-Up Process for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-crafting-success-in-youtubes-creator-hub/"><u>[New] In 2024, Crafting Success in YouTube's Creator Hub</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-the-ultimate-guide-to-superior-free-lut-options/"><u>[New] The Ultimate Guide to Superior, Free LUT Options</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-innovative-drone-designs-always-on-your-side/"><u>[Updated] Innovative Drone Designs Always on Your Side</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-maximizing-video-impact-a-comprehensive-guide-to-youtube-popularity/"><u>2024 Approved Maximizing Video Impact A Comprehensive Guide to YouTube Popularity</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-sound-capture-gadget-testing/"><u>2024 Approved Sound Capture Gadget Testing</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722861175751-anticipating-the-arrival-of-google-pixel-9-estimated-pricing-details-revealed/"><u>Anticipating the Arrival of Google Pixel 9 - Estimated Pricing Details Revealed!</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/cannot-initialize-graphical-display/"><u>Cannot Initialize Graphical Display</u></a></li>
<li><a href="https://win-top.techidaily.com/enhancing-email-marketing-success-mastering-unique-address-management-with-massmails-advanced-cleanup-features/"><u>Enhancing Email Marketing Success: Mastering Unique Address Management with MassMail's Advanced Cleanup Features</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-innovative-approaches-to-macos-subtitles-editing/"><u>In 2024, Innovative Approaches to macOS Subtitles Editing</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-laptop-friendly-tips-to-start-live-chats-with-whatsapp-desktop/"><u>In 2024, Laptop-Friendly Tips to Start Live Chats with WhatsApp Desktop</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/instantaneously-amplify-your-pcs-graphics-with-intels-driver-fix/"><u>Instantaneously Amplify Your PC's Graphics with Intels Driver Fix</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/latest-driver-for-amds-hd-6950-graphics-on-w11-os/"><u>Latest Driver for AMD's HD 6950 Graphics on W11 OS</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/streamlined-repairs-gpu-no-monitor-attached/"><u>Streamlined Repairs: GPU, No Monitor Attached</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/the-hidden-direct-x-curse-cleared-from-league-of-legends/"><u>The Hidden Direct X Curse Cleared From League of Legends</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-10-brightness-fluctuation-fixed/"><u>Windows 10 Brightness Fluctuation Fixed</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-10-display-fix-hidden-advanced-options/"><u>Windows 10 Display Fix: Hidden Advanced Options</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-gui-error-rectified-gfxui-back-online/"><u>Windows GUI Error Rectified: GfxUI Back Online</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/winstability-secure-preventing-bsod-from-wdf-violations/"><u>WinStability Secure: Preventing BSOD From WDF Violations</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qfCSLAhd4FY?si=CUBztmilaeAwl1lw&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

