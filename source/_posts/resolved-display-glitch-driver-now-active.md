---
title: "Resolved Display Glitch: Driver Now Active"
date: 2024-09-04T07:08:08.398Z
updated: 2024-09-05T07:08:08.398Z
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
<li><a href="https://graphic-issues.techidaily.com/corrected-drivers-display-system-back-to-normal/"><u>[Corrected] Drivers: Display System Back to Normal</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fix-directx12-setback-for-launch-of-halo-infinite/"><u>[FIX] DirectX12 Setback for Launch of Halo Infinite</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/solved-dxgkrnlsys-blue-screen-of-death-on-windows/"><u>[Solved] dxgkrnl.sys Blue Screen of Death on Windows</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-easy-peasy-guide-to-crafting-and-tweaking-multiple-snaps-in-snapchat-for-2024/"><u>[Updated] Easy-Peasy Guide to Crafting and Tweaking Multiple Snaps in Snapchat for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-game-recorder-mastery-top-5-techniques-for-windows-11-for-2024/"><u>[Updated] Game Recorder Mastery  Top 5 Techniques for Windows 11 for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-free-and-easy-building-attractive-youtube-intros-without-expense/"><u>[Updated] In 2024, Free & Easy  Building Attractive YouTube Intros without Expense</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-enhance-audio-visual-fidelity-use-av1-on-youtube/"><u>2024 Approved  Enhance Audio-Visual Fidelity  Use AV1 on YouTube</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/accelerate-gaming-and-workflow-with-updated-intelligent-graphic-drivers/"><u>Accelerate Gaming & Workflow with Updated Intelligent Graphic Drivers</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/comprehensive-guide-to-nvidia-screener-use/"><u>Comprehensive Guide to NVIDIA Screener Use</u></a></li>
<li><a href="https://solve-latest.techidaily.com/comprendre-lelectronique-facturation-un-guide-essentiel-pour-les-comptes-fournisseurs-software-de-labbyy/"><u>Comprendre L'électronique Facturation: Un Guide Essentiel Pour Les Comptes Fournisseurs - Software De L'ABBYY</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/corrective-measures-applied-to-winos-comexceptions/"><u>Corrective Measures Applied to WinOS COMExceptions</u></a></li>
<li><a href="https://sound-issues.techidaily.com/corsair-hs35-headset-mic-wont-work-on-windows-diagnosis-and-fixes/"><u>Corsair HS35 Headset Mic Won't Work on Windows: Diagnosis and Fixes</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/cursor-alone-in-windows-10/"><u>Cursor Alone in Windows 10</u></a></li>
<li><a href="https://technical-tips.techidaily.com/deciphering-ray-tracing-the-future-of-realistic-graphics/"><u>Deciphering Ray Tracing: The Future of Realistic Graphics?</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/display-malfunction-no-detected-card/"><u>Display Malfunction: No Detected Card</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/drivers-reset-nvidia-display-now-functional/"><u>Drivers Reset: Nvidia Display Now Functional</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/enhanced-video-performance-after-win11-update/"><u>Enhanced Video Performance After Win11 Update</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/expertise-applied-to-solve-comexception-window-errors/"><u>Expertise Applied to Solve COMException Window Errors</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/glitch-overcome-visuals-preserved-and-stable/"><u>Glitch Overcome: Visuals Preserved and Stable</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/1719818203494-gpu-glitch-spotlight-now-resolved/"><u>GPU Glitch Spotlight - Now Resolved!</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/gpu-issues-resolved-on-new-laptop-win11-version/"><u>GPU Issues Resolved on New Laptop Win11 Version</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/mastering-the-might-in-god-of-war/"><u>Mastering the Might in 'God of War'</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/narrative-enrichment-integrating-chatgpt-and-creative-ai-tools-in-dungeons-and-dragons/"><u>Narrative Enrichment: Integrating ChatGPT & Creative AI Tools in Dungeons & Dragons</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/navigating-minimum-system-criteria-for-gpu/"><u>Navigating Minimum System Criteria for GPU</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/opengl-error-flagged-by-tdr-now-safe-with-nvidia/"><u>OpenGL Error Flagged by TDR — Now Safe with NVIDIA</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overturn-pc-monitoring-in-win7/"><u>Overturn PC Monitoring in Win7</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/quick-cure-rectify-distorted-laptop-borders/"><u>Quick Cure: Rectify Distorted Laptop Borders</u></a></li>
<li><a href="https://driver-download.techidaily.com/quick-guide-installing-amd-ryzen-5-2600-graphics-drivers-step-by-step/"><u>Quick Guide: Installing AMD Ryzen 5 2600 Graphics Drivers - Step by Step</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/reinforcing-surface-pro-7s-visual-fortitude/"><u>Reinforcing Surface Pro 7'S Visual Fortitude</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/securing-a-smooth-display-in-win11/"><u>Securing a Smooth Display in Win11</u></a></li>
<li><a href="https://tech-haven.techidaily.com/solve-your-displays-issues-when-nvidia-output-is-missing/"><u>Solve Your Displays Issues When Nvidia Output Is Missing</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/solving-r9-driver-issues-on-windows-10-platform/"><u>Solving R9 Driver Issues on Windows 10 Platform</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/solving-win10-resolution-errors/"><u>Solving Win10 Resolution Errors</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/tackling-interruptions-in-win11s-live-streaming/"><u>Tackling Interruptions in Win11's Live Streaming</u></a></li>
<li><a href="https://extra-tips.techidaily.com/vlc-media-player-your-free-windows-substitute/"><u>VLC Media Player  Your Free Windows Substitute</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068440/7443" target="_top" id="2068440">
  <img src="//a.impactradius-go.com/display-ad/7443-2068440" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068440/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->