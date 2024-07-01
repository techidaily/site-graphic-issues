---
title: Making AMD FreeSync Work Across Systems
date: 2024-06-30T11:21:48.585Z
updated: 2024-07-01T11:21:48.585Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: This Article Describes Making AMD FreeSync Work Across Systems
excerpt: This Article Describes Making AMD FreeSync Work Across Systems
keywords: AMD FreeSync Compatibility,FreeSync Technology Integration,Synchronized Display Setup for AMD FreeSync,Cross-Platform FreeSync Support,FreeSync Performance Optimization Across Systems,HDR Gaming with AMD FreeSync,FreeSync and Multi-Monitor Setups
thumbnail: https://thmb.techidaily.com/3dae50570edf845253cb7d1a2a03642e6fd28847b0566a64ae5bae28165ba633.jpg
---

## Making AMD FreeSync Work Across Systems

![](https://images.drivereasy.com/wp-content/uploads/2021/12/freesync-not-supported.jpg)

 FreeSync is an AMD hack that can reduce screen tearing and stuttering. But 6 years after its release, gamers are still complaining about the**FreeSync not working** issue. And for some, their FreeSync monitors even say**FreeSync is not supported** .

 But don’t worry if you’re on the same boat. We’ve gathered most of the working fixes down below. Just try them and get FreeSync working right away.

 Before you start troubleshooting, first**make sure your monitor is AMD FreeSync compatible** . You can find out by checking the product page on the official website.

## Try these fixes

 You might not need to try them all. Simply work your way down until you hit the one that does the charm.

1. [**Try different ports**](#fix1)
2. [**Make sure you have the latest correct drivers**](#fix2)
3. [**Perform a clean boot**](#fix3)
4. [**Check for Windows updates**](#fix4)
5. [**Check the monitor settings**](#fix5)
6. [**Disable Fullscreen optimizations**](#fix6)
7. **[Configure the default GPU](#fix7)**

### Fix 1: Try different ports

 First you should check if it’s a hardware issue by changing to another port. For example, if you’re using HDMI, try DP instead and see how it goes. Note that you’ll need**a HDMI 2.0 or DP 1.2 cable** for FreeSync to work properly. If the other ports work perfectly, you might be looking at a faulty GPU/cable/monitor.

For your reference, here’s what HDMI and DP ports look like:

![](https://images.drivereasy.com/wp-content/uploads/2021/12/graphics-card-hdmi-dp-ports.jpg)

If the problem persists, take a look at the next fix.

### Fix 2: Check the monitor settings

 Some FreeSync monitors require users to**configure this function manually in OSD (on-screen display)** . If you don’t know what OSD is, it’s a jargon for the monitor control panel, where you can change viewing options and adjust general settings like brightness and contrast.

 To bring up OSD, look for**buttons or joysticks** at the bottom or the back of your monitor. You can also refer to the manual and explore the settings. If FreeSync is on by default, do a**factory reset** and see how it goes.

![](https://images.drivereasy.com/wp-content/uploads/2021/12/freesync-osd-dell.jpg)

 If this doesn’t fix the issue, simply continue to the next solution.

### Fix 3: Make sure you have the latest correct drivers

 This issue could also be graphics related. In other words, you could be using**a buggy or outdated graphics driver** . Before you try anything more advanced, first make sure you have the latest correct GPU driver.

 You can update your graphics drivers manually, by visiting the AMD website, finding the latest correct installer and installing step by step. But if you’re not comfortable playing with device drivers, you can use [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) to scan, repair and update all your drivers.

1. [**Download**](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.
2. Run Driver Easy, then click **Scan Now** . Driver Easy will then scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2021/08/scan-now-v5_7_0.jpg)
3. Click **Update All** to automatically download and install the correct version of _all_ the drivers that are missing or out of date on your system.  
 (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  – you’ll be prompted to upgrade when you click Update All. If you don’t want to pay for the Pro version, you can still download and install all the drivers you need with the free version; you just have to download them one at a time, and manually install them, the normal Windows way.)  
![](https://images.drivereasy.com/wp-content/uploads/2021/10/de-update-6700-xt-driver.jpg)

**The Pro version of Driver Easy** comes with _full technical support_ . If you need assistance, please contact **Driver Easy’s support team** at **[support@drivereasy.com](mailto:support@drivereasy.com) .**

 After updating all the drivers, restart your PC and check if FreeSync is working.

 If the latest drivers can’t solve your problem, simply check out the next method. (Or you can follow [this guide](https://tools.techidaily.com/drivereasy/download/) and do a clean reinstallation with DDU.)

### Fix 4:**Perform a clean boot**

 This issue could also indicate a compatibility issue, meaning that some other programs might be conflicting with each other. To rule out this possibility, you can do a clean boot.

1. On your keyboard, press**Win+R** (the Windows logo key and the r key) at the same time to invoke the Run box. Type or paste**msconfig** and click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/11/msconfig-clean-boot-1.jpg)
2. In the pop-up window, navigate to the **Services**  tab and check the box next to **Hide all Microsoft services** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/09/msconfig-hide-all-windows-services.jpg)
3. **Uncheck**  all the services EXCEPT those belong to your hardware manufacturers, such as **Realtek** , **AMD** , **NVIDIA** ,**Logitech** and **Intel** . Then click **OK**  to apply the changes.  
![](https://images.drivereasy.com/wp-content/uploads/2020/09/msconfig-disable-services-except-gpu-audio.jpg)
4. On your keyboard, press **Ctrl** , **Shift**  and **Esc**  at the same time to open Task Manager, then navigate to the **Startup**  tab.  
![](https://images.drivereasy.com/wp-content/uploads/2020/08/task-manager-startup.jpg)
5. One at a time, select any programs you suspect might be interfering, and click **Disable** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/08/task-manager-startup-disable-startup-program.jpg)
6. Restart your PC.

 If FreeSync works after a clean boot, you can root out the offending program by repeating these steps and disabling half of the services every time.

 If this trick doesn’t give you luck, take a look at the next one below.

### Fix 5: Check for Windows update

 You also need to make sure you have the latest patches for your system. Normally this is done automatically by your system, but you can also check if you’re missing any feature updates.

Here’s how:

1. On your keyboard, press**Win+I** (the Windows logo key and the i key) to open the Windows Settings app. Click**Update & Security** .  
![update & security](https://images.drivereasy.com/wp-content/uploads/2020/10/update-security-2.jpg)
2. Click**Check for updates** . Windows will then download and install the available patches. It might take some time (up to 30 mins).  
![](https://images.drivereasy.com/wp-content/uploads/2020/08/windows-security-update-click-check-for-update.jpg)

 To confirm you’ve installed _all_  the system updates, **repeat these steps** until it prompts “You’re up to date” when you click **Check for updates** .

 After installing all the system updates, restart and check if FreeSync is working.

If the issue is still there, simply try the next fix.

### Fix 6: Disable Fullscreen optimizations

 You can try this when FreeSync isn’t working in certain games or programs.

**Fullscreen optimization** is a Windows 10 feature which could improve the overall experience of full screen apps. But according to some users, this feature might be conflicting with FreeSync. You can try to disable it and see if that helps:

1. Right-click the program and select**Properties** .
2. Navigate to the **Compatibility**  tab. Under the **Settings**  section, check the box next to **Disable fullscreen optimizations** . Then click **OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/10/disable-fullscreen-optimizations.jpg)

Now restart the program and check if FreeSync is working.

If this doesn’t help, you can continue to the next method.

### Fix 7: Configure the default GPU

 If your PC has dual GPUs, say an integrated one comes with the CPU and a dedicated one, you might need to**specify the default GPU for your program** . Since FreeSync is currently only compatible with AMD GPUs, besides connecting the monitor to an AMD graphics card, you can also configure the default GPU for the program.

1. At the empty area of your desktop, right-click and select **Display settings** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/10/change-preferred-gpu-1.jpg)
2. Under the **Multiple displays** section, click **Graphics settings** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/10/change-preferred-gpu-2.jpg)
3. Click **Browse**  to specify the file location of the program/game launcher.  
![](https://images.drivereasy.com/wp-content/uploads/2021/12/change-preferred-gpu-3-clean.jpg)
4. Click**Options** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/10/change-preferred-gpu-4.jpg)
5. You’ll see three**graphics preference** . Select the**AMD** one and click**Save** .

Now launch the program/game and check if FreeSync is working.

---

 Hopefully you can now enjoy FreeSync with zero issues. If you have any questions or ideas, feel free to leave your thoughts in the comments below.

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
<li><a href="https://graphic-issues.techidaily.com/demystifying-ultra-high-definition-what-is-4k/"><u>Demystifying Ultra-High-Definition: What Is 4K?</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolving-win11-dark-display-post-fall-update/"><u>Resolving Win11 Dark Display Post-Fall Update</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/lenovo-tapscreen-troubleshoot-successful/"><u>Lenovo TapScreen Troubleshoot Successful</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/managing-oversized-windows-11-resolution/"><u>Managing Oversized Windows 11 Resolution</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/stepping-up-performance-in-underpowered-systems/"><u>Stepping Up Performance in Underpowered Systems</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/reverse-visual-output-windows-7-style/"><u>Reverse Visual Output, Windows 7 Style</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/reconnect-without-struggle-displayport-fix-guide/"><u>Reconnect Without Struggle: DisplayPort Fix Guide</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/ensuring-savable-displays-tips-for-win-710-users-success-done/"><u>Ensuring Savable Displays: Tips for Win 7/10 Users' Success [Done]</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/update-intel-graphics-3000-driver-for-windows-10-easily/"><u>Update Intel Graphics 3000 Driver for Windows 10. Easily</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-win10-screen-grabbing-top-quality-captures/"><u>[New] In 2024, Win10 Screen Grabbing - Top Quality Captures</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-facebook-dating-for-your-vivo-v27-drfone-by-drfone-virtual-android/"><u>How to Change Location On Facebook Dating for your Vivo V27 | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-unlock-the-power-of-engagement-to-monetize-facebook/"><u>[Updated] 2024 Approved  Unlock the Power of Engagement to Monetize Facebook</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-blurred-lines-the-art-of-anonymizing-youtube-content/"><u>[Updated] In 2024, Blurred Lines  The Art of Anonymizing YouTube Content</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-2024-approved-guitarists-picks-the-ranked-list-of-cutting-edge-recording-programs/"><u>Updated 2024 Approved Guitarists Picks The Ranked List of Cutting-Edge Recording Programs</u></a></li>
<li><a href="https://animation-videos.techidaily.com/in-2024-adobe-animate-riggings-tutorial-for-you/"><u>In 2024, Adobe Animate Riggings Tutorial for You</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-a-beginners-guide-to-video-editing-on-mac-create-stunning-movies/"><u>Updated 2024 Approved A Beginners Guide to Video Editing on Mac Create Stunning Movies</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-from-zero-to-hero-in-the-youtube-world-starting-your-channel-and-earning-money/"><u>2024 Approved  From Zero to Hero in the Youtube World  Starting Your Channel & Earning Money</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/new-in-2024-enhance-your-tiktok-viewing-experience/"><u>[New] In 2024, Enhance Your TikTok Viewing Experience</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-non-identifiable-video-blurring-private-elements-efficiently/"><u>[Updated] 2024 Approved  Non-Identifiable Video  Blurring Private Elements Efficiently</u></a></li>
</ul></div>
