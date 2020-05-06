---
layout: page
title: "Información"
permalink: "/info/"
header:
    image_fullwidth: "header.png"
---

Acá encontrarás información sobre que, quienes y para que existe RECA.

<ul>
    {% for post in site.categories.info %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>