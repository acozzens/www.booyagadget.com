---
title: 'How To: Create Google Chrome Web Extensions'
date: 2011-05-23T15:45:42+00:00
author: BooyaTRJ
excerpt: "A how to tutorial on how to create custom Google Chrome Web Extensions."
layout: post
permalink: /2011/05/how-to-create-google-chrome-web-extensions.html
post_thumbnail_loc: /wp-content/uploads/2011/05/chrome-web-extensions-booya-thumb.jpg

categories:
  - Chromebook
  - Computers
  - Google
  - Google Web Apps
  - Streaming Video

tags:
  - Android
  - Google Chrome Extensions
  - Google Webmaster Tools
  - how to make chrome web extension
---
So you have followed BooyaGadget's tutorial on [How To: Create Google Chrome Web Apps](/2011/05/how-to-develop-a-google-chrome-web-app.html), but you have hit a roadblock. The problem is that you want to create an App for your favorite site, but you are not the owner. Well there is a work-around, it won't be public, but it will work in your Browser and let's be honest, Chrome Web Apps are just beautiful glorified bookmarks. That being said, I love them, and I use them everyday so I would like to have all my favorite sites right there with all my Google Chrome Web Apps.

The first thing you will need is your favorite website. In this tutorial I will use ESPN3.com, which is not present in the [Google Chrome Web Store](https://chrome.google.com/webstore/category/extensions?hl=en-US){:target="_blank"}. This process will work for all your favorites and once you have done the process once, you will spend more time creating the icons.

>Well there is a work-around, it won't be public, but it will work in your Browser and let's be honest, Chrome Web Apps are just beautiful glorified bookmarks.

#### Step #1

Create a "Manifest" using notepad.  Similar to creating a Web App, you need to copy this code and save it as "manifest.json"
~~~
{"name": "ESPN","
description": "Watch Live Sports Online","
version": "1.0","
icons": {
"128": "icon_espn.png"
},
"app": {
"urls": [
"http://www.espn3.com"
],
"launch": {
"web_url": "http://www.espn3.com"
}
},
"permissions": [
"unlimitedStorage",
"notifications"
]
}
~~~
This extension is for ESPN3.com, but if you would like to make changes just edit the bold lines to fit your needs.   The icon must have the same name as the icon that you will create.  The icon must also be 128x128 to work for the extension.  Once you have finished this manifest place it into a folder named for your extension.  In this example I am going to place the manifest into a folder named ESPN3.

#### Step #2
<figure>
  <img src="{{ site.cdn-url }}/wp-content/uploads/2011/05/icon_espn-booya-chrome-extension.png" 
       alt="how to chrome extension espn icon booya gadget" title="chrome extension espn icon">
	<figcaption>Watch ESPN Icon</figcaption>
</figure>

Create an Icon for your extension.  As mentioned above the icon must be 128 x 128 and named exactly as you have called it out in the manifest.  Typically for commercial products that I am converting to extensions I will do a Google Search for an Icon.  Most companies now have created icons for the numerous Apps that are now floating around in all the different marketplaces.  Feel free to be creative and create one yourself if you like.  When you are finished place the icon in the same folder as your manifest, in this case ESPN3.

#### Step #3
Installing your extension is very simple.  Click on the setting icon for Google Chrome and scroll down until you see Tools.  Under the Tools tab you will see Extensions.  This will open a new tab in Chrome and you will see a list of previously installed Extensions.
<figure>
    <img src="{{ site.cdn-url }}/wp-content/uploads/2011/05/howto-create-google-chrome-web-extensions-1-tools-booya.jpg" 
         alt="how to chrome extension settings tools extensions booya gadget" title="navigate to extensions">
	<figcaption>Settings - Tools - Extensions</figcaption>
</figure>

Click on "Load Unpacked Extension" and navigate to your created Folder.  Select the folder and click OK.  This will install your extension.
<figure>
    <img src="{{ site.cdn-url }}/wp-content/uploads/2011/05/howto-create-google-chrome-web-extensions-2-unpack-booya.jpg" 
         alt="how to chrome extension load unpacked booya gadget" title="load unpacked">
	<figcaption>Load Unpacked Extension</figcaption>
</figure>

There it is, open a new tab and your new extension will be there waiting for you.  Click on it to give it a test drive and make sure that it is working properly.  Repeat this process for all your favorite websites that aren't in the Chrome Web Store.  You can see from my screenshot that I have also created a Hulu Plus extension.  As I said before, you'll spend more time tracking down or creating icons. Booya!
<figure>
	<a href="{{ site.cdn-url }}/wp-content/uploads/2011/05/howto-create-google-chrome-web-extensions-list-booya.jpg">
    <img src="{{ site.cdn-url }}/wp-content/uploads/2011/05/howto-create-google-chrome-web-extensions-list-booya-640.jpg" 
         alt="how to chrome extension custom apps list booya gadget" title="chrome extension custom apps list"></a>
	<figcaption>chrome extension custom apps list</figcaption>
</figure>