---
title: Solving R9 Driver Issues on Windows 10 Platform
date: 2024-08-15T07:21:19.817Z
updated: 2024-08-16T07:21:19.817Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: This Article Describes Solving R9 Driver Issues on Windows 10 Platform
excerpt: This Article Describes Solving R9 Driver Issues on Windows 10 Platform
keywords: Windows 10 Radeon Graphics Fixes,R9 Chipset Troubleshooting Guide,Win10 Driver Update Assistance,AMD GPU R9 Error Resolution,Solving Windows PC Graphics Problems,Optimize Radeon Performance on 10,R9 Driver Compatibility for Windows 10
thumbnail: https://thmb.techidaily.com/4b1d432d185a9307d4c64d844f91526f6a3048c24d149908b382d0c549a92a65.jpg
---

## Solving R9 Driver Issues on Windows 10 Platform

![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_58647de6a91e7.jpg)

AMD Radeon R9 series of graphics card is one of the perfect choices for gamers. Windows 10 users have reported that they are having some problem with their AMD Radeon R9 series of graphics card.  
  
For example, some users reported that the screen would go blank after 5 to 20 minutes into the games and the only thing left to do was to restart. And that the screen flickered when they are playing games and the screen brightness could not be adjusted.
  
In such case, you might need to consider getting your graphics card driver checked and fix any problem it has by yourself.
  
In this post, we will show you exactly how to do it. So, just read along and follow the instructions to get your graphics card back to normal.
  
[**Step one: Run DISM command**](#1)
[**Step two: Run SFC command**](#2)
[**Step three: Clean install AMD Radeon R9 display driver**](#3)
  
Before we proceed with the following resolutions, please make sure that you have done the following things:
  
1) Check to see if you have installed the latest patches and fixes updates provided by Windows.In Windows, most patches and fixes are available through**Windows Update**. It is suggested that you check whether your computer has installed the latest released patches in**Settings > Updates & security.**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/settings-updates-security.jpg)

2) Make sure you have installed the latest version of the Microsoft .Net Framework. For more information as to how to install the latest version of Microsoft .Net Framework, please visit this [**post here**](https://tools.techidaily.com/drivereasy/download/).
  
 **Step one: Run DISM command**
  
 DISM stands for Deployment Image Servicing and Management, which is a tool that helps you scan the integrity of your Windows image.
  
 1) Press**Windows key** and**X** at the same time, then choose**Command Prompt (Run as administrator)** .
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_586482f8af0b5.png)
  
 When prompted with administrator permission, press**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_586483a425d5a.jpg)
  
 2) In the command prompt window, type in the following command:

DISM /Online /Cleanup-Image /RestoreHealth

 Make sure that you have made no typo, and hit**Enter** .
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_58648713723c7.jpg)

 3) You need to wait for a while with patience for the process to finish, especially when it reaches 20%. The operation will finish in a few minutes.  
  
 **Step two: Run SFC command**
  
 SFC stands for system file checker, which is another tool that helps you scan for all protected system files and will replace the corrupted, damaged and/or incorrect versions with correct Microsoft versions.
  
 1) Press**Windows key** and**X** at the same time, then choose**Command Prompt (Run as administrator)** .
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_586482f8af0b5.png)
  
 When prompted with administrator permission, press**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_586483a425d5a.jpg)
  
2) In the command prompt window, type in command:**SFC /SCANNOW**. Make sure that you have made no typo and hit**Enter**.
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_58648e300e3c1.jpg)

3) Wait for a while for the process to finish. If no problem is found here, please move on to the next step.
  
 **Step three: Clean install AMD Radeon R9 display driver**
  
**Note**: Before proceeding with the steps below, it is highly suggested that you **[create a restore point first](https://tools.techidaily.com/drivereasy/download/) .**
  
1) Follow the path:**Start**button**\> Control Panel > Uninstall a program**(View by**Category**).  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_58648e5733e51.jpg)

2) If you are with AMD processors, select**Catalyst Control Center**and choose**Uninstall**.
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_58648f8f4dd21.jpg)
  
 If you are with Intel processors, select to uninstall **ALL** AMD software that you can see in this window.  
  
 3) Press**Windows key** and**X** at the same time, then choose**Device Manager** .

![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_586490d260746.png)

4) Locate**Display adapters**category, then double click the**AMD Radeon R9**series of display driver that you have.
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_5864a9af8c728.jpg)

5) Under**Driver**tab, choose**Uninstall**.
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_5864a9dcb005b.jpg)
  
 Tick the box for**Delete the driver software for this device** option and click**OK** to continue.
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_5864ab747efcd.png)

 6) Reboot your PC.
  
 7) Then**download** the AMD Clean Uninstall Utility from its support website. Then double click the**AMDCleanUtility.exe** icon to run the application.  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_5864ac776f616.png)
  
 Then just follow the instructions on screen to get all your AMD driver and application components removed.  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_5864acd59401a.jpg)
  
 Your computer will restart when the whole process if finished.
  
