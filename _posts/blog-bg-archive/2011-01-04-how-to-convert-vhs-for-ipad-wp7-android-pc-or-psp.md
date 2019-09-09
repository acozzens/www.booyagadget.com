---
title: How To Convert VHS for iPad, WP7, Android, PC or PSP
date: 2011-01-04T15:46:48+00:00
author: BooyaTRJ
excerpt: "It's time to convert all those old VHS tapes that are cluttering the closet into nice digital files that you can play and share with your friends."
layout: post
permalink: /2011/01/how-to-convert-vhs-for-ipad-wp7-android-pc-or-psp.html
post_thumbnail_loc: /wp-content/uploads/2011/01/old-vcr-vhs-tape-booya-gadget-thumb.jpg

categories:
  - Android
  - OTHER TECHNOLOGY
  - PSP
  - Smart Phones
  - Streaming Video
  - Windows Phone 7

tags:
  - Android
  - android video
  - convert vhs
  - How To
  - iPad video
  - vhs conversion
  - video conversion
  - WP7
  - wp7 video
---
In this beginners guide we are going to convert our VHS tapes into two different digital files. The first file will be a full resolution copy of your personal video and the second will be a smaller digital file for playback on your Android or PSP.  Share them on the web at Facebook or Flickr with your friends.  These tapes aren't designed to last forever so the time to make them digital is now.

