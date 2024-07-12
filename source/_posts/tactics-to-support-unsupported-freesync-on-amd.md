---
title: Tactics to Support Unsupported FreeSync on AMD
date: 2024-07-11T17:42:41.418Z
updated: 2024-07-12T17:42:41.418Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: This Article Describes Tactics to Support Unsupported FreeSync on AMD
excerpt: This Article Describes Tactics to Support Unsupported FreeSync on AMD
keywords: FreeSync Compatibility,AMD FreeSync Tips,Unsupported FreeSync Resolution,FreeSync Fix Guide AMD,Enhancing FreeSync on AMD Graphics Cards,AMD FreeSync Alternatives,FreeSync Adaptation Methods for AMD
thumbnail: https://thmb.techidaily.com/2738dcb65655ca3023848f9ec7026a9cce211e70815a31f4f65d2f9ea9ded629.jpg
---

## Tactics to Support Unsupported FreeSync on AMD

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
<li><a href="https://graphic-issues.techidaily.com/optimize-your-gpu-with-latest-driver/"><u>Optimize Your GPU with Latest Driver</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/catalyzing-stalled-gpu-fans-back-into-motion/"><u>Catalyzing Stalled GPU Fans Back Into Motion</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/easing-big-windows-11-resolution-issue/"><u>Easing Big Windows 11 Resolution Issue</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/regaining-access-to-nvidia-writable-displays/"><u>Regaining Access to NVIDIA' Writable Displays</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/tackling-nvidiaintel-hybrid-card-problems-in-windows/"><u>Tackling NVIDIA/Intel Hybrid Card Problems in Windows</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/the-screen-stillness-manifesto-banish-flickering/"><u>The Screen Stillness Manifesto: Banish Flickering</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/next-level-graphics-nvidia-210-software-upgrade-for-windows-10/"><u>Next-Level Graphics: NVIDIA 210 Software Upgrade for Windows 10</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-proiphone-photo-techniques-for-beginners/"><u>2024 Approved  Proiphone Photo Techniques for Beginners</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-or-downgrade-iphone-se-2020-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade iPhone SE (2020) Without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/perfected-preferences-save-after-glitch-overhaul/"><u>Perfected Preferences Save After Glitch Overhaul</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-2024-approved-decibel-defense-empowering-users-to-tame-digital-audio-chaos/"><u>New 2024 Approved Decibel Defense Empowering Users to Tame Digital Audio Chaos</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-a-curated-selection-top-8-streaming-audio-tools-to-enhance-your-broadcasts/"><u>Updated A Curated Selection Top 8 Streaming Audio Tools to Enhance Your Broadcasts</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-jump-into-todays-buzzing-tiktok-trials-for-2024/"><u>[New] Jump Into Today's Buzzing TikTok Trials for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/upgraded-graphics-performance-with-new-nvidia-drivers-on-windows/"><u>Upgraded Graphics Performance with New NVIDIA Drivers on Windows</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/monitor-failure-with-bg-black/"><u>Monitor Failure with BG-Black</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-amd-freesync-compatibility-hurdles/"><u>Overcoming AMD FreeSync Compatibility Hurdles</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/stabilize-no-more-flicker-in-win11/"><u>Stabilize: No More Flicker in Win11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-the-vr-wave-crafting-engaging-360-video-narratives-for-youtube-audiences/"><u>In 2024, The VR Wave  Crafting Engaging 360 Video Narratives for YouTube Audiences</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/win11-resolved-gpu-issues-in-latest-laptop-model/"><u>Win11 Resolved GPU Issues in Latest Laptop Model</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/gpu-compatibility-windows-11-laptop-confirmed/"><u>GPU Compatibility: Windows 11 Laptop Confirmed</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/dusk-to-dawn-for-darkened-windows-11-win11/"><u>Dusk to Dawn for Darkened Windows 11 Win11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-ultimate-guide-to-mastering-multi-tasking-with-your-favorite-talk-shows/"><u>In 2024, The Ultimate Guide to Mastering Multi-Tasking With Your Favorite Talk Shows</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-disabled-gpu-on-your-laptop-win1011/"><u>Overcoming Disabled GPU On Your Laptop (Win10/11)</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/combatting-the-blackout-on-a-laptop-monitor/"><u>Combatting the Blackout on a Laptop Monitor</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-bypass-the-required-apple-store-verification-for-apple-iphone-13-by-drfone-ios/"><u>How To Bypass the Required Apple Store Verification For Apple iPhone 13</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-quicktime-video-editing-made-easy-top-10-free-tools/"><u>In 2024, QuickTime Video Editing Made Easy Top 10 Free Tools</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/gpu-not-present-screen-blank/"><u>GPU Not Present, Screen Blank</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-premium-15-high-resolution-camcorders-reviewed/"><u>2024 Approved  Premium 15 High-Resolution Camcorders Reviewed</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-quick-fixes-enhancing-your-snaps-with-snapchat-edits/"><u>2024 Approved  Quick Fixes  Enhancing Your Snaps with Snapchat Edits</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-enhancing-social-media-reach-with-tweets-in-video-form-insta-style/"><u>[Updated] Enhancing Social Media Reach with Tweets in Video Form, Insta Style</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-gpu-challenges-while-ensuring-computer-survival/"><u>Overcoming GPU Challenges While Ensuring Computer Survival</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-itel-p55-5g-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Itel P55 5G to Other Android Devices? | Dr.fone</u></a></li>
</ul></div>
