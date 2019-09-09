---
title: Free PS3 Themes
date: 2011-03-04T12:47:06+00:00
author: Booya Gadget
layout: page
search_omit: true
permalink: /free-ps3-themes/
image:
  feature: /images/feature/solar-system-ps3-theme-preview-1280-featured.jpg
# | sort: "download-ct"
---
Enjoy our free selection of free themes for your PS3! This is one of our most popular pages. TRJ compiled all these, some are custom created images, some are basedon popular media.  We make them for ourselves, so we share these PS3 themes with you too.  Enjoy.
* [View our Full Size Preview images on Flickr Booya Gadget](https://www.flickr.com/photos/booyagadget/sets/72157626217451291/){:target="_blank"}

1. TOC
{:toc}

<BR>

#### Seasonal PS3 Themes (total seasonal themes: {{ site.data.ps3-themes-seasonal.size }})
{% for ps3-theme in site.data.ps3-themes-seasonal %}
##### {{ ps3-theme.title }}
* [Download Directly to PS3 Here]({{ site.cdn-url }}{{ site.ps3-theme-download-loc }}seasonal/{{ ps3-theme.download-link }})
{% unless ps3-theme.video-link == '' %}* [YouTube Demo Video]({{ ps3-theme.video-link }}){:target="_blank"}  {% endunless %}
{% unless ps3-theme.article-link == '' %}* [Read our Article Here]({{ ps3-theme.article-link }}){% endunless %}
<figure>
	<a href="{{ site.cdn-url }}{{ site.ps3-theme-preview-img-loc }}{{ ps3-theme.img-preview-full }}">
    <img src="{{ site.cdn-url }}{{ site.ps3-theme-preview-img-loc }}{{ ps3-theme.img-preview-small }}" 
         alt="{{ ps3-theme.img-preview-alt }}" title="{{  ps3-theme.title }}"></a>
	<figcaption>{{ ps3-theme.img-fig-caption }}</figcaption>
</figure>
* * *
{% endfor %}<!-- for ps3-theme in site.data.ps3-themes-seasonal -->

#### More PS3 Themes GAMES/TV/MOVIE/CUSTOM (total additional themes: {{ site.data.ps3-themes-tv-other.size }})
{% for ps3-theme in site.data.ps3-themes-tv-other %}
##### {{ ps3-theme.title }}
* [Download Directly to PS3 Here]({{ site.cdn-url }}{{ site.ps3-theme-download-loc }}{{ ps3-theme.download-link }})
{% unless ps3-theme.video-link == '' %}* [YouTube Demo Video]({{ ps3-theme.video-link }}){:target="_blank"}  {% endunless %}
{% unless ps3-theme.article-link == '' %}* [Read our Article Here]({{ ps3-theme.article-link }}){% endunless %}
<figure>
	<a href="{{ site.cdn-url }}{{ site.ps3-theme-preview-img-loc }}{{ ps3-theme.img-preview-full }}">
    <img src="{{ site.cdn-url }}{{ site.ps3-theme-preview-img-loc }}{{ ps3-theme.img-preview-small }}" 
         alt="{{ ps3-theme.img-preview-alt }}" title="{{  ps3-theme.title }}"></a>
	<figcaption>{{ ps3-theme.img-fig-caption }}</figcaption>
</figure>
* * *
{% endfor %}<!-- for ps3-theme in site.data.ps3-themes-seasonal -->

{% comment %}
#
#  yo
#  Tasdf
#
{% endcomment %}

<BR><BR>
PS3 Theme Install Instructions for PC to PS3 transfer.

**How to install our Custom Themes. EZ**

  1. Using your PS3 Browser, navigate to this page or google search "booya gadget PS3 themes"
  2. Click on the Direct Download hyperlink.
  3. Go to Themes Settings on your PSP
  4. Select your Custom Theme and apply

**Enjoy our free selection of free themes for your PSP ! If you like our freebies, [visit our Booya Communication page and visit our other sites today](/booya-communications) !**