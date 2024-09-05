---
title: "Monitor Malfunction Rectified: Driver Running"
date: 2024-09-04T07:05:44.961Z
updated: 2024-09-05T07:05:44.961Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: "This Article Describes Monitor Malfunction Rectified: Driver Running"
excerpt: "This Article Describes Monitor Malfunction Rectified: Driver Running"
keywords: Malfunctioning Device Repair,Computer System Diagnostics,Automotive Computer Repair Services,Faulty Hardware Troubleshooting,Software Glitch Resolution,Computer Boot Problems,Driver Error Fixes
thumbnail: https://thmb.techidaily.com/b458df85a4bb141857a3c4d2de6e35b07f50e405e5e03af8173f938324bb194b.png
---

## Monitor Malfunction Rectified: Driver Running

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
<li><a href="https://youtube-zero.techidaily.com/024-approved-capturing-moving-images-mirrorless-versus-dslr/"><u>[New] 2024 Approved  Capturing Moving Images  Mirrorless Versus DSLR</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-snap-into-style-expert-tips-to-outshine-the-competition/"><u>[New] 2024 Approved  Snap Into Style  Expert Tips to Outshine the Competition</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-creating-immersive-iphone-video-content/"><u>[New] In 2024, Creating Immersive iPhone Video Content</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-how-to-keep-your-audience-engaged-top-6-strategies-for-higher-youtube-stickiness/"><u>[New] In 2024, How To Keep Your Audience Engaged  Top 6 Strategies for Higher YouTube Stickiness</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-fleeting-films-on-the-friendly-social/"><u>[Updated] 2024 Approved  Fleeting Films on the Friendly Social</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-cutting-edge-identifying-the-best-10-free-online-art-schools-on-youtube-for-2024/"><u>[Updated] Cutting Edge  Identifying the Best 10 Free Online Art Schools on YouTube for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-capturing-clarity-the-essential-list-of-macos-recorders/"><u>[Updated] In 2024, Capturing Clarity  The Essential List of macOS Recorders</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-the-essential-guide-for-diy-gif-makers-youtube-to-visual-storytelling/"><u>[Updated] The Essential Guide for DIY GIF Makers  YouTube to Visual Storytelling</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-hidden-history-unveiled-understanding-off-facebook-data/"><u>2024 Approved  Hidden History Unveiled  Understanding Off-Facebook Data</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-masterclass-in-instagram-designing-eye-catching-cover-images/"><u>2024 Approved  Masterclass in Instagram  Designing Eye-Catching Cover Images</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/4-quick-ways-to-transfer-contacts-from-apple-iphone-6s-plus-to-iphone-withwithout-itunes-drfone-by-drfone-transfer-from-ios/"><u>4 Quick Ways to Transfer Contacts from Apple iPhone 6s Plus to iPhone With/Without iTunes | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/amd-radeon-hd-6950-graphics-drivers-update-on-windows-10/"><u>AMD Radeon HD 6950 Graphics Drivers Update on Windows 10</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/1719818172681-amds-graphics-evolution-upgraded-hd-6950-windows-10-driver/"><u>AMD's Graphics Evolution: Upgraded HD 6950 Windows 10 Driver!</u></a></li>
<li><a href="https://driver-install.techidaily.com/boost-operational-speed-os-revitalization-via-mf4770n-driver-update/"><u>Boost Operational Speed: OS Revitalization via MF4770n Driver Update</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/boosting-performance-fixes-for-unsupported-freesync/"><u>Boosting Performance: Fixes for Unsupported FreeSync</u></a></li>
<li><a href="https://unlock-android.techidaily.com/chatbot-tricks-how-to-tell-them-apart/"><u>ChatBot Tricks: How to Tell Them Apart</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/decrease-windows-display-in-win-10-system/"><u>Decrease Windows Display in WIN 10 System</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/dell-laptop-screen-stability-achieved-after-fix/"><u>Dell Laptop Screen Stability Achieved After Fix</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/effortless-ending-of-graphics-cards-in-windows/"><u>Effortless Ending of Graphics Cards in Windows</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/enabled-win-graphics-functionality/"><u>Enabled Win Graphics Functionality</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/eradicate-windows-11-display-glitches/"><u>Eradicate Windows 11 Display Glitches</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/1719817948147-fix-laptop-screen-wont-turn-on-issue/"><u>Fix Laptop Screen Won’t Turn On Issue</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixing-aspect-ratio-error-on-wide-windows-10-displays/"><u>Fixing Aspect Ratio Error on Wide Windows 10 Displays</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-oneplus-ace-2-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on OnePlus Ace 2 Pro | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/geforce-7025-no-more-win11-issues/"><u>GeForce 7025, No More Win11 Issues</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/gfxui-win-troubleshoot-complete-functioning-normally/"><u>GFXUI Win Troubleshoot Complete, Functioning Normally</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/ghostly-gtx-displayed-by-device-hub/"><u>Ghostly GTX Displayed by Device Hub</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/graphics-processor-error-overcome-system-safe/"><u>Graphics Processor Error Overcome, System Safe</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/how-to-fix-lenovo-laptop-screen-dim-issue/"><u>How to Fix Lenovo Laptop Screen Dim Issue</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-screen-to-realme-gt-neo-5-se-phones-drfone-by-drfone-android/"><u>How to Mirror PC Screen to Realme GT Neo 5 SE Phones? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-call-logs-from-infinix-hot-30i-by-fonelab-android-recover-call-logs/"><u>How to rescue lost call logs from Infinix Hot 30i</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-disabled-iphone-13-mini-how-to-unlock-a-disabled-iphone-13-mini-by-drfone-ios/"><u>In 2024, Disabled iPhone 13 mini How to Unlock a Disabled iPhone 13 mini?</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-realme-v30-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Realme V30? | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/invisible-screen-post-firmware/"><u>Invisible Screen Post-Firmware</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/kernel-conflict-addressed-error-22/"><u>Kernel Conflict Addressed: Error 22</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/laptop-display-normalized-flickering-no-more/"><u>Laptop Display Normalized: Flickering No More</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/mending-disconnected-laptop-and-tv-via-hdmi/"><u>Mending Disconnected Laptop and TV via HDMI</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-in-2024-the-ultimate-fcpx-freebie-list-10-best-plugins/"><u>New In 2024, The Ultimate FCPX Freebie List 10 Best Plugins</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/new-laptop-gpu-works-smoothly-on-win11-os/"><u>New Laptop GPU Works Smoothly on Win11 OS</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/1719818243705-no-more-laptop-screen-flickers-problem-solved/"><u>No More Laptop Screen Flickers, Problem Solved!</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcome-installation-obstacle-for-nvidia-driver/"><u>Overcome Installation Obstacle for Nvidia Driver</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-google-frp-lock-on-11-proplus-by-drfone-android-unlock-remove-google-frp/"><u>Remove Google FRP lock on 11 Pro+</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/repaired-amd-driver-functionality-on-win10/"><u>Repaired AMD Driver Functionality on Win10</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/resolving-gpu-fan-stillness-issues/"><u>Resolving GPU Fan Stillness Issues</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/reversing-high-dpi-lockup-windows-11s-fix/"><u>Reversing High-DPI Lockup: Windows 11'S Fix</u></a></li>
<li><a href="https://data-recovery.techidaily.com/revitalize-missing-data-now-unmatched-recovery-rate-at-hand/"><u>Revitalize Missing Data Now! Unmatched Recovery Rate at Hand</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/right-orientation-fix-in-win7-mode/"><u>Right Orientation Fix in Win7 Mode</u></a></li>
<li><a href="https://extra-skills.techidaily.com/social-network-video-download-for-audio-conversion-for-2024/"><u>Social Network Video Download for Audio Conversion for 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/speedy-driver-update-intel-graphics-3000-win11-style/"><u>Speedy Driver Update - Intel Graphics 3000, Win11 Style</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/strategies-to-overcome-youtubes-bluish-background-blues/"><u>Strategies to Overcome YouTube's Bluish Background Blues</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/1719818132567-streaming-on-windows-10-after-upgrade-secured/"><u>Streaming on Windows 10 After Upgrade Secured!</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/successful-resolution-of-graphics-switching-problem/"><u>Successful Resolution of Graphics Switching Problem</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/swift-victory-in-apex-game-overhaul-complete/"><u>Swift Victory in Apex: Game Overhaul Complete!</u></a></li>
<li><a href="https://android-unlock.techidaily.com/the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-asus-rog-phone-7-ultimate-device-by-drfone-android/"><u>The Ultimate Guide How to Bypass Swipe Screen to Unlock on Asus ROG Phone 7 Ultimate Device</u></a></li>
<li><a href="https://win-dash.techidaily.com/the-ultimate-tutorial-on-installing-the-latest-logitech-m310-drivers/"><u>The Ultimate Tutorial on Installing the Latest Logitech M310 Drivers</u></a></li>
<li><a href="https://buynow-help.techidaily.com/tp-link-tl-wr902ac-ac750-travel-router-review/"><u>TP-Link TL-WR902AC AC750 Travel Router Review</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/troubleshooting-flashing-lcd-on-hp-systems/"><u>Troubleshooting Flashing LCD on HP Systems</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/uncovering-brightness-from-black-on-lenovo/"><u>Uncovering Brightness From Black on Lenovo</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/unsaved-settings-no-more-display-fixed/"><u>Unsaved Settings No More: Display Fixed</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/upgrade-to-advanced-gpu-software-for-gtx-1060/"><u>Upgrade to Advanced GPU Software for GTX 1060</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/what-is-4k-resolution/"><u>What Is 4K Resolution</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-pokemon-evolve-with-a-dawn-stone-for-tecno-spark-go-2024-drfone-by-drfone-virtual-android/"><u>What Pokémon Evolve with A Dawn Stone For Tecno Spark Go (2024)? | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/which-pokemon-can-evolve-with-a-moon-stone-for-honor-v-purse-drfone-by-drfone-virtual-android/"><u>Which Pokémon can Evolve with a Moon Stone For Honor V Purse? | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/win10-screen-size-set-rightly/"><u>Win10 Screen Size Set Rightly</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/win7-visual-orientation-tweaks/"><u>Win7 Visual Orientation Tweaks</u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-10-update-stuck-or-frozen-how-do-i-fix-it/"><u>Windows 10 Update Stuck or Frozen - How Do I Fix It?</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105860/7443" target="_top" id="2105860">
  <img src="//a.impactradius-go.com/display-ad/7443-2105860" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105860/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->