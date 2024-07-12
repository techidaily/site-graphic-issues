---
title: "GPU Malfunction Resolved: Screen Responding"
date: 2024-07-11T16:53:35.825Z
updated: 2024-07-12T16:53:35.825Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: "This Article Describes GPU Malfunction Resolved: Screen Responding"
excerpt: "This Article Describes GPU Malfunction Resolved: Screen Responding"
keywords: GPU Troubleshooting Guide,Repairing GPU Issues,Fixed GPU Screen Response,GPU Diagnostic and Fix,Overcoming GPU Display Problems,How to Resolve GPU Errors,Successful GPU Recovery Steps
thumbnail: https://thmb.techidaily.com/1b3acf6f92837e9104aa399e6aa268354b94b6b827af6bb095b68b19082ca48f.png
---

## GPU Malfunction Resolved: Screen Responding

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
<li><a href="https://graphic-issues.techidaily.com/discovering-the-fix-for-win11nvidia/"><u>Discovering the Fix for Win11/NVIDIA</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-charismatic-communicator-overview-part-8-for-2024/"><u>[New] Charismatic Communicator Overview, Part 8 for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-motorola-edge-40-drfone-by-drfone-android/"><u>How To Use Allshare Cast To Turn On Screen Mirroring On Motorola Edge 40 | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/enhanced-interaction-making-skype-calls-on-your-phone-for-2024/"><u>Enhanced Interaction  Making Skype Calls on Your Phone for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/breaking-through-d3d-init-blocks/"><u>Breaking Through D3D Init Blocks</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/direct-video-transfer-a-compreenas-guide-to-youtube-plus-tiktok-integration-for-2024/"><u>Direct Video Transfer  A Compreenas Guide to YouTube + TikTok Integration for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/banish-blur-effective-strategies-for-screen-stability/"><u>Banish Blur: Effective Strategies for Screen Stability</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/amd-radeon-r9-resolved-display-driver-woes-in-w10/"><u>AMD Radeon R9: Resolved Display Driver Woes in W10</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/streamline-win7-performance-integrating-latest-intel-drivers/"><u>Streamline Win7 Performance: Integrating Latest Intel Drivers</u></a></li>
<li><a href="https://extra-resources.techidaily.com/captivate-with-voice-intros-that-intrigue/"><u>Captivate with Voice  Intros That Intrigue</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/deal-mp4-slicer-for-mac-boost-your-vlog-game-for-2024/"><u>[New] Ideal MP4 Slicer for Mac  Boost Your Vlog Game for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/accessing-hidden-reaction-mechanisms-of-youtube-users-for-2024/"><u>Accessing Hidden Reaction Mechanisms of YouTube Users for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixing-missing-displays-via-nvidia-control-panel/"><u>Fixing Missing Displays via NVIDIA Control Panel</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixing-hulu-streaming-errors-after-win11s-latest-update/"><u>Fixing Hulu Streaming Errors After Win11's Latest Update</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/sculpt-your-media-techniques-for-excising-audio-in-iphones-and-mac-videos/"><u>Sculpt Your Media Techniques for Excising Audio in iPhones & Mac Videos</u></a></li>
<li><a href="https://facebook.techidaily.com/awaiting-the-call-facebook-orders-ruling-on-prohibited-access/"><u>Awaiting the Call: Facebook Orders Ruling on Prohibited Access</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-multiplatform-iptv-live-streaming/"><u>[Updated] In 2024, Multiplatform IPTV Live Streaming</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/drive-performance-streamlined-installation-of-intel-gfx-driver-for-win11/"><u>Drive Performance: Streamlined Installation of Intel GFX Driver for Win11</u></a></li>
<li><a href="https://fox-links.techidaily.com/elite-echoes-outstanding-games-for-your-google-cardboard-for-2024/"><u>Elite Echoes  Outstanding Games for Your Google Cardboard for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/tomorrows-insight-rethinking-choices/"><u>Tomorrow's Insight  Rethinking Choices</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-mastering-the-process-of-verifying-age-on-tiktok/"><u>In 2024, Mastering the Process of Verifying Age on TikTok</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/card-absence-alert-visuals-issue/"><u>Card Absence Alert: Visuals Issue</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/downsize-window-space-in-win-10/"><u>Downsize Window Space in WIN 10</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/gpu-shutdown-black-screen/"><u>GPU Shutdown: Black Screen</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-intercept-text-messages-on-vivo-s18e-drfone-by-drfone-virtual-android/"><u>How to Intercept Text Messages on Vivo S18e | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/sharp-focus-quick-cure-for-amd-and-tarkov-bug/"><u>Sharp Focus: Quick Cure for AMD & Tarkov Bug</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/apexs-speedier-setup-game-saved-and-solved/"><u>Apex's Speedier Setup: Game Saved & Solved</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-vpna-fake-gps-location-free-review-on-apple-iphone-6s-drfone-by-drfone-virtual-ios/"><u>A Detailed VPNa Fake GPS Location Free Review On Apple iPhone 6s | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-the-essential-guide-to-creating-cinematic-videos-in-camtasa-for-2024/"><u>[New] The Essential Guide to Creating Cinematic Videos in Camtasa for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-810-plus-no-amd-graphics-software-installed/"><u>Windows 8/10 + No AMD Graphics Software Installed</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/solutions-for-dimming-screen-issue-in-lenovo-pcs/"><u>Solutions for Dimming Screen Issue in Lenovo PCs</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/the-opaque-direct-x-issue-answers-found-solutions-rendered/"><u>The Opaque Direct X Issue: Answers Found, Solutions Rendered</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/win10-screen-distortion-window-not-fullscreen/"><u>Win10 Screen Distortion: Window Not Fullscreen</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/display-failure-detected-no-device/"><u>Display Failure Detected: No Device</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixed-advanced-display-settings-windows-11-missing/"><u>[Fixed] Advanced Display Settings Windows 11 Missing</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/direct3d-incompatibility-eliminated-for-accelerated-gaming/"><u>Direct3D Incompatibility Eliminated for Accelerated Gaming</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/masterclass-in-logo-making-best-of-9-free-software-for-youtubers-for-2024/"><u>Masterclass in Logo-Making  Best of 9 Free Software for YouTubers for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixed-directx-12-renderer-bug/"><u>Fixed DirectX 12 Renderer Bug</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixed-screen-dance-in-windows-11/"><u>[FIXED] Screen Dance in Windows 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-professional-photography-with-canons-complimentary-luts/"><u>[New] Professional Photography with Canon's Complimentary LUTs</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolved-graphics-driver-error-22/"><u>Resolved Graphics Driver Error 22</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/gpu-not-found-need-immediate-fix/"><u>GPU Not Found, Need Immediate Fix</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/dxgkrnlsys-system-freeze-bluescreen-solution/"><u>dxgkrnl.sys System Freeze - BlueScreen Solution</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/screen-serenity-eradicate-flickering-mishaps/"><u>Screen Serenity: Eradicate Flickering Mishaps</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/break-the-blackout-blank-screen-on-twitch/"><u>Break the Blackout Blank Screen on Twitch</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/combating-distorted-ui-design-in-far-cry-6/"><u>Combating Distorted UI Design in Far Cry 6</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/guide-for-fixing-common-windows-11-error-code-c1900101/"><u>Guide for Fixing Common Windows 11 Error Code: C1900101</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/easy-steps-to-reactivate-displayport-outputs/"><u>Easy Steps to Reactivate DisplayPort Outputs</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/essential-youtube-equipment-for-starting-your-channel-what-do-you-really-need-in-2024/"><u>Essential YouTube Equipment For Starting Your Channel - What Do You Really Need, In 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-video-post-production-on-mac-yosemite-best-practices/"><u>2024 Approved Video Post-Production on Mac Yosemite Best Practices</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-discover-the-best-10-free-tiktok-video-editing-apps-for-mac/"><u>[Updated] 2024 Approved  Discover the Best 10 FREE TikTok Video Editing Apps for Mac</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/merging-forces-win10s-success-with-nvidia-graphics/"><u>Merging Forces - Win10's Success with Nvidia Graphics</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-clear-youtube-watch-later-playlist/"><u>[Updated] In 2024, How to Clear YouTube Watch Later Playlist</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/dark-screenside-card-firmware/"><u>Dark Screenside: Card Firmware</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/unleash-joy-with-9-complete-uncut-films-celebrating-christmas-day-online-for-2024/"><u>Unleash Joy with 9 Complete, Uncut Films Celebrating Christmas Day Online for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-quick-climb-up-the-feed-use-of-likes-and-video-content/"><u>[New] Quick Climb Up the Feed  Use of Likes and Video Content</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-cutting-edge-cadence-exclusive-perfected-dj-templates-online/"><u>[New] In 2024, Cutting Edge Cadence  Exclusive, Perfected DJ Templates Online</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-unlock-your-realme-narzo-n55s-potential-the-top-20-lock-screen-apps-you-need-to-try-by-drfone-android/"><u>In 2024, Unlock Your Realme Narzo N55s Potential The Top 20 Lock Screen Apps You Need to Try</u></a></li>
<li><a href="https://android-location.techidaily.com/3-effective-methods-to-fake-gps-location-on-android-for-your-motorola-edge-2023-drfone-by-drfone-virtual/"><u>3 Effective Methods to Fake GPS location on Android For your Motorola Edge 2023 | Dr.fone</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-best-gif-to-avi-converters-online-plus-software-solutions-for-2024/"><u>Updated Best GIF to AVI Converters (Online + Software Solutions) for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/understanding-windows-8s-safety-sequence-how-to-remove-graphics-drivers/"><u>Understanding Windows 8'S Safety Sequence: How to Remove Graphics Drivers</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/completed-resolving-installer-snags/"><u>Completed: Resolving Installer Snags</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/ending-the-screen-dance-in-win11/"><u>Ending the Screen Dance in Win11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-from-start-to-finish-complete-xvideostudioinsight/"><u>In 2024, From Start to Finish  Complete XVideoStudioInsight</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-no-money-just-screen-time-how-to-record-youtube/"><u>In 2024, No Money, Just Screen Time  How To Record YouTube</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/direct3d-compatibility-now-secured-gpu-acceleration-available/"><u>Direct3D Compatibility Now Secured - GPU Acceleration Available</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-online-vertical-video-editing-made-easy-top-picks/"><u>Updated Online Vertical Video Editing Made Easy Top Picks</u></a></li>
</ul></div>
