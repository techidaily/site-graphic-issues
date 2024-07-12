---
title: Guidelines to Enable AMD FreeSync
date: 2024-07-11T17:52:32.556Z
updated: 2024-07-12T17:52:32.556Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: This Article Describes Guidelines to Enable AMD FreeSync
excerpt: This Article Describes Guidelines to Enable AMD FreeSync
keywords: FreeSync Compatible Monitors,Optimize G-Sync Alternative,FreeSync Sync Speed Benefits,Implementing AMD FreeSync,FreeSync Vs. FidelityGrade LUTs,Enhancing Display Technology with FreeSync,FreeSync Sync Range Optimization
thumbnail: https://thmb.techidaily.com/c8166e8b96eec7a32e2c5447a156a34a01b3ade6d8a5a024a318a811ffe0e892.jpg
---

## Guidelines to Enable AMD FreeSync

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
<li><a href="https://some-knowledge.techidaily.com/how-to-seamlessly-add-pictures-to-youtube-videos-for-2024/"><u>How to Seamlessly Add Pictures to YouTube Videos for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-4-sim-location-trackers-to-easily-find-your-lost-realme-v30-device-by-drfone-android/"><u>Top 4 SIM Location Trackers To Easily Find Your Lost Realme V30 Device</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-in-2024-dont-let-crashes-hold-you-back-fcpx-troubleshooting-guide/"><u>New In 2024, Dont Let Crashes Hold You Back FCPX Troubleshooting Guide</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/dx12-glitch-blocks-new-halo-infinite-release/"><u>DX12 Glitch Blocks New Halo Infinite Release</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/nvidia-brings-better-performance-to-windows-11-geforce-210/"><u>NVIDIA Brings Better Performance to Windows 11, GeForce 210</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-maximizing-audience-reach-the-6-step-roadmap-to-youtube-success/"><u>[New] 2024 Approved  Maximizing Audience Reach  The 6-Step Roadmap to YouTube Success</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/winos-bsod-remedy-wdf-blue-screen-anomaly/"><u>WinOS BSOD: Remedy WDF Blue Screen Anomaly</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/streamline-recovery-of-non-responsive-dp-port/"><u>Streamline Recovery of Non-Responsive DP Port</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-fix-oem-unlock-missing-on-poco-f5-pro-5g-by-drfone-android/"><u>How To Fix OEM Unlock Missing on Poco F5 Pro 5G?</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/adjustment-for-small-win-10-interface/"><u>Adjustment for Small WIN 10 Interface</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-mobile-focus-top-gimbal-systems-for-dynamic-shooting/"><u>In 2024, Mobile Focus  Top Gimbal Systems for Dynamic Shooting</u></a></li>
<li><a href="https://vp-tips.techidaily.com/podcast-perfection-best-timing-strategy-for-2024/"><u>Podcast Perfection  Best Timing Strategy for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixing-error-nvidia-setup-completed/"><u>Fixing Error: NVIDIA Setup Completed</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-elevate-meta-descriptions-top-template-strategies/"><u>[Updated] In 2024, Elevate Meta Descriptions  Top Template Strategies</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/shed-light-on-dark-lenovo-screens/"><u>Shed Light on Dark Lenovo Screens</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-10-ways-to-make-your-own-hit-tiktok-video-responses/"><u>2024 Approved  10 Ways to Make Your Own Hit TikTok Video Responses</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fix-displayport-no-signal-easily/"><u>Fix DisplayPort No Signal Easily</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixing-direct3d-non-availability-in-graphics-card/"><u>Fixing Direct3D Non-Availability in Graphics Card</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/reining-in-the-reflexive-responses-of-acer-displays/"><u>Reining in the Reflexive Responses of Acer Displays</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/mending-blank-windows-10-interface-error/"><u>Mending Blank Windows 10 Interface Error</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/avoid-livestream-frustration-addressing-facebook-outages-for-2024/"><u>Avoid Livestream Frustration  Addressing Facebook Outages for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/best-methods-for-honor-70-lite-5g-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Best Methods for Honor 70 Lite 5G Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-get-ready-for-lightning-fast-video-editing-with-64-bit-technology/"><u>New 2024 Approved Get Ready for Lightning-Fast Video Editing with 64-Bit Technology</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-maximize-engagement-with-ideal-video-dimensions-on-insta/"><u>In 2024, Maximize Engagement with Ideal Video Dimensions on Insta</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-top-ten-online-havens-escaping-stress-through-digital-tranquility/"><u>New In 2024, Top Ten Online Havens Escaping Stress Through Digital Tranquility</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/restore-failed-saving-of-displays-tips-for-win-7-and-10-users-resolved/"><u>Restore Failed Saving of Displays: Tips for Win 7 & 10 Users [Resolved]</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-2024-approved-how-to-un-refresh-and-restore-your-tiktok-videos/"><u>[Updated] 2024 Approved  How to Un-Refresh and Restore Your TikTok Videos</u></a></li>
<li><a href="https://extra-hints.techidaily.com/picture-perfect-in-the-sky-discover-infinite-complimentary-and-paid-cloud-repositories/"><u>Picture Perfect in the Sky  Discover Infinite, Complimentary, & Paid Cloud Repositories</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/precision-steps-for-upgraded-intel-gpu-in-win7/"><u>Precision Steps for Upgraded Intel GPU in Win7</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/amplifying-audio-on-social-media-video-tweets/"><u>Amplifying Audio on Social Media Video Tweets</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/uninstall-graphics-drivers-swiftly-in-windows/"><u>Uninstall Graphics Drivers Swiftly in Windows</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/screen-functionality-restored-22/"><u>Screen Functionality Restored - #22</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/mastering-the-modernization-of-intellgraphics-on-win7-machines/"><u>Mastering the Modernization of IntellGraphics on Win7 Machines</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/enhanced-display-precision-on-windows-11/"><u>Enhanced Display Precision on Windows 11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/exploring-superior-visuality-the-truth-of-4k-resolution/"><u>Exploring Superior Visuality: The Truth of 4K Resolution</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/from-darkness-into-light-a-guide-for-asus-laptop-owners/"><u>From Darkness Into Light: A Guide for Asus Laptop Owners</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/seamless-system-shutdown-graphics-drivers-uninstallation/"><u>Seamless System Shutdown: Graphics Drivers Uninstallation</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/solved-halo-infinite-not-launching-due-to-directx12-error/"><u>[SOLVED] Halo Infinite Not Launching Due to DirectX12 Error</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-tips-for-itunes-podcast-enrollment/"><u>In 2024, Tips for iTunes Podcast Enrollment</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolve-pcs-ignorance-of-gpu-hardware/"><u>Resolve PC's Ignorance of GPU Hardware</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/non-detecting-graphics-interface/"><u>Non-Detecting Graphics Interface</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/refining-win-drivers-fixed-battery-functionality/"><u>Refining Win Drivers, Fixed Battery Functionality</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-i-recover-permanently-deleted-photos-from-honor-100-pro-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>Can I recover permanently deleted photos from Honor 100 Pro</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/laptop-to-monitor-revive-dead-hdmi-connection/"><u>Laptop to Monitor: Revive Dead HDMI Connection</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/elevating-visual-fidelity-introduction-to-4k/"><u>Elevating Visual Fidelity: Introduction to 4K</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-grasping-chroma-key-magic-a-complete-beginners-guide-to-green-screens/"><u>[Updated] 2024 Approved  Grasping Chroma Key Magic  A Complete Beginner's Guide to Green Screens</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-broadcast-power-play-which-livestream-tool-should-you-use/"><u>[Updated] 2024 Approved  Broadcast Power Play  Which Livestream Tool Should You Use?</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-value-oriented-pc-recording-tools/"><u>In 2024, Value-Oriented PC Recording Tools</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/drive-your-graphics-with-nvidia-210-on-windows-system/"><u>Drive Your Graphics with Nvidia 210 on Windows System</u></a></li>
<li><a href="https://network-issues.techidaily.com/display-reset-nvidia-overcomes-previous-hiccup/"><u>Display Reset: Nvidia Overcomes Previous Hiccup</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/rejuvenate-your-system-with-newest-intellgraphics-tech/"><u>Rejuvenate Your System with Newest IntellGraphics Tech</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/tweaked-radeon-streaming-error/"><u>Tweaked Radeon Streaming Error</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-elite-listings-easy-purchases-of-startup-youtube-revenue-streams/"><u>[Updated] 2024 Approved  Elite Listings  Easy Purchases of Startup YouTube Revenue Streams</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-breaking-the-streak-code-proven-techniques-for-2024/"><u>[Updated] Breaking the Streak Code  Proven Techniques for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/post-update-windows-10-say-goodbye-to-streaming-issues/"><u>Post-Update Windows 10 - Say Goodbye to Streaming Issues</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/rectified-overcoming-installer-roadblock/"><u>Rectified: Overcoming Installer Roadblock</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/the-blueprint-for-tiktok-profitability-mastering-filmmaker-funds/"><u>The Blueprint for TikTok Profitability – Mastering Filmmaker Funds</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/1719818151562-camera-fix-made-simple-overcome-zoom-issues-now/"><u>Camera Fix Made Simple: Overcome Zoom Issues Now!</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-adding-social-media-magic-snapchat-to-your-mac/"><u>[New] 2024 Approved  Adding Social Media Magic  Snapchat to Your Mac</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/tackling-expanded-viewport-on-windows-10-devices/"><u>Tackling Expanded Viewport on Windows 10 Devices</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overwatchs-graphics-issue-is-ahead-of-schedule/"><u>Overwatch's Graphics Issue Is Ahead of Schedule</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/how-to-make-lenovo-monitors-shine-brighter/"><u>How to Make Lenovo Monitors Shine Brighter</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-elevate-your-video-game-with-fb-upload-on-pc-and-android/"><u>[New] In 2024, Elevate Your Video Game with FB Upload on PC and Android</u></a></li>
<li><a href="https://extra-hints.techidaily.com/digitizing-creativity-prime-nft-generating-platforms-revealed/"><u>Digitizing Creativity  Prime NFT-Generating Platforms Revealed</u></a></li>
</ul></div>
