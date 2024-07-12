---
title: Troubleshooting Non-Functional AMD FreeSync
date: 2024-07-11T17:03:12.842Z
updated: 2024-07-12T17:03:12.842Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: This Article Describes Troubleshooting Non-Functional AMD FreeSync
excerpt: This Article Describes Troubleshooting Non-Functional AMD FreeSync
keywords: AMD FreeSync Troubleshooting,FreeSync Non-Functional Fix,AMD FreeSync Error Resolution,FreeSync Compatibility Issues,AMD FreeSync Performance Troubleshooting,FreeSync Settings Adjustment Guide,FreeSync System Recommendations
thumbnail: https://thmb.techidaily.com/cbd55a60b36d243580c486b7896cd6baf0fe5a1c6ab330fc24fdad62a19d7e96.jpeg
---

## Troubleshooting Non-Functional AMD FreeSync

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
<li><a href="https://graphic-issues.techidaily.com/cannot-initialize-graphical-display/"><u>Cannot Initialize Graphical Display</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/winstability-secure-preventing-bsod-from-wdf-violations/"><u>WinStability Secure: Preventing BSOD From WDF Violations</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/warning-missing-drivers-for-amd-graphics-adapter-on-win10/"><u>[WARNING!] Missing Drivers for AMD Graphics Adapter on Win10</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/quicksnap-pro-studio-tools-for-2024/"><u>QuickSnap Pro Studio Tools for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/1719818155431-how-to-fix-horizontal-lines-on-laptop-screen-quickly-and-easily/"><u>How To Fix Horizontal Lines On Laptop Screen. Quickly & Easily</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-cooldown-chart-on-motorola-edge-2023-drfone-by-drfone-virtual-android/"><u>Pokémon Go Cooldown Chart On Motorola Edge 2023 | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/5-star-channel-cutting-long-urls-down-for-youtube-videos/"><u>5-Star Channel  Cutting Long URLs Down for YouTube Videos</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-unlocking-customization-embedding-text-in-youtube-cards/"><u>[Updated] Unlocking Customization  Embedding Text in YouTube Cards</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/latest-driver-for-amds-hd-6950-graphics-on-w11-os/"><u>Latest Driver for AMD's HD 6950 Graphics on W11 OS</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fix-your-camera-now-a-2024-guide-to-zoom-functionality/"><u>Fix Your Camera Now: A 2024 Guide to Zoom Functionality</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-ultimate-booklist-tikbooks-for-your-next-read/"><u>In 2024, Ultimate Booklist  #TikBooks For Your Next Read</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/master-the-art-of-modernizing-intel-hd-graphics-on-windows/"><u>Master the Art of Modernizing Intel HD Graphics on Windows</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-a-step-by-step-strategy-for-dominating-the-digital-marketing-arena/"><u>[Updated] A Step-by-Step Strategy for Dominating the Digital Marketing Arena</u></a></li>
<li><a href="https://activate-lock.techidaily.com/unlock-your-device-icloud-dns-bypass-explained-and-tested-plus-easy-alternatives-on-apple-iphone-11-pro-by-drfone-ios/"><u>Unlock Your Device iCloud DNS Bypass Explained and Tested, Plus Easy Alternatives On Apple iPhone 11 Pro</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-whip-up-a-fresh-web-comedic-bite-sized-delight-for-2024/"><u>[Updated] Whip Up a Fresh Web Comedic Bite-Sized Delight for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-enhancements-in-vegaspro-with-its-2019-release/"><u>2024 Approved  The Enhancements in VegasPro with Its 2019 Release</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/tactics-for-transforming-youtube-list-layouts-for-2024/"><u>Tactics for Transforming YouTube List Layouts for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/from-snapshots-to-spectacular-exploring-polarrs-edits-deeply-for-2024/"><u>From Snapshots to Spectacular  Exploring Polarr's Edits Deeply for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-best-in-class-identifying-leading-screen-recording-for-macos/"><u>In 2024, Best in Class  Identifying Leading Screen Recording for macOS</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-11-and-geforce-7025-compatibility-fixed/"><u>Windows 11 & GeForce 7025 Compatibility Fixed</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/in-2024-cut-out-the-middleman-learn-to-trim-videos-online-with-kapwing/"><u>In 2024, Cut Out the Middleman Learn to Trim Videos Online with Kapwing</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-music-from-zte-axon-40-lite-by-fonelab-android-recover-music/"><u>Possible solutions to restore deleted music from ZTE Axon 40 Lite</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-master-screen-recording-on-windows-macos-and-android-devices/"><u>[Updated] 2024 Approved  Master Screen Recording on Windows, macOS, and Android Devices</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-your-top-choice-best-offline-mobile-games-for-endless-entertainment/"><u>In 2024, Your Top Choice  Best Offline Mobile Games for Endless Entertainment</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-gui-error-rectified-gfxui-back-online/"><u>Windows GUI Error Rectified: GfxUI Back Online</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/streamlined-repairs-gpu-no-monitor-attached/"><u>Streamlined Repairs: GPU, No Monitor Attached</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/easy-corrections-for-gpus-without-screens/"><u>Easy Corrections for GPUs Without Screens</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-no-cost-memes-made-simple-our-meme-kit/"><u>2024 Approved  No-Cost Memes Made Simple  Our Meme Kit</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-apex-screen-capture-tools-the-elite-line-up-for-2024/"><u>[Updated] Apex Screen Capture Tools  The Elite Line-Up for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-top-video-editing-tools-for-vloggers-free-and-paid-options-for-2024/"><u>Updated Top Video Editing Tools for Vloggers Free and Paid Options for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-10-brightness-fluctuation-fixed/"><u>Windows 10 Brightness Fluctuation Fixed</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/adjusting-display-scale-and-size-on-updated-win11-os/"><u>Adjusting Display Scale and Size on Updated Win11 OS</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-profiling-excellence-a-guide-to-refined-youtube-summaries/"><u>[New] Profiling Excellence  A Guide to Refined YouTube Summaries</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/immediate-feedback-loop/"><u>Immediate Feedback Loop</u></a></li>
<li><a href="https://fix-guide.techidaily.com/restore-missing-app-icon-on-realme-12plus-5g-step-by-step-solutions-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Restore Missing App Icon on Realme 12+ 5G Step-by-Step Solutions | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-art-of-dialogue-in-writing-scripts-for-2024/"><u>The Art of Dialogue in Writing Scripts for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/mastering-safe-mode-in-windows-8-graphics-cards-driver-uninstallation-methods/"><u>Mastering Safe Mode in Windows 8 - Graphics Cards Driver Uninstallation Methods</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/restoring-lost-link-reconnect-computer-and-television-hdmi/"><u>Restoring Lost Link: Reconnect Computer & Television HDMI</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/mending-amd-radeon-r9-drivers-for-w11-users/"><u>Mending AMD Radeon R9 Drivers for W11 Users</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/instantaneously-amplify-your-pcs-graphics-with-intels-driver-fix/"><u>Instantaneously Amplify Your PC's Graphics with Intels Driver Fix</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/cursor-enters-blacked-out-win11/"><u>Cursor Enters Blacked Out Win11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/successful-direct3d-boot-up-confirmed/"><u>Successful Direct3D Boot-Up Confirmed</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-10-display-fix-hidden-advanced-options/"><u>Windows 10 Display Fix: Hidden Advanced Options</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/tweaking-visual-settings-in-windows-11-now-available/"><u>Tweaking Visual Settings in Windows 11 Now Available</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/win11-shadow-issue-fixes-for-fall-creators-patch/"><u>Win11 Shadow Issue - Fixes for Fall Creator's Patch</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-how-to-add-music-to-instagram-videos-and-stories/"><u>[Updated] How to Add Music to Instagram Videos and Stories</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/the-hidden-direct-x-curse-cleared-from-league-of-legends/"><u>The Hidden Direct X Curse Cleared From League of Legends</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/unleashing-system-stability-safe-mode-and-gpu-drivers-removal-guide-for-win8/"><u>Unleashing System Stability: Safe Mode and GPU Drivers Removal Guide for WIN8</u></a></li>
</ul></div>
