---
title: "[SOLVED] Twitch Black Screen Issues"
date: 2024-10-08T18:42:45.246Z
updated: 2024-10-11T18:01:43.149Z
tags:
  - win11
  - win10
  - win7
categories:
  - GraphicIssues
description: This Article Describes [SOLVED] Twitch Black Screen Issues
excerpt: This Article Describes [SOLVED] Twitch Black Screen Issues
keywords: Troubleshooting Twitch Black Screen,Fixing Twitch Video Glitches,Resolving Black Screen on Twitch,Overcoming Twitch Playback Errors,Solutions for Twitch Freeze Problems,Addressing Twitch Connection Issues,Remedying Twitch Display Anomalies
thumbnail: https://thmb.techidaily.com/75030bd59360efbfc2946329061573b90f37300b7251c4b711e0f5f10f28322c.jpg
---

## [SOLVED] Twitch Black Screen Issues

 For most avid**Twitch** streamers, one of the most dreaded errors they could bump into is the**black screen** .

 There’s often a combination of causes for this nuisance, but with this guide, you can navigate your way down the list of solutions, until you get to the root of the problem and find the one that works for you.

 If you stream Twitch on a web browser, try**restarting your web browser** and see if it could fix the issue (According to user feedback, the simple fix very likely works).

## Table of contents

