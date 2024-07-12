---
title: "Resolved Display Glitch: Driver Now Active"
date: 2024-07-11T17:26:51.599Z
updated: 2024-07-12T17:26:51.599Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: "This Article Describes Resolved Display Glitch: Driver Now Active"
excerpt: "This Article Describes Resolved Display Glitch: Driver Now Active"
keywords: Display Glitch Resolution,Active Driver Software Update,Display Issue Fix,Software Bug Remediation,Driver Status Update,Software Glitch Resolution Tips,resolved display glitch driver now active
thumbnail: https://thmb.techidaily.com/db6e8bb5b9330de241494205e28fd162607bcee64226c4e5f87f88fc35435d44.jpg
---

## Resolved Display Glitch: Driver Now Active

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
<li><a href="https://graphic-issues.techidaily.com/no-more-video-glitches-on-upgraded-windows-10/"><u>No More Video Glitches on Upgraded Windows 10</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/bypassed-direct3d-delays-unleash-full-gpu-capabilities-now/"><u>Bypassed Direct3D Delays - Unleash Full GPU Capabilities Now</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/putting-a-stop-to-pulsating-patterns-in-acer-screens/"><u>Putting a Stop to Pulsating Patterns in Acer Screens</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-the-widows-11-setup-challenge-error-c1900101/"><u>Overcoming the WIDows 11 Setup Challenge: Error C1900101</u></a></li>
<li><a href="https://fox-http.techidaily.com/crafting-captivating-content-for-a-consistent-climb-in-subscribers/"><u>Crafting Captivating Content for a Consistent Climb in Subscribers</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/rectified-non-standard-laptop-display-layout/"><u>Rectified Non-Standard Laptop Display Layout</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-expert-approved-apple-video-editing-software-for-professionals/"><u>Updated 2024 Approved Expert-Approved Apple Video Editing Software for Professionals</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-11-and-geforce-7025-harmony-achieved/"><u>Windows 11 & GeForce 7025 Harmony Achieved</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-is-obs-studio-or-fraps-your-ideal-choice-for-capturing-screens/"><u>2024 Approved  Is OBS Studio or Fraps Your Ideal Choice for Capturing Screens?</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/guide-on-how-to-change-your-apple-id-email-address-on-apple-iphone-se-by-drfone-ios/"><u>Guide on How To Change Your Apple ID Email Address On Apple iPhone SE</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/no-more-glitches-nvidia-and-intel-graphics-on-win10-syncing-flawlessly/"><u>No More Glitches! NVIDIA & Intel Graphics on Win10 Syncing Flawlessly</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-facebook-video-maker-how-to-make-facebook-video/"><u>[Updated] Facebook Video Maker  How to Make Facebook Video</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolving-reflective-screen-woes/"><u>Resolving Reflective Screen Woes</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/decoding-and-correcting-youtubes-chroma-key-issues/"><u>Decoding and Correcting YouTube's Chroma Key Issues</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-11-laptop-gpu-identified-correctly/"><u>Windows 11 Laptop GPU Identified Correctly</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/diagnose-and-repair-gpu-detection-failure/"><u>Diagnose & Repair: GPU Detection Failure</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-best-way-to-color-grading-and-color-correction-in-filmora/"><u>Updated Best Way To Color Grading & Color Correction in Filmora</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-access-your-iphone-11-pro-when-you-forget-the-passcode-by-drfone-ios/"><u>In 2024, How to Access Your iPhone 11 Pro When You Forget the Passcode?</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/successful-reinstallation-of-amd-driver-on-windows-10/"><u>Successful Reinstallation of AMD Driver on Windows 10</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/invertedviewresolution/"><u>InvertedViewResolution</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/modifying-monitor-border-symmetry/"><u>Modifying Monitor Border Symmetry</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/tackle-frozen-screen-in-social-settings/"><u>Tackle Frozen Screen in Social Settings</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fine-tuning-screen-border-placement/"><u>Fine-Tuning Screen Border Placement</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/eliminate-tarkov-graphics-hiccups-for-amd/"><u>Eliminate Tarkov Graphics Hiccups for AMD</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/screen-error-no-more-code-22-solved/"><u>Screen Error No More: Code 22 Solved</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-11-to-fullscreen-but-monitor-wont-comply/"><u>Windows 11 to Fullscreen, But Monitor Won't Comply</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/taming-the-wobble-of-pro-7s-screen/"><u>Taming the Wobble of Pro 7'S Screen</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-get-ready-to-amaze-top-rated-3d-video-creation-tools/"><u>In 2024, Get Ready to Amaze Top-Rated 3D Video Creation Tools</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-exploring-high-definition-sw320-4k-monitor-experience/"><u>2024 Approved  Exploring High Definition  Sw320 4K Monitor Experience</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-foundations-first-what-to-invest-in-for-youtubing/"><u>[Updated] 2024 Approved  Foundations First  What To Invest In for YouTubing</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-exit-android-factory-mode-on-tecno-pova-6-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Exit Android Factory Mode On Tecno Pova 6 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-mastering-soundcloud-downloads-tips-and-tricks-for-mp3-conversion/"><u>2024 Approved Mastering Soundcloud Downloads Tips and Tricks for MP3 Conversion</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/how-to-optimize-vertical-or-horizontal-vids-on-fb-for-2024/"><u>How To Optimize Vertical or Horizontal Vids On FB for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/correct-monitor-rotation-for-win7/"><u>Correct Monitor Rotation for Win7</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/remedying-blurry-ui-elements-in-far-cry/"><u>Remedying Blurry UI Elements in Far Cry</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-the-archivists-edge-cutting-edge-strategies-for-social-downloads/"><u>[New] In 2024, The Archivist's Edge  Cutting-Edge Strategies for Social Downloads</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/glide-over-and-adjust-vertical-lines-on-monitors/"><u>Glide Over and Adjust Vertical Lines on Monitors</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixed-the-flashing-problems-for-good/"><u>Fixed the Flashing Problems for Good</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-graphical-forecast-the-dominant-23-social-themes/"><u>[Updated] In 2024, Graphical Forecast  The Dominant '23 Social Themes</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/leveling-screen-horizontal-borders/"><u>Leveling Screen Horizontal Borders</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-non-functional-windows-task-scheduler/"><u>Troubleshooting Non-Functional Windows Task Scheduler</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-kodi-freeze-in-new-win11-release/"><u>Overcoming Kodi Freeze in New Win11 Release</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-comprehensive-srt-education-and-resources/"><u>2024 Approved  Comprehensive SRT Education and Resources</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-best-of-the-best-unlimited-recorders-top12/"><u>[Updated] Best of the Best  Unlimited Recorders, #Top12</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/combatting-screenscape-irregularities-in-pro-7/"><u>Combatting Screenscape Irregularities in Pro 7</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/swift-update-process-for-enhanced-visual-experience-on-win10/"><u>Swift Update Process for Enhanced Visual Experience on Win10</u></a></li>
</ul></div>
