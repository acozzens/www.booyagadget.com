---
title: 'Windows Phone 7 Apps: Developing was easy and fun!'
date: 2011-03-22T20:33:16+00:00
author: BooyaCuz
layout: post
permalink: /2011/03/windows-phone-7-apps-developing-was-easy-and-fun.html
published: false
categories:
  - Smart Phones
  - Windows Phone 7

tags:
  - App Hub
  - Booya Gadget
  - charlie sheen soundboard
  - Developers Guide
  - How To make an app
  - Microsoft
  - Mobile Ads
  - Pub Center
  - SDK
  - Smart Phone Development
  - Visual Studio
  - VS2010 Express Review
  - WP7 Development
---
<a rel="attachment wp-att-3424" href="http://www.booyagadget.com/2011/03/windows-phone-7-apps-developing-was-easy-and-fun.html/wp7-vs-2010-express-phone"><img class="alignleft size-thumbnail wp-image-3424" title="Microsoft Visual Studio 2010 Express for Phone" src="http://www.booyagadget.com/wp-content/uploads/2011/03/WP7-VS-2010-Express-Phone-300x138.png" alt="Microsoft Visual Studio 2010 Express for Phone Booya Gadget" width="300" height="138" srcset="http://www.booyagadget.com/wp-content/uploads/2011/03/WP7-VS-2010-Express-Phone-300x138.png 300w, http://www.booyagadget.com/wp-content/uploads/2011/03/WP7-VS-2010-Express-Phone-480x221.png 480w, http://www.booyagadget.com/wp-content/uploads/2011/03/WP7-VS-2010-Express-Phone.png 527w" sizes="(max-width: 300px) 100vw, 300px" /></a>When i'm not rocking Booya Gadget articles, I pay my bills as a SQL Database developer / analyst.  Although I did begin my career as an applications analyst, SQL and application development are obviously very different.  Having purchased my own Windows Phone 7 a couple months ago, I just could not resist the urge to see if I could indeed develop a phone application.  Keep in mind, curiosity like this is why Booya TRJ and I started Booya Gadget.   Well, let me assure you, I was very impressed with the WP7 SDK.  **If you have some development skills, I highly recommend you give this a shot, because you CAN do it**.  You don't even really have to own a Windows Phone to do it, although I would strongly urge you to acquire one when you get a few bucks, or contract expires with your existing Mobile Carrier.  A friendly reminder to you is that I had never developed a mobile application before.

I have played with many SDK's in my day, and this was by far one of the easiest to get setup and running.  Based on my initial sniffing around, it was clear to me that Microsoft is indeed encouraging developers just like yourself to try out their simple SDK.  Even as a SQL developer, I do rock Visual Studio on occasion, so being familiar with it would help.  To be very direct, you can be up and running with a full Development and emulation environment within an hour or so.  The longest part was simply downloading and installing the FREE VS2010 Express Phone flavor of this slick SDK.  I'm serious.  **Part of me doesn't even want to tell you how easy it was or how much fun I had because you will be my competition**, but I just can't keep this to myself and frankly I'd love to see your creative skills on my phone anyways.

<div id="attachment_3427" style="width: 195px" class="wp-caption aligncenter">
  <a rel="attachment wp-att-3427" href="http://www.booyagadget.com/2011/03/windows-phone-7-apps-developing-was-easy-and-fun.html/wp7-emulator-snapshot-booya"><img class="size-thumbnail wp-image-3427" title="WP7 VS2010 Express Phone Awesome Emulator" src="http://www.booyagadget.com/wp-content/uploads/2011/03/WP7-Emulator-Snapshot-Booya-185x300.png" alt="WP7 VS2010 Express Phone Awesome Emulator Booya Gadget" width="185" height="300" srcset="http://www.booyagadget.com/wp-content/uploads/2011/03/WP7-Emulator-Snapshot-Booya-185x300.png 185w, http://www.booyagadget.com/wp-content/uploads/2011/03/WP7-Emulator-Snapshot-Booya-182x295.png 182w, http://www.booyagadget.com/wp-content/uploads/2011/03/WP7-Emulator-Snapshot-Booya-154x250.png 154w, http://www.booyagadget.com/wp-content/uploads/2011/03/WP7-Emulator-Snapshot-Booya.png 432w" sizes="(max-width: 185px) 100vw, 185px" /></a>
  
  <p class="wp-caption-text">
    WP7 VS2010 Express Phone Awesome Emulator Screenshot
  </p>
