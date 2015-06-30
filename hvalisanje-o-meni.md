---
layout: page
permalink: /hvalisanje-o-meni/index.html
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


Pre svega miran, fin, tih i povučen dečak sa [Vračara](http://www.volimvracar.rs/). 

Hajde da promenimo Srbiju jedan po jedan piksel. 


#Ovaj blog ima {{ site.posts | size }} postova

##sa {{ site.categories | size }} kategorija

### ukupno reči  {{ total_words }}

####trebaće Vam cirka <span class="time">{{ total_readtime }}</span> minuta da sve pročitate.

#####pokreće ga [jekyll](http://jekyllrb.com/ "Jekyll Bloging Platform") i [github pages](https://pages.github.com "GitHub Pages")


###A sada pravac u [Mikser](http://house.mikser.rs/)
<figure>
	<a href="{{ site.url }}/images/about/4.jpg"><img src="{{ site.url }}/images/about/hipster-uplatnica.jpg"  alt="hipster uplatnica"></a>
</figure>