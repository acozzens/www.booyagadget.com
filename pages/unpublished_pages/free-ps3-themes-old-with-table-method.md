---
title: Free PS3 Themes old
date: 2011-03-04T12:47:06+00:00
author: Booya Gadget
layout: page
search_omit: true
#published: false
permalink: /oldthemes
published: false
---
#### Enjoy our free selection of free themes for your PS3!
* [View our Full Size Preview images on Flickr Booya Gadget](https://www.flickr.com/photos/booyagadget/sets/72157626217451291/){:target="_blank"}

1. TOC
{:toc}
<!-- your comment goes here 

border="1"
  <tr><th colspan="2">SEASONAL PS3 THEMES</th></tr>

  <th>Christmas Snowman</th><th>Easter Eggs</th></tr>
  border=".5"
-->

<BR>

#### Seasonal PS3 Themes
{% assign iterator = 0 %}
{% assign arraysize = site.data.ps3-themes-seasonal.size %}
##### Total Seasonal Themes: {{ arraysize }}
<table class="table" >
  {% for ps3-theme in site.data.ps3-themes-seasonal %}

  {% assign current-theme = site.data.ps3-themes-seasonal[iterator] %}
  {% assign next-theme = nil %}
  {% unless forloop.last %}
    {% assign iterator-next = iterator | plus: 1  %}
    {% assign next-theme = site.data.ps3-themes-seasonal[iterator-next]  %}
  {% endunless %}

  <tr>
    <td><center>{{ current-theme.title }}</center>
        <figure>  <!-- first columns data -->
          <a href="{{ current-theme.img-preview-full }}">
            <img src="{{ current-theme.img-preview-small }}"
            alt="{{ current-theme.img-preview-alt }}" title="{{ current-theme.img-preview-alt }}"></a>
          <figcaption>{{current-theme.title }}</figcaption>
        </figure>
        <a href="{{ current-theme.download-link }}">- DIRECT DOWNLOAD TO PS3</a>
        {% unless current-theme.video-link == '' %}<BR><a href="{{ current-theme.video-link }}" target="_blank">- DEMO VIDEO</a>{% endunless %}
        {% unless current-theme.article-link == '' %}<BR><a href="{{ current-theme.article-link }}">- READ ARTICLE</a>{% endunless %}       
    </td>  
    <td>{% if next-theme %}<center>{{ next-theme.title }}</center>
        <figure>          <!-- second columns data unless previous record was the last.-->
          <a href="{{ next-theme.img-preview-full }}">
            <img src="{{ next-theme.img-preview-small }}"
            alt="{{ next-theme.img-preview-alt }}" title="{{ next-theme.img-preview-alt }}"></a>
          <figcaption>{{ next-theme.title }}</figcaption> <!--   -->
        </figure>
        <a href="{{ next-theme.download-link }}">DIRECT DOWNLOAD TO PS3</a>
        {% unless next-theme.video-link == '' %}<BR><a href="{{ current-theme.video-link }}" target="_blank">DEMO VIDEO</a>{% endunless %}
        {% unless next-theme.article-link == '' %}<BR><a href="{{ current-theme.article-link }}">READ ARTICLE</a>{% endunless %}
        {% endif %}
    </td>
  </tr>
  {% assign next-theme = nil %}
  {% assign iterator = iterator | plus: 2 %}
  {% if iterator >= arraysize %} {% break %} {% endif %}<!-- half the cycles since 2 columns break if +2 is past size -->
  {% endfor %}      <!-- for ps3-theme in site.data.ps3-themes-seasonal -->
</table>

<!--  



#### Halloween
* [Click here to Direct Download from your PS3 Browser. Free Christmas Holiday Theme for PS3](/downloads/ps3-themes/seasonal/HalloweenTheme.p3t)
* [Video Link to our Free Halloween PS3 background Theme](https://www.youtube.com/watch?v=fXLF9XXS7tU){:target="_blank"}
* [Halloween PS3 Theme Details](/2010/10/free-ps3-halloween-theme-from-booya-gadget.html)
<figure>
	<a href="/images/theme-previews/free-halloween-ps3-theme.jpg">
    <img src="/images/theme-previews/free-halloween-ps3-theme-640.jpg" 
         alt="Free Halloween Scary PS3 Theme Preview booya gadget" title="Halloween Scary PS3 theme preview"></a>
	<figcaption>Fear this Scary Pumpkin</figcaption>
</figure>

-->

<BR><BR>

<!-- 

#### SEASONAL PS3 THEMES
<table class=".table">
  <tr><th>Christmas Snowman</th><th>Easter Eggs</th></tr>
  <tr>
    <td>
        <a href="/downloads/ps3-themes/seasonal/HolidayPS3Theme.p3t">DIRECT DOWNLOAD</a> - 
        <a href="https://www.youtube.com/watch?v=MV-KtKg669g">DEMO VIDEO</a> - 
        <a href="/2010/11/free-christmas-happy-holidays-ps3-theme.html">READ ARTICLE TO SEE IF ITs MULTILINE</a>
        <figure>
	      <a href="/images/theme-previews/free-holiday-ps3-theme_booya-gadget.jpg">
          <img src="/images/theme-previews/free-holiday-ps3-theme_booya-gadget-640.jpg" 
            alt="Free Christmas Holiday PS3 Theme Preview booya gadget" title="holiday theme preview"></a>
	      <figcaption>Snowman!</figcaption>
        </figure>
    </td>
    <td><figure>
	        <a href="/images/theme-previews/free-easter-egg-ps3-theme-booya-gadget.jpg">
            <img src="/images/theme-previews/free-easter-egg-ps3-theme-booya-gadget-640.jpg" 
                alt="Free Easter Egg PS3 Theme Preview booya gadget" title="easter theme preview"></a>
	        <figcaption>Cool Eggs for Easter</figcaption>
        </figure>
    </td>
  </tr>
  <tr><th colspan="2">OTHER POPULAR PS3 THEMES</th></tr>
  <tr>
    <td><figure>
	      <a href="/images/theme-previews/free-holiday-ps3-theme_booya-gadget.jpg">
          <img src="/images/theme-previews/free-holiday-ps3-theme_booya-gadget-640.jpg" 
            alt="Free Christmas Holiday PS3 Theme Preview booya gadget" title="holiday theme preview"></a>
	      <figcaption>Snowman!</figcaption>
        </figure>
    </td>
    <td><figure>
	        <a href="/images/theme-previews/free-easter-egg-ps3-theme-booya-gadget.jpg">
            <img src="/images/theme-previews/free-easter-egg-ps3-theme-booya-gadget-640.jpg" 
                alt="Free Easter Egg PS3 Theme Preview booya gadget" title="easter theme preview"></a>
	        <figcaption>Cool Eggs for Easter</figcaption>
        </figure>
    </td>
  </tr>
</table>
-->

<!--    -->


### FREE HOLIDAY/SEASONAL PS3 THEMES
#### Christmas
* [Click here to Direct Download from your PS3 Browser. Free Christmas Holiday Theme for PS3](/downloads/ps3-themes/seasonal/HolidayPS3Theme.p3t)
* [This theme has its own description page here](/2010/11/free-christmas-happy-holidays-ps3-theme.html)
* [Here is an HD video demonstration of this Snowman / Holiday Theme, Happy Holidays](https://www.youtube.com/watch?v=MV-KtKg669g){:target="_blank"}
<figure>
	<a href="/images/theme-previews/free-holiday-ps3-theme_booya-gadget.jpg">
    <img src="/images/theme-previews/free-holiday-ps3-theme_booya-gadget-640.jpg" 
         alt="Free Christmas Holiday PS3 Theme Preview booya gadget" title="holiday theme preview"></a>
	<figcaption>Snowman!</figcaption>
</figure>

#### Easter
* [Click here to Direct Download from your PS3 Browser. Free Easter Egg PS3 Theme](/downloads/ps3-themes/seasonal/PS3EasterEggTheme.p3t)
* [This theme has its own description page here](/2011/03/free-easter-ps3-theme.html)
* [Free Easter Theme PS3 Preview on YouTube](https://www.youtube.com/watch?v=6Ym4nMGlLYA){:target="_blank"}
<figure>
	<a href="/images/theme-previews/free-easter-egg-ps3-theme-booya-gadget.jpg">
    <img src="/images/theme-previews/free-easter-egg-ps3-theme-booya-gadget-640.jpg" 
         alt="Free Easter Egg PS3 Theme Preview booya gadget" title="easter theme preview"></a>
	<figcaption>Cool Eggs for Easter</figcaption>
</figure>

#### Thanksgiving Turkey
* [Click here to Direct Download from your PS3 Browser. Free Easter Egg PS3 Theme](/downloads/ps3-themes/seasonal/FreeThanksgivingPS3Theme.p3t)
* [This theme has its own description page here](/2010/11/free-thanksgiving-theme-for-your-ps3-and-psp.html)
<figure>
	<a href="/images/theme-previews/free-thanksgiving-day-ps3-theme-booya.jpg">
    <img src="/images/theme-previews/free-thanksgiving-day-ps3-theme-booya-640.jpg" 
         alt="Free Thanksgiving PS3 Theme Preview booya gadget November" title="Thanksgiving PS3 theme preview"></a>
	<figcaption>This is a 3d Turkey for you to remember the Pilgrims</figcaption>
</figure>

#### Halloween
* [Click here to Direct Download from your PS3 Browser. Free Christmas Holiday Theme for PS3](/downloads/ps3-themes/seasonal/HalloweenTheme.p3t)
* [Video Link to our Free Halloween PS3 background Theme](https://www.youtube.com/watch?v=fXLF9XXS7tU){:target="_blank"}
* [Halloween PS3 Theme Details](/2010/10/free-ps3-halloween-theme-from-booya-gadget.html)
<figure>
	<a href="/images/theme-previews/free-halloween-ps3-theme.jpg">
    <img src="/images/theme-previews/free-halloween-ps3-theme-640.jpg" 
         alt="Free Halloween Scary PS3 Theme Preview booya gadget" title="Halloween Scary PS3 theme preview"></a>
	<figcaption>Fear this Scary Pumpkin</figcaption>
</figure>

#### Valentines Day
* [Click here to Direct Download from your PS3 Browser. Free Easter Egg PS3 Theme](/downloads/ps3-themes/seasonal/PS3ValentinesDayTheme.p3t)
* [This theme has its own description page here](/2011/01/free-ps3-valentines-day-theme-a-scentsy-offer-cupid-mini.html)
<figure>
	<a href="/images/theme-previews/free-valentines-day-ps3-theme-booya.jpg">
    <img src="/images/theme-previews/free-valentines-day-ps3-theme-booya-640.jpg" 
         alt="Free Valentines Day PS3 Theme booya gadget" title="Valentines Day PS3 theme preview"></a>
	<figcaption>Valentines Day Hearts Showing some Love</figcaption>
</figure>

#### St Patrick's Day Guiness
* [Click here to Direct Download from your PS3 Browser. Free St Patrick's Day Guiness PS3 Theme](/downloads/ps3-themes/seasonal/StPatricksDayPS3Theme.p3t)
* [This theme has its own description page here](/2011/01/free-ps3-valentines-day-theme-a-scentsy-offer-cupid-mini.html)
<figure>
	<a href="/images/theme-previews/free-st-pats-ps3-theme-booya.jpg">
    <img src="/images/theme-previews/free-st-pats-ps3-theme-booya-640.jpg" 
         alt="Free St Patricks Day Guiness PS3 Theme booya gadget" title="Valentines Day PS3 theme preview"></a>
	<figcaption>St Patrick's Day Guiness</figcaption>
</figure>

### GAMES/TV/MOVIE PS3 THEMES
#### TRON
#### Smurfs
* Direct Download Smurfs PS3 Theme for PS3: [XXXX THEME FREE DOWNLOAD](/downloads/ps3-themes/seasonal/The-Smurfs-PS3-Theme-Update.p3t)
<figure>
	<a href="/images/theme-previews/the-smurfs-free-ps3-theme-preview.jpg">
    <img src="/images/theme-previews/the-smurfs-free-ps3-theme-preview.jpg" 
         alt="Free PSP Themes booya gadget" title="xxx ps3 theme"></a>
	<figcaption>Smurfs ps3 theme</figcaption>
</figure>






<BR><BR><BR><BR>
PS3 Theme Install Instructions for PC to PS3 transfer.

Install Quick Steps

  1. Download from BooyaGadget
  2. Place file in a folder, name that folder "Theme"
  3. Place folder "Theme" in another folder named "PS3"
  4. Place all of this on a USB Thumbdrive and plug into your PS3
  5. Under "Settings", select "Theme Settings", and then "Theme".
  6. At the very top, there is an "Install" option, select it.

| A COLUMN          | ANOTHER COLUMN                 |
| :-------------: |:-------------:      |
| Free PS3 Themes | Free PSP Themes     |
| col 2 is        | Free WP7 Wallpapers |


Once you've installed your Theme to your PS3, your theme will now be selectable your "Theme List"

**Enjoy our free selection of free themes for your PSP ! If you like our freebies, [visit our Booya Communication page and visit our other sites today](/booya-communications) !**