**Note** : If you already have a trusted application or driver remover, you can use it to do the full uninstall too.
  
 8) When your computer restart again, download the latest version of the AMD Radeon R9 series driver from AMD website and then install it manually.  
  
![](https://images.drivereasy.com/wp-content/uploads/2016/12/img_5864b2625647d.png)

 If you want to save yourself more time and energy for other things, you can leave your driver problems to [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) . It automatically help you detects, downloads and updates device drivers that are missing or outdated on your computer. And, there are only two steps you take to do it:
  
 Step one: press the**Scan Now** button so [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) can help you detect for needed drivers.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58e894bc3e848.png)
  
 Step two: press the**Update** button so [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) can help you download the setup file for the device driver that you need.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/img_58e897add407d.jpg)
  
 If you want to enjoy more features such as driver backup and driver restore, as well as professional tech support waiting to solve your driver problems, you can have a try at the [**professional version of Driver Easy**](https://tools.techidaily.com/drivereasy/download/) . If you are not satisfied with it, you can always ask for a refund thirty days within the purchase. Guaranteed.
  
 What’s with the waiting, come on and have a try at [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) now!

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
<li><a href="https://youtube-blog.techidaily.com/024-approved-transformative-techniques-to-mute-background-noise/"><u>[New] 2024 Approved  Transformative Techniques to Mute Background Noise</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-basicwin10recorder-easy-to-use-software/"><u>[New] BasicWin10Recorder - Easy to Use Software</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-evaluating-streamlabs-vs-competitive-embedders-for-2024/"><u>[New] Evaluating StreamLabs Vs. Competitive Embedders for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-mastering-the-art-of-screen-sharing-in-zoom-for-2024/"><u>[New] Mastering the Art of Screen Sharing in Zoom for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-craft-your-story-aspect-ratios-for-powerful-yt-thumbnails/"><u>[Updated] Craft Your Story  Aspect Ratios for Powerful YT Thumbnails</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-best-hd-video-screen-recorders/"><u>[Updated] In 2024, Best HD Video Screen Recorders</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-navigating-online-public-opinion-for-video-content-concepts/"><u>[Updated] Navigating Online Public Opinion for Video Content Concepts</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-foremost-news-channels-on-youtube-to-watch-daily/"><u>2024 Approved  Foremost News Channels on YouTube to Watch Daily</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-sound-on-call-sensor-iphone-24-tech/"><u>2024 Approved  Sound-on-Call Sensor  IPhone '24 Tech</u></a></li>
<li><a href="https://fox-helps.techidaily.com/5-upgrades-to-shine-your-digital-clips/"><u>5 Upgrades to Shine Your Digital Clips</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1722871038419-a-glimpse-into-the-future-the-2025-samsung-unpacked-showcase-what-to-expect-on-date-and-beyond/"><u>A Glimpse Into the Future: The 2025 Samsung Unpacked Showcase – What to Expect on Date & Beyond!</u></a></li>
<li><a href="https://extra-tips.techidaily.com/a-step-further-in-animation-innovative-techniques-using-movie-maker/"><u>A Step Further in Animation  Innovative Techniques Using Movie Maker</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/correcting-missing-display-options-on-gpu/"><u>Correcting Missing Display Options on GPU</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/deciphering-and-fixing-geforce-experiences-error-0x0003/"><u>Deciphering and Fixing GeForce Experience's Error 0X0003</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/diablo-ii-resurrected-installation-issues-solved/"><u>Diablo II: Resurrected Installation Issues Solved</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/diagnosing-and-repairing-the-recurrent-crashes-in-fuelstation-pro-simulator-for-pc-players/"><u>Diagnosing and Repairing the Recurrent Crashes in FuelStation Pro Simulator for PC Players</u></a></li>
<li><a href="https://fake-location.techidaily.com/does-life360-notify-when-you-log-out-on-honor-play-7t-drfone-by-drfone-virtual-android/"><u>Does Life360 Notify When You Log Out On Honor Play 7T? | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/1721923306768-dont-fall-for-the-google-bard-scam-its-dangerous/"><u>Don't Fall for the Google Bard Scam, It's Dangerous</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/dying-light-audio-malfunction-repaired-step-by-step-solutions/"><u>Dying Light Audio Malfunction Repaired: Step-by-Step Solutions</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/enhance-your-fortnite-experience-by-resolving-stutter-and-buffer-issues-on-desktopslaptops/"><u>Enhance Your Fortnite Experience by Resolving Stutter and Buffer Issues on Desktops/Laptops</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/expert-advice-troubleshoot-your-obs-mic-with-these-top-6-remedies/"><u>Expert Advice: Troubleshoot Your OBS Mic with These Top 6 Remedies</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fixing-silent-airpods-issues-with-bluetooth-on-windows-11-and-10/"><u>Fixing Silent AirPods Issues with Bluetooth on Windows 11 & 10</u></a></li>
<li><a href="https://techidaily.com/hard-reset-tecno-spark-20c-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Tecno Spark 20C in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-can-infinix-hot-40mirror-share-to-pc-drfone-by-drfone-android/"><u>How Can Infinix Hot 40Mirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-zte-nubia-z60-ultra-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>How to Cast ZTE Nubia Z60 Ultra Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/how-to-get-league-of-legends-running-smoothly-again-expert-tips/"><u>How to Get League of Legends Running Smoothly Again – Expert Tips</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/id-lost-naming-intel-icd-with-opengl-support/"><u>ID Lost: Naming Intel ICD with OpenGL Support</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/improving-discord-voice-chat-during-gaming-game-audio-captured-successfully-now/"><u>Improving Discord Voice Chat During Gaming: Game Audio Captured Successfully Now</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-a-step-by-step-guide-to-finding-your-apple-id-on-your-iphone-8-by-drfone-ios/"><u>In 2024, A Step-by-Step Guide to Finding Your Apple ID On Your iPhone 8</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-poco-f5-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Poco F5 5G | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-sony-xperia-1-v-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>In 2024, How to Cast Sony Xperia 1 V Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-fix-apple-iphone-15-pro-passcode-not-working-by-drfone-ios/"><u>In 2024, How to Fix Apple iPhone 15 Pro Passcode not Working?</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/no-graphics-available-during-startup/"><u>No Graphics Available During Startup</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/no-more-freezing-resolve-escape-from-tarkov-pc-game-crashes-now/"><u>No More Freezing: Resolve Escape From Tarkov PC Game Crashes Now!</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-youtubes-greenscreen-mishaps-effectively/"><u>Overcoming YouTube's Greenscreen Mishaps Effectively</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/pc-troubleshooting-guide-deciphering-double-impact-incidents/"><u>PC Troubleshooting Guide: Deciphering Double Impact Incidents</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/perfect-playback-every-time-correcting-your-games-audio-problems-with-these-proven-strategies/"><u>Perfect Playback Every Time: Correcting Your Game's Audio Problems with These Proven Strategies</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/slow-mobile-internet-woes-discover-10-ways-to-boost-your-data-speed/"><u>Slow Mobile Internet Woes: Discover 10 Ways to Boost Your Data Speed</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/solve-your-darkest-dungeon-2-stalling-problems-no-more-pc-freezes/"><u>Solve Your Darkest Dungeon 2 Stalling Problems - No More PC Freezes!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solving-rockalldlldll-absence-in-windows-systems/"><u>Solving 'Rockalldll.dll' Absence in Windows Systems</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/step-by-step-guide-to-restore-windows-11-taskbar-functionality/"><u>Step-by-Step Guide to Restore Windows 11 Taskbar Functionality</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/stop-deathloop-from-crashing-on-your-computer-easy-fixes-revealed/"><u>Stop Deathloop From Crashing on Your Computer - Easy Fixes Revealed!</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/tailor-your-viewing-angle-with-ease/"><u>Tailor Your Viewing Angle with Ease</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/the-elite-selection-best-cordless-computer-mice-for-this-year/"><u>The Elite Selection: Best Cordless Computer Mice for This Year</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/the-ultimate-guide-to-erasing-your-files-forever-with-these-7-techniques/"><u>The Ultimate Guide to Erasing Your Files Forever with These 7 Techniques</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/top-8-artificial-intelligence-mobile-applications-android-and-ios-downloads/"><u>Top 8 Artificial Intelligence Mobile Applications: Android & iOS Downloads</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/ultimate-fixes-for-a-seamless-halo-infinite-gaming-session/"><u>Ultimate Fixes for a Seamless Halo Infinite Gaming Session</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/uniting-forces-nvidia-and-windows-10s-graphical-ally/"><u>Uniting Forces: Nvidia & Windows 10'S Graphical Ally</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/update-troubleshooting-how-to-successfully-refresh-your-minecraft-native-launcher/"><u>Update Troubleshooting - How To Successfully Refresh Your Minecraft Native Launcher</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/video-streaming-problems-on-windows-11-after-upgrade-solved/"><u>Video Streaming Problems on Windows 11 After Upgrade [Solved]</u></a></li>
<li><a href="https://howto.techidaily.com/why-does-my-samsung-galaxy-s23-fe-keep-turning-off-by-itself-6-fixes-are-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Does My Samsung Galaxy S23 FE Keep Turning Off By Itself? 6 Fixes Are Here | Dr.fone</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/1723012843350-winning-at-games-how-to-deal-with-fps-fluctuations-eradicate-hitches-and-increase-overall-gameplay-quality/"><u>Winning at Games: How to Deal with FPS Fluctuations, Eradicate Hitches & Increase Overall Gameplay Quality.</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->