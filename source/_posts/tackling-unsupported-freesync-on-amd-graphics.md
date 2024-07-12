---
title: Tackling Unsupported FreeSync on AMD Graphics
date: 2024-07-11T17:02:13.543Z
updated: 2024-07-12T17:02:13.543Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: This Article Describes Tackling Unsupported FreeSync on AMD Graphics
excerpt: This Article Describes Tackling Unsupported FreeSync on AMD Graphics
keywords: Unsupported FreeSync,AMD Graphics FreeSync Troubleshooting,FreeSync Compatibility Issues with AMD GPUs,Enabling Unsupported FreeSync on AMD Radeon,FreeSync Latency Reduction Techniques (AMD),Workarounds for Unsupported FreeSync on AMD Radeon,AMD Graphics
thumbnail: https://thmb.techidaily.com/e6c6b6e32249dbf76f20abd6c6055b57975d7da74a0ada4b319cc0a746113075.jpg
---

## Tackling Unsupported FreeSync on AMD Graphics

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
<li><a href="https://graphic-issues.techidaily.com/enhancing-windows-drivers-with-ms-tools/"><u>Enhancing Windows Drivers with MS Tools</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/reclaim-your-channel-from-dark-screens-on-twitch/"><u>Reclaim Your Channel From Dark Screens on Twitch</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/how-to-fix-windows-7-screen-flickering/"><u>How to Fix Windows 7 Screen Flickering</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/boost-graphics-card-functionality-update-gtx-1060/"><u>Boost Graphics Card Functionality, Update GTX 1060</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-your-apple-iphone-7-passcode-4-easy-methods-with-or-without-itunes-by-drfone-ios/"><u>How to Unlock Your Apple iPhone 7 Passcode 4 Easy Methods (With or Without iTunes)</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/elevate-views-a-guide-to-best-youtube-hash-tags-for-2024/"><u>Elevate Views  A Guide to Best YouTube Hash Tags for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/1719817886641-cam-problems-save-your-asus/"><u>Cam Problems? Save Your ASUS</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/correcting-lenovo-screen-brightness-fluctuations/"><u>Correcting Lenovo Screen Brightness Fluctuations</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolving-battle-challenges-in-god-of-war/"><u>Resolving Battle Challenges in 'God of War'</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolved-gpu-malfunction-alert-nvidia/"><u>Resolved: GPU Malfunction Alert (NVIDIA)</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-vivo-g2-to-computer-for-iphone-and-android-drfone-by-drfone-android/"><u>In 2024, How to Cast Vivo G2 to Computer for iPhone and Android? | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/narrow-down-overly-large-win-10-screen/"><u>Narrow Down Overly Large WIN 10 Screen</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-guide-to-consolidating-your-youtube-video-collection/"><u>[New] In 2024, Guide to Consolidating Your YouTube Video Collection</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/banishing-flicker-fix-your-lenovo-screen/"><u>Banishing Flicker: Fix Your Lenovo Screen</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/instant-drive-shedding-guide-for-graphics-removal/"><u>Instant Drive Shedding - Guide for Graphics Removal</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/addressing-lcd-issues-hp-laptop-fix/"><u>Addressing LCD Issues: HP Laptop Fix</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/optimized-graphics-drivers-for-nvidia-geforce-210-on-win11/"><u>Optimized Graphics Drivers for NVIDIA GeForce 210 on Win11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/bringing-light-to-darkened-windows-11-post-creators/"><u>Bringing Light to Darkened Windows 11 Post Creators</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/unlit-screen-following-graphics-install/"><u>Unlit Screen Following Graphics Install</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-mastering-time-lapse-a-guide-with-gopro-studio/"><u>2024 Approved  Mastering Time-Lapse  A Guide with GoPro Studio</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-10-displays-re-enable-advanced-settings/"><u>Windows 10 Displays: Re-Enable Advanced Settings</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/in-2024-right-moves-to-use-tts-in-descript/"><u>In 2024, Right Moves to Use TTS in Descript</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/normalize-windows-10-display-orientation/"><u>Normalize Windows 10 Display Orientation</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-filmora-guide-efficiently-convert-avi-files-to-gifs-on-both-operating-systems/"><u>In 2024, Filmora Guide  Efficiently Convert AVI Files to GIFs on Both Operating Systems</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-os-lacks-support-for-amd-graphics-cards/"><u>Windows OS Lacks Support for AMD Graphics Cards</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-dose-life360-notify-me-when-someone-checks-my-location-on-huawei-nova-y91-drfone-by-drfone-virtual-android/"><u>In 2024, Dose Life360 Notify Me When Someone Checks My Location On Huawei Nova Y91? | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/streamlining-win-10118-graphics-functions/"><u>Streamlining Win 10/11/8 Graphics Functions</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/eradicating-flickering-glitches-from-your-lenovo/"><u>Eradicating Flickering Glitches From Your Lenovo</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/1719818312100-efficiently-upgrade-your-intel-3000-drivers-make-win10-shine/"><u>Efficiently Upgrade Your Intel 3000 Drivers, Make Win10 Shine</u></a></li>
<li><a href="https://games-able.techidaily.com/secure-access-to-more-gaming-with-xbox-ultimate/"><u>Secure Access to More Gaming with Xbox Ultimate</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-the-graphic-problem-in-overwatch/"><u>Overcoming the Graphic Problem in Overwatch</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/video-streaming-problems-on-windows-10-after-upgrade-solved/"><u>Video Streaming Problems on Windows 10 After Upgrade [Solved]</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/1719817890200-no-graphic-detection-action-required/"><u>No Graphic Detection, Action Required</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-easy-way-to-edit-youtube-videos-in-imovie/"><u>2024 Approved  Easy Way to Edit YouTube Videos in iMovie</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/enhancing-rtx-3080-playtime-quality/"><u>Enhancing RTX 3080 Playtime Quality</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-boosting-engagement-the-key-to-successful-tiktok-unpack-videos/"><u>In 2024, Boosting Engagement  The Key to Successful TikTok Unpack Videos</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-mobile-video-mastery-top-split-screen-apps-for-iphone-and-android/"><u>New 2024 Approved Mobile Video Mastery Top Split Screen Apps for iPhone and Android</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/deciphered-the-veiled-direct-x-discreprancy-in-legion/"><u>Deciphered the Veiled Direct X Discreprancy in Legion</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/clearing-chroma-key-fuzziness-for-professional-online-videos/"><u>Clearing Chroma Key Fuzziness for Professional Online Videos</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-merge-mov-files-for-free-5-best-options/"><u>New Merge MOV Files for Free 5 Best Options</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/undetected-display-adapter-alert/"><u>Undetected Display Adapter Alert</u></a></li>
</ul></div>
