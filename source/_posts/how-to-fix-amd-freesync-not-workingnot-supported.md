---
title: How to Fix AMD FreeSync Not Working/Not Supported
date: 2024-07-11T17:48:32.521Z
updated: 2024-07-12T17:48:32.521Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: This Article Describes How to Fix AMD FreeSync Not Working/Not Supported
excerpt: This Article Describes How to Fix AMD FreeSync Not Working/Not Supported
keywords: FreeSync Troubleshooting,AMD FreeSync Support,Fix FreeSync Display Issue,AMD FreeSync Compatibility Guide,FreeSync Error Resolution,Enabling AMD FreeSync,Best Practices for FreeSync Setup
thumbnail: https://thmb.techidaily.com/5f63ba1e3593ebd7d73d1c72fb68eace0cd63a5c8a537d585a504e6de4ee75de.jpg
---

## How to Fix AMD FreeSync Not Working/Not Supported

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
<li><a href="https://graphic-issues.techidaily.com/fixing-bios-routes-in-msi-windows-os/"><u>Fixing BIOS Routes in MSI Windows OS</u></a></li>
<li><a href="https://screen-capture.techidaily.com/effortless-no-cost-screening-of-android-gadgets-for-2024/"><u>Effortless, No-Cost Screening of Android Gadgets for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-11-screen-flashing-or-flickering-solved/"><u>Windows 11 Screen Flashing Or Flickering [SOLVED]</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/triumph-in-technicality-smooth-run-for-nvidia-nforce-630a/"><u>Triumph in Technicality: Smooth Run for Nvidia, nForce 630A</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/navigating-gpu-malfunctions-without-system-breaks/"><u>Navigating GPU Malfunctions Without System Breaks</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-tapestry-transitions-loom-recording-steps/"><u>[Updated] Tapestry Transitions  Loom Recording Steps</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/render-engine-failed-to-initialize/"><u>Render Engine Failed to Initialize</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/horizons-in-focus-easy-monitor-alignment-techniques/"><u>Horizons in Focus: Easy Monitor Alignment Techniques</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/advanced-graphics-tweaking-for-optimal-display-performance/"><u>Advanced Graphics Tweaking for Optimal Display Performance</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/correctupsidedownscreens/"><u>CorrectUpsideDownScreens</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/screen-inactive-graphics-card-not-found/"><u>Screen Inactive: Graphics Card Not Found</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/error-corrected-in-display-driver-recovery-achieved/"><u>Error Corrected in Display Driver: Recovery Achieved</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/identifying-null-pointer-to-nvidia-driver/"><u>Identifying Null-Pointer to Nvidia Driver</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/revolutionary-clear-window-tech/"><u>Revolutionary Clear Window Tech</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/enhancing-lenovo-laptop-vision-clarity/"><u>Enhancing Lenovo Laptop Vision Clarity</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/god-of-war-simplifying-complex-moves/"><u>'God of War': Simplifying Complex Moves</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-2024-approved-online-beat-detectors-you-should-try-now-online-and-free/"><u>[New] 2024 Approved  Online Beat Detectors You Should Try Now [Online & Free]</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolve-non-displaying-full-screen-in-windows-11-pcs/"><u>Resolve: Non-Displaying Full Screen in Windows 11 PCs</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/nvidia-card-not-compatible-with-windows-11-fix/"><u>Nvidia Card Not Compatible with Windows 11 [Fix]</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/ease-laptops-warped-display-lines-painlessly/"><u>Ease Laptop's Warped Display Lines Painlessly</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/breakthrough-on-sims-4-invisible-launching/"><u>Breakthrough on Sims 4 Invisible Launching</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/enhancinas-microsofts-windows-core-functions/"><u>Enhancinas Microsoft's Windows Core Functions</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixing-and-curing-screen-flashes-in-dell-computers/"><u>Fixing and Curing Screen Flashes in Dell Computers</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/precision-in-problem-solving-save-now/"><u>Precision in Problem-Solving: Save Now</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-effortless-video-streaming-on-your-facebook-page/"><u>2024 Approved  Effortless Video Streaming on Your Facebook Page</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/solved-video-driver-issue-43-quickly/"><u>Solved Video Driver Issue #43 Quickly</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-expertly-slice-your-videos-macs-finest-mp4-applications/"><u>2024 Approved  Expertly Slice Your Videos  Mac's Finest MP4 Applications</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-finding-your-footprint-in-the-world-of-youtube-comments/"><u>[New] Finding Your Footprint in the World of YouTube Comments</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/amds-compatibility-issue-with-win10-settled/"><u>AMD's Compatibility Issue with Win10, Settled</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/1719817589959-precision-in-problem-solving-save-now/"><u>Precision in Problem-Solving: Save Now!</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/troubleshooting-windows-11-streaming-problems-fixed/"><u>Troubleshooting Windows 11 Streaming Problems Fixed</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/drivers-glitch-code-43-overcome/"><u>Drivers' Glitch Code 43 Overcome</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/refining-win-os-render-performance-via-upgrades/"><u>Refining Win OS Render Performance via Upgrades</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/the-ultimate-list-of-windows-audio-equalization-software/"><u>The Ultimate List of Windows Audio Equalization Software</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/access-updated-nvidia-gtx-1060-drivers-online/"><u>Access Updated Nvidia GTX 1060 Drivers Online</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-beautys-brightest-stars-youtube-personalities-to-follow/"><u>[New] 2024 Approved  Beauty's Brightest Stars  YouTube Personalities to Follow</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/optimized-dual-gpu-operation-on-windows-10-with-nvidiaintel/"><u>Optimized Dual-GPU Operation on Windows 10 with Nvidia/Intel</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/easy-solution-stop-pc-crashes-in-fallout-4/"><u>Easy Solution: Stop PC Crashes in Fallout 4</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/latest-win11-enhancements-for-visual-customization/"><u>Latest Win11 Enhancements for Visual Customization</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-in-depth-analysis-and-exploration-adobe-storage-vs-competitors-options/"><u>2024 Approved  In-Depth Analysis & Exploration  Adobe Storage Vs. Competitors' Options</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/step-into-the-future-of-gaming-updated-amd-hd-6950-drivers-for-win10/"><u>Step Into the Future of Gaming: Updated AMD HD 6950 Drivers for Win10</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/troubleshoot-vertical-edges-misalignment-in-laptop-screens/"><u>Troubleshoot Vertical Edges Misalignment in Laptop Screens</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-enhanced-interaction-through-effective-zoom-screenshares/"><u>In 2024, Enhanced Interaction Through Effective Zoom Screenshares</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/restore-asus-video-output-capabilities/"><u>Restore ASUS Video Output Capabilities</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/ending-switchable-gpu-woes-nvidiaintel-fix-on-win10/"><u>Ending Switchable GPU Woes: Nvidia/Intel Fix on Win10</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/cracked-code-direct-x-quirk-no-longer-lurks-in-lol/"><u>Cracked Code: Direct X Quirk No Longer Lurks in LoL</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/simple-troubleshoot-for-dead-displayport/"><u>Simple Troubleshoot for Dead DisplayPort</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/conquered-initialization-obstacle/"><u>Conquered Initialization Obstacle</u></a></li>
</ul></div>
