---
title: "Graphic System Patched: Screen Responsive"
date: 2024-09-04T07:09:53.669Z
updated: 2024-09-05T07:09:53.669Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: "This Article Describes Graphic System Patched: Screen Responsive"
excerpt: "This Article Describes Graphic System Patched: Screen Responsive"
keywords: Responsive Display Technology,Graphic System Updates,Screen Adaptability Features,Graphical User Interface Responsiveness,Adaptive Screen Technology,Dynamic Display System Patches,Flexible Screen Technology Updates
thumbnail: https://thmb.techidaily.com/f5fc965758dead74b06c9dd7514fff9b2e384059ddee924706920d8dd594b0c4.jpg
---

## Graphic System Patched: Screen Responsive

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
<li><a href="https://vp-tips.techidaily.com/new-skincare-secrets-for-success/"><u>[New] Skincare Secrets for Success</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-the-complete-guide-to-precision-crafting-in-minecraft-worlds/"><u>[New] The Complete Guide to Precision Crafting in Minecraft Worlds</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-best-quadcopters-for-kids-and-playtime/"><u>[Updated] Best Quadcopters for Kids & Playtime</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-comprehensive-ios-live-photo-handbook/"><u>[Updated] Comprehensive iOS Live Photo Handbook</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-perfect-your-skills-applying-radial-blur-in-photoshop-easily/"><u>[Updated] In 2024, Perfect Your Skills  Applying Radial Blur in Photoshop Easily</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-crafting-your-signature-tone-a-comprehensive-zoom-recording-workshop/"><u>2024 Approved  Crafting Your Signature Tone  A Comprehensive ZOOM Recording Workshop</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-motorola-g54-5g-drfone-by-drfone-virtual-android/"><u>3 Ways to Fake GPS Without Root On Motorola G54 5G | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/amd-radeon-r9-display-driver-issues-on-windows-10-solved/"><u>AMD Radeon R9 Display Driver Issues on Windows 10 [Solved]</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/bypass-game-lag-in-anthem/"><u>Bypass Game Lag in Anthem</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/el-conclusion-mastery-customized-screens-in-focus-for-2024/"><u>Channel Conclusion Mastery  Customized Screens in Focus for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/correcting-ui-glitches-in-civilization-v/"><u>Correcting UI Glitches in Civilization V</u></a></li>
<li><a href="https://location-social.techidaily.com/edit-and-send-fake-location-on-telegram-for-your-gionee-f3-pro-in-3-ways-drfone-by-drfone-virtual-android/"><u>Edit and Send Fake Location on Telegram For your Gionee F3 Pro in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/enabling-intel-driver-on-limited-specs-machine/"><u>Enabling Intel Driver on Limited Specs Machine</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/eradicate-buffer-and-jitter-in-seconds/"><u>Eradicate Buffer and Jitter in Seconds</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/expedite-system-speed-download-geforce-gtx-1060-drivers/"><u>Expedite System Speed: Download GeForce GTX 1060 Drivers</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fix-unsaved-display-configurations-in-win-7-and-10-systems-done/"><u>Fix Unsaved Display Configurations in WIN 7 & 10 Systems [Done]</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixing-displays-surface-pro-7-sync-issues/"><u>Fixing Displays: Surface Pro 7 Sync Issues</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/gfx-init-no-success-detected/"><u>GFX Init: No Success Detected</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/improving-display-contrast-on-lenovo-models/"><u>Improving Display Contrast on Lenovo Models</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-7-top-ways-to-resolve-apple-id-not-active-issue-for-apple-iphone-14-drfone-by-drfone-ios/"><u>In 2024, 7 Top Ways To Resolve Apple ID Not Active Issue For Apple iPhone 14 | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-sim-unlock-realme-gt-neo-5-se-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>In 2024, Sim Unlock Realme GT Neo 5 SE Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/nvidia-gpu-help-focus-on-fixes-not-displays/"><u>NVIDIA GPU Help: Focus on Fixes Not Displays</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-graphical-challenges-overwatch-updates/"><u>Overcoming Graphical Challenges, Overwatch Updates!</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-guide-to-tackle-black-screens-on-windows-11/"><u>Quick-Fix Guide to Tackle Black Screens on Windows 11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/rapidly-revamping-your-computer-driver-cleansing/"><u>Rapidly Revamping Your Computer: Driver Cleansing</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolution-win11-screens-flashing/"><u>Resolution: Win11 Screens Flashing</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/restoring-hdmi-link-between-notebook-and-television/"><u>Restoring HDMI Link Between Notebook & Television</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/revived-infinity-sapphire-probe/"><u>Revived Infinity Sapphire Probe</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/secured-windows-graphic-creation/"><u>Secured Windows Graphic Creation</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/solutions-for-shutdown-screen-failures-in-pcs/"><u>Solutions for Shutdown Screen Failures in PCs</u></a></li>
<li><a href="https://driver-download.techidaily.com/step-by-step-guide-correcting-drivers-issues-for-your-hp-screen-in-microsofts-latest-and-older-os-versions-windows-1187/"><u>Step-by-Step Guide: Correcting Drivers Issues for Your HP Screen in Microsoft's Latest and Older OS Versions (Windows 11/8/7)</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/step-by-step-tutorial-for-finding-old-notifications-in-the-ios-notification-center/"><u>Step-by-Step Tutorial for Finding Old Notifications in the iOS Notification Center</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/stop-flickering-monitors-on-desktops/"><u>Stop Flickering Monitors on Desktops</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/streamline-screen-saving-solutions-for-win-710-problems-solved/"><u>Streamline Screen Saving: Solutions for Win 7/10 Problems [Solved]</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/upgrade-to-high-end-gaming-new-drivers-for-amds-hd-6950-on-windows-10/"><u>Upgrade to High-End Gaming: New Drivers for AMD's HD 6950 on Windows 10</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/win11-rebirth-bright-screen-after-update-fallout/"><u>Win11 Rebirth: Bright Screen After Update Fallout</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-10-overcoming-challenges-with-dual-graphics-cards/"><u>Windows 10: Overcoming Challenges with Dual Graphics Cards</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/zero-display-fresh-pcie/"><u>Zero Display, Fresh PCIe</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1304647">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1304647.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1304647">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1304647.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1304647%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1304647/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->