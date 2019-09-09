---
title: FreeNAS PS3 XBox Samsung 6500 LED TV Streaming Media
date: 2010-11-20T17:07:29+00:00
author: BooyaCuz
excerpt: "Let me begin by saying, I love my FreeNAS box. My Shuttle Box rocking FreeNAS actually replaced my Windows Home Server box as my main Media Streaming source for my entire house."
layout: post
permalink: /2010/11/freenas-ps3-xbox-samsung-6500-led-tv-streaming-media.html
post_thumbnail_loc: /images/category/freenas-open-source-logo-booya-thumb.jpg

categories:
  - OTHER TECHNOLOGY
  - PS3
  - Streaming Video
  - Xbox

tags:
  - freenas ps3
  - freenas xbox
  - How To
  - nas
  - playstation
  - ps3 move
  - xbox 360
---
<figure>
	<a href="{{ site.cdn-url }}/wp-content/uploads/2010/11/FreeNAS-XBox-PS3-Stream-Video.jpg">
    <img src="{{ site.cdn-url }}/wp-content/uploads/2010/11/FreeNAS-XBox-PS3-Stream-Video-640.jpg" 
         alt="FreeNAS XBox PS3 Stream Video" title="FreeNAS XBox PS3 Stream Video"></a>
	<figcaption>FreeNAS XBox PS3 Stream Video</figcaption>
</figure>
I was able to stream to both PS3,XBox, and my [Samsung 46" C6500 1080p LED HDTV](http://amzn.to/2l9PPaW){:target="_blank"} using the XBox 360 DLNA profile. It even worked playing the same video simulataneously on both consoles.  I was impressed once again with my beloved FreeNAS.

With the recent Kinect release, I had to bust out my XBox from the closet but since Playstation 3 is my "primary" console, I knew I was going to have to make some changes on my NAS box..  I wasn't sure if it was going ot be a hassle or not, or require constant flip-flopping of changes to be able to stream my Video, Music, and Picture library to BOTH my PS3 and XBox by way of my beloved FreeNAS Box.  **I was very happy to achieve successful streaming of all my media (movies #1 priority) with a few settings changes** and rebuild of my Fuppes UPnP settings.
<figure>
	<a href="{{ site.cdn-url }}/wp-content/uploads/2010/11/FreeNAS-PS3-XBox-Fuppes-UPnP-Settings.jpg">
    <img src="{{ site.cdn-url }}/wp-content/uploads/2010/11/FreeNAS-PS3-XBox-Fuppes-UPnP-Settings-640.jpg" 
         alt="FreeNAS PS3 XBox Fuppes UPnP Settings" title="FreeNAS PS3 XBox Fuppes UPnP Settings"></a>
	<figcaption>FreeNAS PS3 XBox Fuppes UPnP Settings</figcaption>
</figure>
I read up at the [FreeNAS Forum](https://sourceforge.net/apps/phpbb/freenas/index.php){:target="_blank"} to view some basics before jumping in.  If you rock FreeNAS I definitely recommend checking it out because there are a lot of smart people there.

Basically I did just a few steps:

1. Select the Microsoft XBox 360 DLNA Profile in the UPnP Settings
2. Access the Web GUI via the link at the bottom of the Fuppes settings page.
3. Rebuild the Database, don't do step 4 until step 3 is complete.  View your Log settings to see when this process is complete.
4. Rebuild the Virtual Container, once this was done I just restarted the UPnP service.

Restart the service, restart your PS3 and XBox and do some testing on your video, audio and image files.

<figure>
	<a href="{{ site.cdn-url }}/wp-content/uploads/2010/11/FreeNAS-PS3-XBox-My-Setup-SHUTTLE-BOX.jpg">
    <img src="{{ site.cdn-url }}/wp-content/uploads/2010/11/FreeNAS-PS3-XBox-My-Setup-SHUTTLE-BOX-640.jpg" 
         alt="FreeNAS PS3 XBox My Setup SHUTTLE BOX" title="FreeNAS PS3 XBox My Setup SHUTTLE BOX"></a>
	<figcaption>FreeNAS PS3 XBox My Setup SHUTTLE BOX</figcaption>
</figure>
**Key Factor for your PS3 or XBox video/movie streaming..**

I use what's best for my setup which is mostly XVid with AVI formats mostly converted with either [Sony Vegas](https://forums.creativecow.net/magixvegas){:target="_blank"} or [DVDFab](http://www.dvdfab.cn/){:target="_blank"}.  I love both products for managing video files, and I do not like having a stack of movies lying around and since BooyaGadget pumps out a lot of videos, we're always tweaking formats etc.  Since we love streaming media at Booya Gadget I rely heavily on video conversions so our media is friendly via  iTunes, PSP, PS3,Android,Blackberry,XBox, JVC Kamelion Head Unit,and PC it's a lot of video files !   I haven't started converting my BluRay library yet because I'll have to upgrade my storage as those are some big ol' files.  But those big files are converted nicely with the Core i7 8 threads cranking on it.  My other key network related item is that I use the [D-Link DIR-655 Router Switch](http://amzn.to/2k8gW6c){:target="_blank"}. I do really like that router, it was my first DLink product after switching around from Linksys and Netgear in the past.

<figure>
	<a href="{{ site.cdn-url }}/wp-content/uploads/2010/11/FreeNAS-PS3-and-XBox-Streaming-Pics-Video-Images-LAN-TRAFFIC-USED.jpg">
    <img src="{{ site.cdn-url }}/wp-content/uploads/2010/11/FreeNAS-PS3-and-XBox-Streaming-Pics-Video-Images-LAN-TRAFFIC-640.jpg" 
         alt="FreeNAS PS3 XBox LAN Traffic Visual During dual Streaming" title="FreeNAS PS3 XBox LAN Traffic Visual During dual Streaming"></a>
	<figcaption>FreeNAS PS3 XBox LAN Traffic Visual During dual Streaming</figcaption>
</figure>
Here is our[ Video demonstration showing Video Streaming from freeNAS to XBox and PC](https://www.youtube.com/watch?v=22d4B6YqpAk){:target="_blank"}
<iframe width="560" height="315" src="https://www.youtube.com/embed/22d4B6YqpAk" frameborder="0" allowfullscreen></iframe>