</div>

**WHERE TO START?**

I'm not going to go into detail on everything you need to do, because I don't need to, [Microsoft's &#8220;Getting Started Guide&#8221;](http://create.msdn.com/en-us/home/getting_started "Get Started Developing for WP7 Today") was very solid indeed.  As I said, I was up and running with full emulation environment within about 1 hour..  I can write in many-a-language, but you can expect C# to be your primary development language.  There does appear to be options for Visual Basic as well, but since I prefer C# you'll have to check that out when you explore the getting started page.

**WHAT'S THE CATCH?**

C'mon now Booya Cuz, it can't be that easy dude, right ?  I still think there's not really a catch.  You can download the kit, start your own &#8220;Hello World&#8221; app, and run it on your desktop in a matter of minutes after installing **Visual Studio 2010 Express Phone.** But if you have aims of **actually publishing an application to the world** then you will need to register as an individual or company with App Hub.  Unfortunately this part is not free.  At the time I registered I paid $99 which allows me to pump up up to 100 (no cost) apps.  However, since I don't have diaper bills to pay, I jumped at that price, didn't bother me at all!   Once again, in a matter of minutes, I became a bonafied, and most importantly certified Mobile application developer.  Booya Mom would be proud !

**Another &#8220;catch&#8221; is Silverlight.** This was more of a conceptual issue for me, and I found it a little bit different than what I had envisioned.  Back in the day(think 1994-1999), I used to roll C++ MFC, which focused more on **Modal** Dialog based windows.  What that means is that I had FULL CONTROL over what the user did, how they interacted, exited and left my program.  All the basic principles of coding are still there but what took me some time to wrap my head around was User Navigation.  In Windows Phone 7, a user has 2 &#8220;bonus&#8221; options of leaving or navigating your app.  They can hit BACK, or they can press the Windows button and go to the desktop.  Because I was rusty-as-all-hell it took me a few hours of development and my own issues to wrap my head around this.  Don't worry, you'll get used to it very fast when you're in test mode.  If you find yourself choking a little on this while you're playing, the term you'll want to explore is **Tombstoning**.  That search should lead you to the river if knowledge that you need.  To manage this, I found myself working with &#8220;Isolated Storage&#8221;, and overriding events like &#8220;On Navigated To&#8221;.  It will make sense once you make the brave jump into this very fun project !

**MAKING MONEY: OPTIONS**

There are 2 main flavors of getting paid.  #1 is make an app that ain't free.  99 cents is the minimum you can charge for an application, but if you're some kind of Steven Hawking genius you can go all the way up $500.  Uhh, if you make a $500 app, I really want to see what the hell it does.  It better change my life, slice bread, or give a hell of a back massage.

**The 2nd way you can make money is with Ads**.  Advertisements may piss off a customer or 20, but for a free App, I personally don't mind, in fact I even give a click or two to show my love if an Ad is well targeted.  And guess what, the Microsoft Gods have made that easy as well with yet another freebie download:  [The Advertising SDK](http://msdn.microsoft.com/en-us/library/ff973757(v=msads.10).aspx "Free Advertising SDK").  This takes very little time to setup, comes with easy to follow instructions, and simple, yet thorough, reporting available at the [Microsoft Pub Center](https://sts.advertising.microsoft.com/?wa=wsignin1.0&wtrealm=https%3a%2f%2fpubcenter.microsoft.com%2fLogin%2fWifLogin "View the Reports for your Ads").  You can absolutely customize the look, feel, and content of your ads.  It even allows you to get very specific as to the ads you want surfaced by topics.  The limitation here is that you can only select 3 focused topics.  For example, if you make an application related to Movies, you probably wouldn't want gardening ads to appear, get it ?

&nbsp;

**SUMMARY**

If you read this far, congratulations, because you have an interest in development and a little spare time.  That's pretty much all you need to get started.  Assuming you don't have any jive-turkey related issues simply downloading free software then I guarantee that you can build a Hello World application in ONE NIGHT !  LOL, Microsoft already gives you the damn code to do it!

<div id="attachment_3312" style="width: 210px" class="wp-caption alignleft">
  <a rel="attachment wp-att-3312" href="http://www.booyagadget.com/2011/03/free-windows-phone-7-app-charlie-sheen-winning-sounboard.html/csheadshot_reasonably_smal200"><img class="size-full wp-image-3312" title="Charlie Sheen Headshot" src="http://www.booyagadget.com/wp-content/uploads/2011/03/CSHeadshot_reasonably_smal200.png" alt="Charlie Sheen Winning WP7 Free App" width="200" height="200" srcset="http://www.booyagadget.com/wp-content/uploads/2011/03/CSHeadshot_reasonably_smal200.png 200w, http://www.booyagadget.com/wp-content/uploads/2011/03/CSHeadshot_reasonably_smal200-105x105.png 105w" sizes="(max-width: 200px) 100vw, 200px" /></a>
  
  <p class="wp-caption-text">
    Charlie Sheen Winning WP7 Free App
  </p>
</div>

I did it and you can too.  I do have a day job, so I can' t spend as much time as I'd like but I have a zillion ideas.  If you are a fellow thinker, you might wake up in the middle of the night with a million dollar idea.  I have so many super-secret ideas that I must have a notepad file to store them all or email myself random thoughts on app ideas I get.  I have multiple applications in progress.  Some are easy, some are more nasty.  You'd be really surprised at how many Web Services are out there for you to tap into.

My first app took about 1 weekend to create, edit, and test.  Upon submittal, I got my PUBLISHED letter from Microsoft about 4 days later.  Waiting was an anxiety rollercoaster, but I had confidence in the app.   If you want to see my first (VERY SIMPLE) app then feast your eyes upon the [Charlie Sheen WINNING Soundboard.](http://social.zune.net/redirect?type=phoneApp&id=9748d81e-c34b-e011-854c-00237de2db9e "Booya Gadget's Charlie Sheen WINNING Soundboard (opens zune)") Totally easy, I could pump out a bunch of these, but I have my development focused more complicated ideas, and I will eventually pump out a non-freebie download!  SWEEET.

<div id="attachment_3313" style="width: 190px" class="wp-caption aligncenter">
  <a rel="attachment wp-att-3313" href="http://www.booyagadget.com/2011/03/free-windows-phone-7-app-charlie-sheen-winning-sounboard.html/releasescreenshot1480800"><img class="size-thumbnail wp-image-3313" title="Charlie Sheen WP7 Screenshot" src="http://www.booyagadget.com/wp-content/uploads/2011/03/ReleaseScreenShot1480800-180x300.png" alt="Charlie Sheen WP7 Screenshot" width="180" height="300" srcset="http://www.booyagadget.com/wp-content/uploads/2011/03/ReleaseScreenShot1480800-180x300.png 180w, http://www.booyagadget.com/wp-content/uploads/2011/03/ReleaseScreenShot1480800-177x295.png 177w, http://www.booyagadget.com/wp-content/uploads/2011/03/ReleaseScreenShot1480800-150x250.png 150w, http://www.booyagadget.com/wp-content/uploads/2011/03/ReleaseScreenShot1480800.png 480w" sizes="(max-width: 180px) 100vw, 180px" /></a>
  
  <p class="wp-caption-text">
    Charlie Sheen WP7 Screenshot All 21 Rants
  </p>
</div>

If you read this article, became inspired, and went all the way let me know.  I'll check out your app myself if you want to share it with Booya in the comments.  If it's a paid app that is in my wheelhouse, let me know i'll give the bastard a spin and give you HONEST feedback. CAUTION:  I am really honest!    My Charlie Sheen app is not mind blowing, but it got my feet wet and I am addicted.  You can plug your stuff here if you really are trying to get a boost, but please consider reciprocating the love.  Plus, my app is free.  Check it out, see if you can copy it.  I don't mind, plus, it'll inspire me to beat you with my next one!  There is enough room to go around, and a lot of smart people out there.  I love the creativity&#8230;

BOOYA, HAVE FUN OUT THERE, YOU CAN DO IT !