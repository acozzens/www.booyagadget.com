---
title: How to Develop a Google Chrome Web App
date: 2011-05-19T21:44:33+00:00
author: BooyaTRJ
excerpt: "A brief guide on how to create your own Chrome Web Apps."
layout: post
permalink: /2011/05/how-to-develop-a-google-chrome-web-app.html
post_thumbnail_loc: /wp-content/uploads/2011/05/icon_128.png

categories:
  - Android
  - Chromebook
  - Google

tags:
  - how to make chrome web app
  - chrome os
  - chrome developer
  - chrome web app
---
So Google has a [Web Store](https://chrome.google.com/webstore?hl=en-) full of Apps that you can use within Google Chrome.  Apps that span an entire spectrum from family fun to all your social networking needs. Want to easily access your favorite sites or play [Angry Birds](https://chrome.google.com/webstore/detail/angry-birds/nllkkflncainlmehooebdaodggehpknh?hl=en){:target="_blank"} on the office dime?  It is all there as long as you are a Google Chrome user.

**UPDATE FROM GOOGLE**
> As of November 21st, 2016, all newly published packaged or hosted apps are restricted to Chrome OS, and are not available to users on Windows, Mac or Linux. Existing apps will continue to be available on all major platforms and will continue to receive updates.
**Note:** This change does not apply to Google Drive Apps or Add-Ons for Google Apps.

<figure>
	<a href="{{ site.cdn-url }}/wp-content/uploads/2011/05/how-to-develop-a-google-chrome-app-booya.jpg">
    <img src="{{ site.cdn-url }}/wp-content/uploads/2011/05/how-to-develop-a-google-chrome-app-booya-640.jpg" 
         alt="How To Develop a Google Chrome App 4" title="How To Develop a Google Chrome App4"></a>
	<figcaption>Chrome Web Apps</figcaption>
</figure>

As an avid Google user, one might argue that Google currently owns my entire life when it comes to the world wide web, I have found myself using these little apps more and more each day.  Its to the point that I now have an app for all my favorite sites.  However, one of my favorite sites, Booya Gadget was missing from the store.  I figured that I would not only fix that massive error, but I would show you how to make your own Chrome Web Apps, so that you can share your blog with the world.

Head on over to your [Developer's Dashboard](https://chrome.google.com/webstore/developer/dashboard?hl=en-US){:target="_blank"} to get started and here are the steps to get your Blog in the Google Web Store:

<figure>
	<a href="{{ site.cdn-url }}/wp-content/uploads/2011/05/how-to-develop-a-google-chrome-app-3-booya.jpg">
    <img src="{{ site.cdn-url }}/wp-content/uploads/2011/05/how-to-develop-a-google-chrome-app-3-booya-640.jpg" 
         alt="How To Develop a Google Chrome App 5" title="Developer Dashboard"></a>
	<figcaption>Developer Dashboard</figcaption>
</figure>

**Verify your Blog**- Google wants to know that you own your blog so you will have to verify it with [Google Webmaster Tools.](https://www.google.com/webmasters/tools/home?hl=en){:target="_blank"}

**Buck up** - Five bucks to be exact.  To publish your final product it will cost you 5 dollars.  This is a one time fee so once you fork it over, you can publish as many apps as you like.

**Create A Folder** - On your desktop create a folder and give it the name of your blog.  In my case, we are doing the Booya Gadget site, I will name my folder "BooyaGadget"

**Create A Manifest** - Using notepad open up a new document.  Cut and paste the following code into your new document.  Fill in the appropriate data for you blog and save this file as "manifest.json" and store it in the folder you created.

~~~~
{
    "name": "Name of Your Blog",
    "description": "Description of Your Blog",
    "version": "0.1",
    "icons": {
        "128": "icon_128.png"
    },
    "app": {
        "urls": [
            "http://www.yourblog.com"
        ],
        "launch": {
            "web_url": "http://www.yourblog.com"
        }
    }
}
~~~~

**Create your Icon** - The icon must be 128 x 128 and saved in .png format.  This is the icon that will display in the Chrome Browser, so make it nice.  Save the file as "icon_128.png" and place it in the folder with your Manifest.
<figure>
    <img src="{{ site.cdn-url }}/wp-content/uploads/2011/05/icon_128.png" 
         alt="Booya Gadget Icon" title="Booya Gadget Icon">
	<figcaption>Booya Gadget Icon</figcaption>
</figure>

**Compress Your Folder** - With the Manifest and Icon inside compress your folder into a ZIP File.  Name the ZIP File the name of your Blog.

**Upload your App** - From your [Developer's Dashboard](https://chrome.google.com/webstore/developer/dashboard?hl=en-US) click "Add A New Item"  This will allow you to upload your ZIP File.

**Describe Your App** - Now that you have uploaded your App it is time to fill in the descriptions so that users will know what they can expect when they install your App.  Upload some Screenshots or images of your blog that best describe your Blog.  These files must be 400 x 175 and saved in .PNG format. Fill in all the required information for your App page, remember that this is the page that users will see before deciding to download your App.
<figure>
	<a href="{{ site.cdn-url }}/wp-content/uploads/2011/05/how-to-develop-a-google-chrome-app-4-booya-gadget.jpg">
    <img src="{{ site.cdn-url }}/wp-content/uploads/2011/05/how-to-develop-a-google-chrome-app-4-booya-gadget-640.jpg" 
         alt="How To Develop a Google Chrome App 6" title="App Meta Data and Description"></a>
	<figcaption>App Meta Data and Description</figcaption>
</figure>

**Publish Your App** - There are two choices for publishing. You can publish your app "for testers," which will allow you to send your App to emails you choose for testing.  The other option is to publish your app to the Web Store.  If you feel you have done all you can and your App is ready to go live, then hit the Publish Button.
<figure>
	<a href="{{ site.cdn-url }}/wp-content/uploads/2011/05/how-to-develop-a-google-chrome-app-5-booya-gadget.jpg">
    <img src="{{ site.cdn-url }}/wp-content/uploads/2011/05/how-to-develop-a-google-chrome-app-5-booya-gadget-640.jpg" 
         alt="How To Develop a Google Chrome App 7" title="Chrome Web my App Listed"></a>
	<figcaption>Chrome Web my App Listed. Booya!</figcaption>
</figure>
Now you are in the Google Web Store.  Give yourself a huge BOOYA!