* [Fix 1: Restart your network devices](#h-fix-1-restart-your-network-devices)
* [Fix 2: Change your DNS settings](#h-fix-2-change-your-dns-settings)
* [Fix 3: Update your graphics driver](#h-fix-3-update-your-graphics-driver)
* [Fix 4: Clear cache and cookies](#h-fix-4-clear-cache-and-cookies)
* [Fix 5: Disable browser extensions](#h-fix-5-disable-browser-extensions)
* [Fix 6: Switch in or out of hardware acceleration](#h-fix-6-switch-in-or-out-of-hardware-acceleration)
* [Fix 7: Is it a server issue?](#h-fix-7-is-it-a-server-issue)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016165/19272" target="_top" id="2016165">
  <img src="//a.impactradius-go.com/display-ad/19272-2016165" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016165/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Fix 1: Restart your network devices

 Twitch may go black if it loses its connection. Chances are you have a weak internet connection that doesn’t provide enough bandwidth for Twitch to stream properly. So the first thing we should look into is your network devices, which could become overflooded with cache if you have kept them on for too long a while.

 In this fix, you can restart your network devices, allowing them to flush out cached memory and cool off.

Here’s how you go about it:

1. Unplug your modem (and your router, if it’s a separate device) from the power socket.  
![](https://images.drivereasy.com/wp-content/uploads/2021/02/modem.jpg) (a modem)  
![](https://images.drivereasy.com/wp-content/uploads/2021/02/router.png) (a router)
2. Wait **60 seconds**  for your modem (and your router) to cool off.
3. Plug the network devices back in again and wait until the indicator lights are back to the normal state.
4. Restart your computer.
5. Start streaming in Twitch and see if the black screen issue is resolved. If yes, then congrats! If the black screen persists, please try**Fix 2** , below.

 You can test your internet to see if other devices and apps can be connected properly. If the connection is off, then you should contact your ISP for assistance. If the problem doesn’t lie with the router or modem, you can try boosting your connection a bit – moving your modem & router to a more central place in your home, limiting the number of devices connected to your network etc. If your internet is up and running but Twitch gives black screen, then you should move on to**Fix 2** to further narrow down the issue.

### Fix 2: Change your DNS settings

 DNS, or Domain Name System, is like the phonebook of the internet. It is a network component that matches the user-friendly domain names with the numberical format the computer recognizes (IP address). By default, you’re using the DNS server supplied by your ISP as the gateway to the web, but the server may be slow or ill-configured for caching, which effectively slows your internet connection.

 To rule this out as a possible cause, you can change to Google public DNS (8.8.8.8 and 8.8.4.4) to see if it helps with the connection.

1. On your keyboard, press the Windows logo key and R at the same time, then type   **control.exe /name Microsoft.NetworkAndSharingCenter** and press **Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2021/05/、name-Microsoft.NetworkAndSharingCenter-1.png)
2. In the window that pops up, click **Change adapter settings** .  
![](https://images.drivereasy.com/wp-content/uploads/2021/05/Change-adapter-settings-1.png)
3. Right-click on your network adapter, and select **Properties** .  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087253/19272" target="_top" id="2087253">
  <img src="//a.impactradius-go.com/display-ad/19272-2087253" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087253/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2021/05/network-adapter-Properties.png)
4. Click **Internet Protocol Version 4 (TCP/IPv4)** \> **Properties** .  
![](https://images.drivereasy.com/wp-content/uploads/2021/05/Internet-Protocol-Version-4.png)
5. Choose the **Use the following DNS server addresses** option. For **Preferred DNS server** , type **8.8.8.8** ; and for **Alternate DNS server** , type **8.8.4.4** . Click **OK**  to save the changes.  
![](https://images.drivereasy.com/wp-content/uploads/2021/05/8844.png)
6. Close the window.

 Next up, you can run the**ipconfig /flushdns** command for the changes to apply. Here’s how:

1. On your keyboard, press **the Windows Logo Key** and type **cmd** . Then right-click Command Prompt when it comes up as a result and select **Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2021/05/cmd-1.png)
2. When prompted for permission, click **Yes**  to run Command Prompt.
3. Type **ipconfig /flushdns** and press **Enter**  on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2021/05/ip-1.png)
4. Test streaming in Twitch and see if the video is playing properly. If it’s no joy, please move on to**Fix 3** , below.

### Fix 3: Update your graphics driver

 A graphics driver is an essential piece of software program that enables your computer to work with your graphics hardware. If the driver is wrong, corrupt or outdated, you may experience a black screen. So you should update your graphics driver to see if it fixes your problem. If you don’t have the time, patience or skills to update the driver manually, you can do it automatically with [](https://tools.techidaily.com/drivereasy/download/) **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to be troubled by the wrong driver you would be downloading, and you don’t need to worry about making a mistake when installing. **Driver Easy handles it all.**

 You can update your drivers automatically with either the [**FREE**](https://tools.techidaily.com/drivereasy/download/) or the **[Pro versio](https://tools.techidaily.com/drivereasy/download/)** [**n**](https://tools.techidaily.com/drivereasy/download/) of Driver Easy. But with the Pro version it takes just 2 steps (and you get full support and a 30-day money back guarantee):

1. **[Download](https://tools.techidaily.com/drivereasy/download/)** [](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.
2. Run Driver Easy and click the **Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2020/12/last-scan-never.png)
3. Click **Update All** to automatically download and install the correct version of _all_ the drivers that are missing or out of date on your system (this requires the [**Pro version**](https://tools.techidaily.com/drivereasy/download/) – you’ll be prompted to upgrade when you click Update All).  
![](https://images.drivereasy.com/wp-content/uploads/2021/04/5-3.png)  
**Note** : You can do it for free if you like, but it’s partly manual.

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137975/21526" target="_top" id="2137975">
  <img src="//a.impactradius-go.com/display-ad/21526-2137975" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137975/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Restart your computer for the changes to take effect.
5. Open Twitch and check if the black screen issue is solved. If yes, then great. If it still doesn’t cut it, please head on to**Fix 4** , below.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997695/19272" target="_top" id="1997695">
  <img src="//a.impactradius-go.com/display-ad/19272-1997695" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997695/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Fix 4: Clear cache and cookies

 Browsers save files and data so that next time the same information can load up faster. However, overtime, the cached data may have gone wrong, corrupt or outdated, causing the video to not load in Twitch. You can try clearing cache and cookie in your web browser and see how it goes.

**Clear cache and cookies in Google Chrome:**

1. Open Google Chrome.
2. In the top right corner of your screen, click the**three-vertical-dots** icon >**More tools > Clear browsing data…** .  
![](https://images.drivereasy.com/wp-content/uploads/2021/05/cachechrome.png)
3. Click**Clear data** .  
![](https://images.drivereasy.com/wp-content/uploads/2021/05/cleardata.png)
4. Restart Google Chrome.
5. Open Twitch and see if you can play the streaming content properly. If it still doesn’t do the trick, please continue with**Fix 5** , below.

**Clear cache and cookies in** **Firefox:**

1. Open Firefox.
2. Click**the menu button** \>**Options** .  
![](https://images.drivereasy.com/wp-content/uploads/2021/05/2021-05-19_14-31-11.png)
3. In the left panel, choose**Privacy & Security** , then in the right, scroll down to**Cookies and Site data** section and click**Clear Data…** .  
![](https://images.drivereasy.com/wp-content/uploads/2021/05/；rivacy.png)
4. Make sure both boxes for the data items are checked and click**Clear** .  
![](https://images.drivereasy.com/wp-content/uploads/2021/05/clear.png)
5. Click**Clear Now** to confirm.  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136619/26400" target="_top" id="2136619">
  <img src="//a.impactradius-go.com/display-ad/26400-2136619" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136619/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2021/05/now.png)
6. Restart Firefox.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137208/26400" target="_top" id="2137208">
  <img src="//a.impactradius-go.com/display-ad/26400-2137208" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137208/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Open Twitch, and see if you can play the streaming content properly. If it still doesn’t do the trick, please continue with**Fix 5** , below.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134230/18498" target="_top" id="2134230">
  <img src="//a.impactradius-go.com/display-ad/18498-2134230" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134230/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Fix 5: Disable browser extensions

 You may encounter black screen in Twitch because of browser add-on conflict. To rule out this as a possible cause, you can disable all browser extensions and check if Twitch streamly normally – if yes, then you can employ the 50% rule – enabling half of the extensions once at a time to isolate the offender.

 If disabling browser extensions doesn’t help with the situation, please try the next fix, below.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012415/19272" target="_top" id="2012415">
  <img src="//a.impactradius-go.com/display-ad/19272-2012415" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012415/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Fix 6: Switch in or out of hardware acceleration

 Hardware acceleration refers to the process where a software program pass off computing tasks to special hardware, allowing greater efficiency for those graphics-demanding tasks than the software running on the CPU alone

 It may sound contradictory, but for some computers, the feature has fulfilled the purpose of greater performance but for others, turning it off might be better.

 In this fix, you can check whether you have it on or off and switch to the opposite to see if the issue is resolved.

**Enable or disable hardware acceleration in Google Chrome:**

1. Open Google Chrome.
2. Click the three-vertical-dots icon, then select**Settings** .  
![](https://images.drivereasy.com/wp-content/uploads/2021/05/12-3.png)
3. Scroll down to the bottom and click on**Advanced** to expand the advanced settings section.
4. In**System** , switch the toggle for**Use hardware acceleration when available** .  
![](https://images.drivereasy.com/wp-content/uploads/2021/05/2021-05-19_15-11-08.png)
5. Exit Chrome.
6. Launch Chrome, then test if Twitch can stream the content properly. If yes, then great. If it’s still giving black screen, please try**Fix 7** , below.

**Enable or disable hardware acceleration in Firefox:**

1. Open Firefox.
2. Click**the menu button** \>**Options** .  
![](https://images.drivereasy.com/wp-content/uploads/2021/05/2021-05-19_14-31-11.png)
3. In**General** , uncheck the**Use recommended performance settings** box to expand the section, then for the**Use hardware acceleration when available** box, choose the opposite.  
![](https://images.drivereasy.com/wp-content/uploads/2021/05/g.png)
4. Exit Firefox.
5. Launch Firefox, then test if Twitch can stream the content properly. If yes, then great. If it’s still giving black screen, please try**Fix 7** , below.

### Fix 7: Is it a server issue?

 If you’ve exhausted all the fixes above but Twitch is still showing black screen, perhaps it’s time to check the server status for Twitch. It is possibe that the servers have been taken down for performance maintenance or bug patches. If this is indeed the case, then there is not much you can do but wait for the developer staff to do their thing and restore the servers.

---

 That’s the end of this post. Hopefully it has pointed you in the right direction in fixing the black screen in Twitch issue. If you have any questions, ideas or suggestions, you’re more than welcome to leave us a comment below.

* [black screen](https://tools.techidaily.com/drivereasy/download/)
* [Twitch](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://article-knowledge.techidaily.com/new-unraveling-the-mysteries-of-av1-vs-vp9-for-2024/"><u>[New] Unraveling the Mysteries of AV1 Vs. VP9 for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-step-by-step-guide-to-earning-on-reddit-no-skills-required/"><u>2024 Approved Step-by-Step Guide to Earning on Reddit - No Skills Required</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/balancing-win11-resolution-settings/"><u>Balancing Win11 Resolution Settings</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/bring-back-the-colors-lenovos-secret/"><u>Bring Back The Colors: Lenovo's Secret</u></a></li>
<li><a href="https://games-able.techidaily.com/budget-smart-high-fidelity-gaming-monitors-selection/"><u>Budget-Smart, High Fidelity Gaming Monitors Selection</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/enabling-seamless-video-output-via-amd-freesync/"><u>Enabling Seamless Video Output via AMD FreeSync</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/enhanced-display-options-in-windows-11-unlocked/"><u>Enhanced Display Options in Windows 11 Unlocked</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/fix-window-display-lack-of-full-screen-on-monitor-win11/"><u>Fix Window Display: Lack of Full-Screen on Monitor Win11</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-samsung-galaxy-m14-4g-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Samsung Galaxy M14 4G? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-samsung-galaxy-s23plus-by-phone-number-drfone-by-drfone-virtual-android/"><u>How to Track Samsung Galaxy S23+ by Phone Number | Dr.fone</u></a></li>
<li><a href="https://fox-where.techidaily.com/identifying-mobile-surveillance-are-you-being-watched-by-your-own-device/"><u>Identifying Mobile Surveillance: Are You Being Watched by Your Own Device?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-best-tecno-pop-8-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>In 2024, Best Tecno Pop 8 Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-rotated-interface-issue-on-windows-10/"><u>Overcoming Rotated Interface Issue on Windows 10</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/refining-gameplay-dynamics-in-god-of-war/"><u>Refining Gameplay Dynamics in 'God of War'</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/reversing-rear-screen-renders-in-tablets/"><u>Reversing Rear Screen Renders in Tablets</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-trouble-with-trusting-automated-ai-for-intellectual-property-protection/"><u>The Trouble With Trusting Automated AI for Intellectual Property Protection</u></a></li>
<li><a href="https://fox-sys.techidaily.com/ultimate-guide-to-choosing-the-best-disk-imaging-software-for-windows-users-11-10-8-7/"><u>Ultimate Guide to Choosing the Best Disk Imaging Software for Windows Users (11, 10, 8, 7)</u></a></li>
</ul></div>

