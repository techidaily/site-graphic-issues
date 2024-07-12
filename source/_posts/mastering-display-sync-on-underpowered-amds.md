---
title: Mastering Display Sync on Underpowered AMDs
date: 2024-07-11T17:29:45.512Z
updated: 2024-07-12T17:29:45.512Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: This Article Describes Mastering Display Sync on Underpowered AMDs
excerpt: This Article Describes Mastering Display Sync on Underpowered AMDs
keywords: AMD Performance Optimization,Display Synchronization Techniques for AMD CPUs,Underpowered AMD Graphics Troubleshooting,Optimizing Underperforming AMD GPUs,Effective Display Sync for Budget AMD PCs,Enhancing AMD CPU Performance with Display Synchronization,AMD Processor Latency Reduction
thumbnail: https://thmb.techidaily.com/f3acba4ab3a16a6eb071b7ad05fb5dc6bcda3ad9bf54bc2e5b6e949de6c9c500.jpg
---

## Mastering Display Sync on Underpowered AMDs

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
<li><a href="https://graphic-issues.techidaily.com/amplifying-clarity-of-in-game-notifications/"><u>Amplifying Clarity of In-Game Notifications</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/successfully-solved-lenovo-interactive-screens/"><u>Successfully Solved Lenovo Interactive Screens</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/switching-gpu-issues-nvidiaintel-on-win10-fixed/"><u>Switching GPU Issues: Nvidia/Intel on Win10 - Fixed!</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-masterclass-youtube-music-arrangement/"><u>[Updated] Masterclass  YouTube Music Arrangement</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/revamp-windows-10s-visual-performance-via-intel-driver-update/"><u>Revamp Windows 10'S Visual Performance via Intel Driver Update</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-the-updated-method-to-bypass-honor-90-lite-frp-by-drfone-android/"><u>In 2024, The Updated Method to Bypass Honor 90 Lite FRP</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolved-reinstalling-nvidia-software/"><u>Resolved: Reinstalling NVIDIA Software</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/display-initialization-disrupted/"><u>Display Initialization Disrupted</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/comresol-critical-comerror-in-winos-addresses/"><u>ComResol: Critical COMError in WinOS Addresses</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-instagram-ready-auto-resizing-videos-using-mac-tech/"><u>[Updated] In 2024, Instagram-Ready  Auto-Resizing Videos Using Mac Tech</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-exploring-bandicam-ultimate-guide-to-screen-capture/"><u>2024 Approved  Exploring Bandicam  Ultimate Guide to Screen Capture</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/eliminated-flickering-on-laptops-display-panels/"><u>Eliminated Flickering on Laptops' Display Panels</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-reinstating-lost-sound-output-in-obs-recordings/"><u>2024 Approved  Reinstating Lost Sound Output in OBS Recordings</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-dimness-in-lenovo-displays/"><u>Overcoming Dimness in Lenovo Displays</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/steps-to-fix-c1900101-issue-when-installing-windows-11/"><u>Steps to Fix C1900101 Issue When Installing Windows 11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolving-incorrect-win10-resolution/"><u>Resolving Incorrect Win10 Resolution</u></a></li>
<li><a href="https://extra-resources.techidaily.com/crafting-excellent-micro-photography-videos-step-by-step-for-2024/"><u>Crafting Excellent Micro Photography Videos Step by Step for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/1719817865704-update-intel-graphics-3000-driver-for-windows-11-easily/"><u>Update Intel Graphics 3000 Driver for Windows 11. Easily!</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-activate-and-use-life360-ghost-mode-on-apple-iphone-13-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, How To Activate and Use Life360 Ghost Mode On Apple iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/from-live-to-recorded-simplifying-facebook-broadcasting-for-2024/"><u>From Live to Recorded  Simplifying Facebook Broadcasting for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-unlock-the-secrets-for-a-viral-instagram-account-gain-fans-and-verified-status-in-less-than-150-characters/"><u>[Updated] 2024 Approved  Unlock the Secrets for a Viral Instagram Account  Gain Fans and Verified Status in Less Than 150 Characters</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/dark-to-light-solving-win11-shadow-issue-post-fall/"><u>Dark to Light: Solving Win11 Shadow Issue Post Fall</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-windows-10-screen-blankness/"><u>Overcoming Windows 10 Screen Blankness</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-nokia-c12-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Nokia C12 Pro | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/unable-to-launch-full-screen-in-windows-11/"><u>Unable to Launch Full Screen in Windows 11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/reinitiating-your-gpus-spinning-fans/"><u>Reinitiating Your GPU's Spinning Fans</u></a></li>
<li><a href="https://animation-videos.techidaily.com/2024-approved-10-caricature-makers-to-turn-photo-to-caricature-effects/"><u>2024 Approved 10 Caricature Makers to Turn Photo to Caricature Effects</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/end-upside-down-screen-problems-in-windows-10/"><u>End Upside-Down Screen Problems in Windows 10</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overhaul-asus-display-stop-the-shimmer-effect/"><u>Overhaul ASUS Display: Stop the Shimmer Effect</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/refinement-of-visual-settings-in-latest-win11-update/"><u>Refinement of Visual Settings in Latest Win11 Update</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/unlocking-vivid-visuals-on-twitch/"><u>Unlocking Vivid Visuals on Twitch</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/correction-of-screen-boundary-alignment/"><u>Correction of Screen Boundary Alignment</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/unmasking-the-invisible-dx-hiccup-in-legion-of-lol/"><u>Unmasking the Invisible DX Hiccup in Legion of LoL</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/address-graphics-issue-in-windowsminecraft/"><u>Address Graphics Issue in Windows/Minecraft</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-diverse-technology-scrutiny-easeus-edition/"><u>In 2024, Diverse Technology Scrutiny  EaseUS Edition</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixed-directx12-obstacle-for-expected-halo-launch/"><u>[FIXED] DirectX12 Obstacle for Expected Halo Launch</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/missing-gpu-support-amd-and-windows-oses/"><u>Missing GPU Support: AMD and Windows OSes</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/mastering-the-art-of-fixing-crashing-gpus-without-shutdown/"><u>Mastering the Art of Fixing Crashing GPUs without Shutdown</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixing-system-compatibility-for-intel-graphics-support/"><u>Fixing System Compatibility for Intel Graphics Support</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-itel-p55-5g-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Itel P55 5G? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-methods-to-mirror-lava-yuva-3-to-roku-drfone-by-drfone-android/"><u>In 2024, 3 Methods to Mirror Lava Yuva 3 to Roku | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/easier-streaming-on-updated-windows-10/"><u>Easier Streaming on Updated Windows 10</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-the-social-media-strategists-guide-to-adjustable-video-sizes-on-fb/"><u>[Updated] 2024 Approved  The Social Media Strategist's Guide to Adjustable Video Sizes on FB</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/adjust-monitor-setup-in-windows-7/"><u>Adjust Monitor Setup in Windows 7</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-windows-10-white-out/"><u>Overcoming Windows 10 White Out</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-from-vivo-v27-pro-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock from Vivo V27 Pro Phones with/without a PC</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/no-graphic-detection-action-required/"><u>No Graphic Detection, Action Required!</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-10-best-3ds-emulator-you-can-find-on-pc/"><u>[New] 10 Best 3Ds Emulator You Can Find on PC</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-leveraging-pip-for-multitasking-in-edge-browser/"><u>[Updated] Leveraging PIP for Multitasking in Edge Browser</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolvingcomputerscreenflip/"><u>ResolvingComputerScreenFlip</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-enhancing-visual-acuity-of-youtubefacebook-playbacks/"><u>[New] Enhancing Visual Acuity of YouTube/Facebook Playbacks</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-methods-to-mirror-poco-x5-to-roku-drfone-by-drfone-android/"><u>In 2024, 3 Methods to Mirror Poco X5 to Roku | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/integrating-songs-and-snaps-online/"><u>Integrating Songs and Snaps Online</u></a></li>
</ul></div>
