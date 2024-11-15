---
title: "Graphic System Patched: Screen Responsive"
date: 2024-11-06T19:19:59.099Z
updated: 2024-11-13T22:57:03.029Z
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
<li><a href="https://some-techniques.techidaily.com/updated-expert-tips-for-sharing-videos-the-ultimate-youtube-photo-poster/"><u>[Updated] Expert Tips for Sharing Videos The Ultimate YouTube Photo Poster</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-chuckle-chronicles-hilarious-meme-crafting-simplified/"><u>2024 Approved Chuckle Chronicles Hilarious Meme Crafting Simplified</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/adjusting-display-edges-vertically/"><u>Adjusting Display Edges Vertically</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/amds-quick-escape-tarkov-glitch-resolution/"><u>AMD's Quick Escape: Tarkov Glitch Resolution</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/avoiding-rtx-3080-game-aborts/"><u>Avoiding RTX 3080 Game Aborts</u></a></li>
<li><a href="https://vp-tips.techidaily.com/convertir-mxf-a-avi-en-linea-gratuito-mediante-movavi-sin-gastos-solo-resultados/"><u>Convertir MXF a AVI En Línea Gratuito Mediante Movavi - Sin Gastos, Sólo Resultados</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-samsung-galaxy-a23-5g-by-phone-number-drfone-by-drfone-virtual-android/"><u>How to Track Samsung Galaxy A23 5G by Phone Number | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-forgotten-the-voicemail-password-of-samsung-galaxy-a14-5g-try-these-fixes-by-drfone-android/"><u>In 2024, Forgotten The Voicemail Password Of Samsung Galaxy A14 5G? Try These Fixes</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-simplifycast-the-ultimate-guide-to-starting-your-podcast-livestream/"><u>In 2024, SimplifyCast The Ultimate Guide to Starting Your Podcast Livestream</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-the-best-methods-to-unlock-the-iphone-locked-to-owner-for-iphone-xs-max-drfone-by-drfone-ios/"><u>In 2024, The Best Methods to Unlock the iPhone Locked to Owner for iPhone XS Max | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/push-boundaries-new-drivers-elevate-amds-hd-6950/"><u>Push Boundaries - New Drivers Elevate AMD's HD 6950</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/restore-normal-screen-orientation-for-windows-10/"><u>Restore Normal Screen Orientation for Windows 10</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/screen-size-control-achieved-in-new-version-of-windows-11/"><u>Screen Size Control Achieved in New Version of Windows 11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/smooth-gaming-experience-with-rtx-3080/"><u>Smooth Gaming Experience with RTX 3080</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-next-level-windows-experience/"><u>The Next-Level Windows Experience</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-free-up-space-how-to-convert-your-dvds-to-digital-video-files/"><u>Updated 2024 Approved Free Up Space How to Convert Your DVDs to Digital Video Files</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959759/19272" target="_top" id="1959759">
  <img src="//a.impactradius-go.com/display-ad/19272-1959759" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959759/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

