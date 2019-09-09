---
title: Stream Movies to your Android with Tversity
date: 2010-11-30T00:51:46+00:00
author: BooyaTRJ
excerpt: "This tutorial will cover how to stream your personal video library to your Android device using TVersity."
layout: post
permalink: /2010/11/stream-movies-to-your-android-with-tversity.html
post_thumbnail_loc: /wp-content/uploads/2010/11/Android-Tversity-Logo-Booya-Gadget-thumb.jpg
categories:
  - Android
  - TVersity

tags:
  - Android
  - Streaming Video
  - T-Mobile
  - tvercity
  - Tversity
  - Verizon Wireless
---
**What you'll need for this Booya:**

* A PC running TVersity  
* An Android Device  
* [Handbrake Software](https://handbrake.fr/downloads.php){:target="_blank"}  
* [nswPlayer](https://play.google.com/store/apps/details?id=com.nsw.android.mediaexplorer&hl=en){:target="_blank"}    
* A Digital Video File

Watch our video or read below to see [Android streaming via TVersity in action.](https://www.youtube.com/watch?v=UJ5Cr2wKXVA){:target="_blank"}
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJ5Cr2wKXVA" frameborder="0" allowfullscreen></iframe>

**Step #1: Converting your Movie for Progressive Streaming**

Once you have installed Handbrake on your PC it is time to convert your digital file for streaming.  Open the Options Menu and set the default output folder to your TVersity Shared Folder.  Use the Iphone Legacy settings in Handbrake to create your file.
<figure>
	<a href="{{ site.cdn-url }}/wp-content/uploads/2010/11/Handbrake-Iphone-Legacy-Screen-Shot.jpg">
    <img src="{{ site.cdn-url }}/wp-content/uploads/2010/11/Handbrake-Iphone-Legacy-Screen-Shot-640.jpg" 
         alt="Handbrake Iphone Legacy Screen Shot Booya Gadget" title="Handbrake Iphone Legacy Screen Shot"></a>
	<figcaption>Handbrake Iphone Legacy Screen Shot</figcaption>
</figure>

Here is where you have to make your decision on compression.  Booya sets the Video Width at 480 and then selects the button to "Keep Aspect Ratio".  The reason for this is that when the file is complete it will not only stream to your Android, but it will be playable by your PSP.
<figure>
	<a href="{{ site.cdn-url }}/wp-content/uploads/2010/11/Handbrake-Keep-Aspect-Ratio-4801.jpg">
    <img src="{{ site.cdn-url }}/wp-content/uploads/2010/11/Handbrake-Keep-Aspect-Ratio-4801-640.jpg" 
         alt="Handbrake Keep Aspect Ratio 480 Booya Gadget" title="Handbrake Keep Aspect Ratio 480"></a>
	<figcaption>Handbrake Keep Aspect Ratio 480</figcaption>
</figure>

Before you begin your conversion you must check the "Web Optimized" button.  This makes your .mp4 a progressive file that can be streamed.
<figure>
	<a href="{{ site.cdn-url }}/wp-content/uploads/2010/11/Handbrake-Web-Optimized.jpg">
    <img src="{{ site.cdn-url }}/wp-content/uploads/2010/11/Handbrake-Web-Optimized-640.jpg" 
         alt="Handbrake Web Optimized booya Gadget" title="Handbrake Web Optimized"></a>
	<figcaption>Handbrake Web Optimized</figcaption>
</figure>

Select the Video tab and we can now adjust the quality of the file.  Booya sets the Average Bitrate between 384 and 512 so that we can get a file that is still of decent quality, but not too large for streaming over 3G.
<figure>
	<a href="{{ site.cdn-url }}/wp-content/uploads/2010/11/Handbrake-Average-Bitrate-512.jpg">
    <img src="{{ site.cdn-url }}/wp-content/uploads/2010/11/Handbrake-Average-Bitrate-512-640.jpg" 
         alt="Handbrake Average Bitrate 512 booya gadget" title="Handbrake Average Bitrate 512"></a>
	<figcaption>Handbrake Average Bitrate 512</figcaption>
</figure>
Hit Start to get your conversion going, conversion times will vary depending on the power of your PC.

**Step #2: Setting up TVersity for Streaming**

Under the Setting Tab in TVersity you will find the Transcode Settings.  Make sure that "When To Transcode" is set to NEVER.
<figure>
	<a href="{{ site.cdn-url }}/wp-content/uploads/2010/11/Tversity-Never-Transcode-Setup.jpg">
    <img src="{{ site.cdn-url }}/wp-content/uploads/2010/11/Tversity-Never-Transcode-Setup-640.jpg" 
         alt="Tversity Never Transcode Setup booya gadget" title="Tversity Never Transcode Setup"></a>
	<figcaption>Tversity Never Transcode Setup</figcaption>
</figure>
Under General Settings you need to set up TVersity to allow outside connections to your media.  Check the Box that says: “TVersity should accept request originating from outside the home network”.  Enter your desired username and password.

<figure>
	<a href="{{ site.cdn-url }}/wp-content/uploads/2010/11/Tversity-Home-Network-Set-up.jpg">
    <img src="{{ site.cdn-url }}/wp-content/uploads/2010/11/Tversity-Home-Network-Set-up-640.jpg" 
         alt="Tversity Home Network Set up booya gadget" title="Tversity Home Network Set up"></a>
	<figcaption>Tversity Home Network Set up</figcaption>
</figure>
Remember to save your settings when you are done.

**Step #3 &#8211; Streaming your move with nswPlayer**

Head on over to the Android Marketplace and download nswPlayer.  This is the only player that will stream an .mp4 from TVersity.   Once you have the player installed it is time to head over to your online Tversity page.  The address of your online Tversity page is *http://youripaddress:41952*. If you are unsure of your PC's IP Address head on over to [whatsmyip.com](https://www.whatismyip.com/){:target="_blank"} and it will show it to you. Enter your username and password and then work through the menus to find your movie file.  Select the file and enjoy the show.