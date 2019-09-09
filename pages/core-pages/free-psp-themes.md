---
title: Free PSP Themes
date: 2011-03-04T12:46:53+00:00
author: BooyaTRJ
layout: page
permalink: /free-psp-themes/
---
Enjoy our free selection of free themes for your PSP. Booya TRJ created all of these to use himself, and share with others.

**PSP Custom Theme Instructions**
 1. Use your PSP Browser and navigate to this page or google search "booya gadget psp themes"
 2. Click on the Direct Download hyperlink.
 3. Go to Themes Settings on your PSP
 4. Select your Custom Theme and apply

[You can view our PSP Theme previews on our flickr library here](https://www.flickr.com/photos/booyagadget/albums/72157625157732532){:target="_blank"}

1. TOC
{:toc}


#### PSP Themes (total themes: {{ site.data.psp-themes.size }})
{% for psp-theme in site.data.psp-themes %}
##### {{ psp-theme.title }}
* [Download Directly to PSP Here]({{ site.cdn-url }}{{ site.psp-theme-download-loc }}{{ psp-theme.download-link }})
{% unless psp-theme.video-link == '' %}* [YouTube Demo Video]({{ psp-theme.video-link }}){:target="_blank"}  {% endunless %}
{% unless psp-theme.article-link == '' %}* [Read our Article Here]({{ psp-theme.article-link }}){% endunless %}
<figure>
    <img src="{{ site.cdn-url }}{{ site.psp-theme-preview-img-loc }}{{ psp-theme.img-preview-small }}" 
         alt="{{ psp-theme.img-preview-alt }}" title="{{  psp-theme.title }}">
	<figcaption>{{ psp-theme.img-fig-caption }}</figcaption>
</figure>
* * *
{% endfor %}<!-- for psp-theme in site.data.psp-themes-seasonal -->