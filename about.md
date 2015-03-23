---
layout: page
permalink: /about/index.html
title: ITMilos Milos Rujevic
tags: [itmlos]
imagefeature: fourseasons.jpg
chart: true
---
<figure>
  <img src="https://raw.githubusercontent.com/itmilos/itmilos.github.io/master/images/itmilos.jpg" alt="itmilos Milos Rujevic">
  <figcaption>itmilos - Milos Rujevic</figcaption>
</figure>

{% assign total_words = 0 %}
{% assign total_readtime = 0 %}
{% assign featuredcount = 0 %}
{% assign statuscount = 0 %}

{% for post in site.posts %}
    {% assign post_words = post.content | strip_html | number_of_words %}
    {% assign readtime = post_words | append: '.0' | divided_by:200 %}
    {% assign total_words = total_words | plus: post_words %}
    {% assign total_readtime = total_readtime | plus: readtime %}
    {% if post.featured %}
    {% assign featuredcount = featuredcount | plus: 1 %}
    {% endif %}
{% endfor %}


Born and raised in Belgrade, Serbia and being dyslexic.. You might think I had a fuck-up live, acctually its the other way around. 

<div align="center">

#This blog has {{ site.posts | size }} posts

##with {{ site.categories | size }} categories

###total words count  {{ total_words }}

####it will take you about <span class="time">{{ total_readtime }}</span> minutes to read. 

#####runs on [jekyll](http://jekyllrb.com/ "Jekyll Bloging Platform") and [github pages](https://pages.github.com "GitHub Pages")

</div>

I am [Drexel Made](http://www.drexel.edu "Drexel University") serb...so I have US degree and SERBIAN heritage.. 
My ultimate goal is to make silicone valley of the blakans here in Belgrade, Serbia.
I am already consulting multiple successful outsourcing business... 

<figure>
	<img src="{{ site.url }}/images/milos-rujevic.jpg" alt="Milos Rujevic">
	<figcaption>At <a href="https://www.google.rs/maps?es_sm=91&q=ada+ciganlija&bav=on.2,or.r_cp.&bvm=bv.88528373,d.ZWU&biw=1429&bih=838&um=1&ie=UTF-8&sa=X&ei=cj8PVbTeM4jsO9GKgJgC&ved=0CAcQ_AUoAg">Ada Ciganlija</a> </figcaption>
</figure>

Born and Raised in Belgrade, Serbia. 

<figure class="half">
	<a href="{{ site.url }}/images/about/4.jpg"><img src="{{ site.url }}/images/about/4-001.jpg"></a>
	<a href="{{ site.url }}/images/about/5.jpg"><img src="{{ site.url }}/images/about/5-001.jpg"></a>
</figure>


I
make
things happen.