Now there are devices out there that you can buy that claim to make this process painless. However, here at Booya Gadget we like to save money so we are going to show you how to do this with a device that you probably already have stuffed away in the attic, your VCR. Here are a list of things that you will need to complete this Booya.

  1. VHS Tapes
  2. Your Old VCR
  3. A PC Tuner Card [Hauppauge HVR 1150 on Amazon](http://amzn.to/2ll4IHV){:target="_blank"}
  4. Video Editing Software

This conversion Booya breaks down into four stages.  First, we are going to capture the video.  Second, we are going to edit the video.  Then we will then compress the video.  Finally, we will upload and share the video.  This process will take some time depending on the lenght of the video that you capture and the power of your PC.

  * **Capture Your Video**

To capture analog video onto your PC you are going to need your old VCR.  To connect your old VCR to your PC you will need a PC Tuner Card.  These cards are usually purchased to watch live TV on your PC via software like Windows Media Center.  These cards are also able to capture an analog signal via the coaxial inputs on the back.  This is the connection we will make your our Tuner Card so that we can capture our personal video.  Here is a card that [Hauppage](http://www.hauppauge.com/site/products/data_hvr1150.html){:target="_blank"} makes that will accept the signal that we are trying to catch.

<figure>
	<a href="{{ site.cdn-url }}/wp-content/uploads/2011/01/WinTV-HVR-1150-model-1288-Booya-Gadget1.jpg">
    <img src="{{ site.cdn-url }}/wp-content/uploads/2011/01/WinTV-HVR-1150-model-1288-Booya-Gadget1.jpg" 
         alt="WinTV-HVR-1150 model 1288 Booya Gadget" title="WinTV-HVR-1150 model 1288"></a>
	<figcaption>WinTV-HVR-1150 model 1288</figcaption>
</figure>
Using a coaxial cable connect the "Out to TV" port on your VCR to the analog input on your PC Tuner card.  The reason we are using coaxial cable to make this connection is that it will carry both the video and the audio to the Tuner Card.  You can connect the RCA cable or the S-Video cables to your tuner card, but don't forget that you will have to run a separate line for audio.

Once you are connected it is time to launch the software that will capture your video.  I am using Win-TV, which is provide by Hauppage when you buy the PC Tuner Card.  Most tuner cards will come with there own capture software.  Win-TV version 6 is available [here](http://www.hauppauge.com/site/support/support_wintv6.html){:target="_blank"}.  Win-TV version 7 has been released, but it requires a Win-TV version 6 disc.  As for capture version 6 is all we will need since we will be doing our editing in a different software suite.

Press play on your VCR so that the device is sending out a signal and then go into the settings and search for analog channels.  It will find the channel that your VCR is broadcasting on and you can then select that channel to view on your PC screen.  You can adjust the output directory while in the settings menu.  I am going to leave it in the default location.  Stop your VHS tape and rewind it back to the beginning.  Hit the record button in Win-TV and then hit the Play button on your VCR.  Now just sit back and relax and let the capture continue.

You will have to manually watch your capture process when you think your video is going to end so that you can stop Win-TV from recording.  Once the end of your video has passed, stop the recording.  Remember we are going to edit and compress this file so the beginning and the end of the video does not have to be perfect.  Congratulation you now have an uncut digital version of your video.

  * **Edit Your Video**

Now its time to edit your video.  Using Sony Vegas Pro, I drag my video into the work area.  First I right click on my video and select "Pan and Crop."  This will open up a new window to allow you to crop the edges off of your video.  Analog video from a VHS can have uneven edges so I use Pan and Crop to cut these out.  Drag the box around your video to make is smaller and give your video a good clean edge.  Second, I cut off any excess video at the beginning or end of my video.  To do this you select where you would like the cut to occur and then under the edit tab you can select "Split."  This will create a break in your video and then you can select the part that you no longer want and hit the delete key.  Finally, I drag a fade in and fade out at the beginning and end of my video.

  * **Compress Your Video**

Now that we have finished editing our video we are going to render this video and this will become our full resolution version.  This version will match the original VHS version in quality and would be great for burning onto DVD or streaming over your home network to watch on your TV.  We will export this video in 640 x 480 because that was its original resolution size.   Compression time will depend on the length of your video and the processing power of your PC.  In most cases once you hit the render button, feel free to go and get some other stuff done while your PC goes to work.

Once the compression is done you now have a digital copy of your personal video.  Feel free to watch some of the video to make sure that it reflects the editing that you did.  Now we will take this version and make a smaller more portable digital file that will be great for watching on your Android, PSP, or Iphone.

Once you have installed Handbrake on your PC it is time to convert your digital file for streaming and for your mobile device.  Open the Options Menu and set the default output folder to your TVersity Shared Folder.  Use the Iphone Legacy settings in Handbrake to create your file.

Here is where you have to make your decision on compression.  Booya sets the Video Width at 480 and then selects the button to "Keep Aspect Ratio".  The reason for this is that when the file is complete it will not only stream to your Android, but it will be playable by your PSP.

Before you begin your conversion you must check the "Web Optimized" button.  This makes your .mp4 a progressive file that can be streamed.

Select the Video tab and we can now adjust the quality of the file.  Booya sets the Average Bitrate between 384 and 512 so that we can get a file that is still of decent quality, but not too large for streaming over 3G.

Hit Start to get your conversion going, conversion times will vary depending on the power of your PC.  Once this process is finished you will have a file that you can play on your Iphone, Android Device or PSP.

* **Sharing your Video Collection**

Once you have finished all of your compression you will have 2 Digital files of your old VHS tape.  One version will be the full resolution copy, while the other will be a smaller digital copy that will be great for your portable devices.  Now in this final step we will show you how to upload and share your video online.  The length and size of your video file is going to dictate where you can store it online.  Normally we would recommend Youtube, but there is a limit of 15 minutes at Youtube and some old family movies filled the entire 2 hour VHS tape.

For my example in this Booya I have captured and compressed an old High School Basketball game.  This video isn't going to fit within the restrictions of Youtube.  The game is over an hour long so I will have to use another service.  One of the services that I have found is Google's Picasa Web Albums.  Despite owning Youtube, Google has a different set of rules for Web Albums.  There is a 1GB limit on video uploads, but the length of video is unlimited, which for our purposes is a much better situation.

As for uploading to Picasa, you will need a Google account, if you have a Gmail account then you already have one.  After you download the Picasa Software you can sync up to your Google account to upload your video collection.  Always upload your original full resolution version if it fits within the limits of the upload requirement.

This tutorial is in noway the end all, be all to VHS conversion.  This is just one of the many ways to accomplish this and share your old content.