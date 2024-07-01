---
title: "GPU Malfunction Resolved: Screen Responding"
date: 2024-06-30T11:15:01.652Z
updated: 2024-07-01T11:15:01.652Z
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
<li><a href="https://graphic-issues.techidaily.com/resolved-reinstalling-nvidia-software/"><u>Resolved: Reinstalling NVIDIA Software</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/how-i-reconnected-my-laptop-and-tv-with-hdmi/"><u>How I Reconnected My Laptop and TV with HDMI</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/combatting-freezing-while-watching-videos-post-upgrade/"><u>Combatting Freezing While Watching Videos Post-Upgrade</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixed-the-static-on-your-windows-11-display/"><u>[FIXED] The Static on Your Windows 11 Display</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/amd-card-unsupported-on-classic-windows-versions/"><u>AMD Card Unsupported on Classic Windows Versions</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/tiltingscreensolution-steps/"><u>TiltingScreenSolution Steps</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/video-system-repaired-driver-running-well/"><u>Video System Repaired: Driver Running Well</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-insider-knowledge-effortlessly-navigate-the-labyrinth-of-discords/"><u>[Updated] In 2024, Insider Knowledge  Effortlessly Navigate the Labyrinth of Discords</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-a-step-by-step-approach-to-masterful-screen-recordings-on-hp-systems/"><u>[New] In 2024, A Step-by-Step Approach to Masterful Screen Recordings on HP Systems</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/ultimate-blueprint-revolutionizing-your-mobile-capture-experience-with-mobizen/"><u>Ultimate Blueprint  Revolutionizing Your Mobile Capture Experience with Mobizen</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-a-treasure-trove-of-premium-rate-free-luts-revealed/"><u>[New] A Treasure Trove of Premium-Rate Free LUTs Revealed</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-enhancing-mobile-and-desktop-streaming-experience-on-discord/"><u>[Updated] Enhancing Mobile & Desktop Streaming Experience on Discord</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-crafting-timeless-videos-with-historical-flair/"><u>[Updated] In 2024, Crafting Timeless Videos with Historical Flair</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-memetic-magic-mastering-the-top-7-techniques-of-gif-craftsmanship/"><u>[Updated] Memetic Magic  Mastering the Top 7 Techniques of GIF Craftsmanship</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-teach-you-to-transfer-files-from-htc-u23-pro-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways To Teach You To Transfer Files from HTC U23 Pro to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-use-pokemon-go-joystick-on-motorola-moto-e13-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Pokemon Go Joystick on Motorola Moto E13? | Dr.fone</u></a></li>
</ul></div>
