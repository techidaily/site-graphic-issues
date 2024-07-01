---
title: "Video System Repaired: Driver Running Well"
date: 2024-06-30T11:14:50.658Z
updated: 2024-07-01T11:14:50.658Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: "This Article Describes Video System Repaired: Driver Running Well"
excerpt: "This Article Describes Video System Repaired: Driver Running Well"
keywords: Repaired Video Systems,Driver Performance Testing,Vehicle Audio System Repair,Video System Diagnostics,Professional Video System Fixes,Enhanced Vehicle Sound Quality,Expert Video System Repairs
thumbnail: https://thmb.techidaily.com/9768937f48cf302572d982e26e42ee65fe0cea8c30a424b4cbbdbad231eaae46.png
---

## Video System Repaired: Driver Running Well

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
<li><a href="https://graphic-issues.techidaily.com/diagnosing-dark-display-distress-on-tablets/"><u>Diagnosing Dark Display Distress on Tablets</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/seamlessly-adjust-screen-a-few-easy-steps/"><u>Seamlessly Adjust Screen: A Few Easy Steps</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/rectified-aspect-ratio-for-sideways-tablet-view/"><u>Rectified Aspect Ratio for Sideways Tablet View</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/banish-blinding-flashes-windows-7s-secret-weapon/"><u>Banish Blinding Flashes: Windows 7'S Secret Weapon</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/effortless-switching-of-graphics-cards-on-win10-via-nvidia-and-intel/"><u>Effortless Switching of Graphics Cards on Win10 via NVIDIA & Intel</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/rapid-reinstatement-of-apexs-perfection/"><u>Rapid Reinstatement of Apex's Perfection</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/windows-10-upgrade-enhanced-nvidia-geforce-driver-release/"><u>Windows 10 Upgrade: Enhanced NVIDIA GeForce Driver Release</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/unlocking-system-safety-access-to-safe-mode-and-gpu-driver-removal-guide/"><u>Unlocking System Safety: Access to Safe Mode & GPU Driver Removal Guide</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-harmonious-hush-for-restfulness-top-asmr-picks/"><u>In 2024, Harmonious Hush for Restfulness  Top ASMR Picks</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-sparking-interest-in-tiktoks-best-50plus-motivational-quotes/"><u>[New] Sparking Interest in TikToks  Best 50+ Motivational Quotes</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-best-pokemons-for-pvp-matches-in-pokemon-go-for-motorola-g24-power-drfone-by-drfone-virtual-android/"><u>In 2024, Best Pokemons for PVP Matches in Pokemon Go For Motorola G24 Power | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-essential-history-vids-student-edition-of-top-10-lists/"><u>2024 Approved  Essential History Vids  Student Edition of Top 10 Lists</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/2024-approved-unleash-your-creativity-top-10-imovie-alternative-apps-for-android/"><u>2024 Approved Unleash Your Creativity Top 10 iMovie Alternative Apps for Android</u></a></li>
<li><a href="https://fix-guide.techidaily.com/quick-fixes-for-why-is-my-poco-m6-pro-4g-black-and-white-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Quick Fixes for Why Is My Poco M6 Pro 4G Black and White | Dr.fone</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-gaming-intro-makers-compared-top-10-free-and-paid-options/"><u>New In 2024, Gaming Intro Makers Compared Top 10 Free and Paid Options</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-ethical-implications-recording-whatsapp-calls-responsibly-for-2024/"><u>[Updated] Ethical Implications  Recording WhatsApp Calls Responsibly for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-highlighting-the-leading-10-shadowy-story-viewers/"><u>[New] 2024 Approved  Highlighting the Leading 10 Shadowy Story Viewers</u></a></li>
</ul></div>
