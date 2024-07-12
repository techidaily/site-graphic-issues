---
title: "Graphic System Patched: Screen Responsive"
date: 2024-07-11T18:00:48.063Z
updated: 2024-07-12T18:00:48.063Z
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
<li><a href="https://graphic-issues.techidaily.com/initial-graphical-system-unresponsive/"><u>Initial Graphical System Unresponsive</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-d3d-initialization-setbacks/"><u>Overcoming D3D Initialization Setbacks</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-unilateral-earbud-error-how-to-rectify/"><u>In 2024, Unilateral Earbud Error  How to Rectify</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/mend-displays-settings-saving-woes-windows-7-10-tips-tackled/"><u>Mend Displays Settings Saving Woes: Windows 7-10 Tips [Tackled]</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-remove-or-bypass-knox-enrollment-service-on-poco-x5-by-drfone-android/"><u>In 2024, How To Remove or Bypass Knox Enrollment Service On Poco X5</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/troubleshoot-anthem-delays/"><u>Troubleshoot Anthem Delays</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/directx12-malfunction-thwarts-new-halo-infinite-play/"><u>DirectX12 Malfunction Thwarts New Halo Infinite Play</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolved-entry-to-control-panel-achieved/"><u>[Resolved] Entry to Control Panel Achieved</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-how-to-blur-a-part-of-a-picture-on-pcmobile/"><u>[New] How to Blur a Part of a Picture on PC/Mobile</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/effortless-repair-processes-screen-absent/"><u>Effortless Repair Processes, Screen Absent</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/revive-dead-asus-integrated-camera/"><u>Revive Dead Asus Integrated Camera</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolving-flickering-phenomenon-on-pro-7/"><u>Resolving Flickering Phenomenon on Pro 7</u></a></li>
<li><a href="https://win11-tips.techidaily.com/clearing-up-empty-directory-mistake-code-0x80070091-guide/"><u>Clearing Up Empty Directory Mistake: Code 0X80070091 Guide</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/no-blur-windows-display-enhanced/"><u>No Blur: Windows Display Enhanced</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/guide-on-how-to-change-your-apple-id-email-address-on-iphone-xs-max-by-drfone-ios/"><u>Guide on How To Change Your Apple ID Email Address On iPhone XS Max</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/monitor-turns-dark-with-new-driver/"><u>Monitor Turns Dark with New Driver</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fully-functional-laptop-gpu-in-windows-11/"><u>Fully Functional: Laptop GPU in Windows 11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/rectified-screen-initialization-error/"><u>Rectified Screen Initialization Error</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/connectivity-crusade-easily-fix-screen-disconnect/"><u>Connectivity Crusade: Easily Fix Screen Disconnect</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/wnddevice-creation-now-smooth/"><u>WndDevice Creation Now Smooth</u></a></li>
<li><a href="https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-vivo-y28-5g-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Unfortunately Settings Has Stopped on Vivo Y28 5G Quickly | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/ease-of-use-solve-fallout-4s-pc-freezing-problems/"><u>Ease of Use: Solve Fallout 4'S PC Freezing Problems</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-sharpness-achievement/"><u>Windows Sharpness Achievement</u></a></li>
<li><a href="https://printer-issues.techidaily.com/steps-to-reconnect-offline-brother-printer/"><u>Steps to Reconnect Offline Brother Printer</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/win11-adjust-display-dimensions/"><u>Win11: Adjust Display Dimensions</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/1719817576948-gpu-non-detection-seek-immediate-assistance/"><u>GPU Non-Detection, Seek Immediate Assistance!</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/nvidia-blackout-mystery/"><u>NVIDIA Blackout Mystery</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-top-5-best-terraria-map-viewers-to-find-treasure/"><u>[Updated] 2024 Approved  Top 5 Best Terraria Map Viewers to Find Treasure</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/graphics-cut-off-new-gpu/"><u>Graphics Cut-Off - New GPU?</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/revise-win10-resolution-norms/"><u>Revise Win10 Resolution Norms</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/new-graphics-card-no-sight/"><u>New Graphics Card No Sight</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/optimal-lateral-laptop-view-achieved/"><u>Optimal Lateral Laptop View Achieved</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixing-windows-cominterface-issue-with-precision/"><u>Fixing Windows COMInterface Issue with Precision</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-essential-strategies-for-memorable-youtube-closings-for-2024/"><u>[Updated] Essential Strategies for Memorable YouTube Closings for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/crisp-windows-image-resolution/"><u>Crisp Windows Image Resolution</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/unlock-secure-operations-methodology-for-safe-mode-access-gpu-cleanup-on-win8/"><u>Unlock Secure Operations: Methodology for Safe Mode Access, GPU Cleanup on WIN8</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/no-visibility-after-driver-update/"><u>No Visibility After Driver Update</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resetting-display-configuration-for-nvidia-gpu/"><u>Resetting Display Configuration for NVidia GPU</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-miui-screen-recorder-review-and-alternatives/"><u>[New] MIUI Screen Recorder Review and Alternatives</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-stuck-on-downloading-of-xiaomi-redmi-note-12-5g-7-ways-to-resolve-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Stuck on Downloading Of Xiaomi Redmi Note 12 5G? 7 Ways to Resolve | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/correct-image-rotation-windows-7-guide/"><u>Correct Image Rotation: Windows 7 Guide</u></a></li>
<li><a href="https://android-frp.techidaily.com/the-complete-guide-to-oppo-find-x6-pro-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>The Complete Guide to Oppo Find X6 Pro FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/drive-upgrade-nvidias-new-geforce-210-version/"><u>Drive Upgrade: NVIDIA's New GeForce 210 Version</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-11-nvidia-driver-issue-settled/"><u>Windows 11, NVidia Driver Issue Settled</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/upend-pc-monitor-for-win7/"><u>Upend PC Monitor for Win7</u></a></li>
</ul></div>
