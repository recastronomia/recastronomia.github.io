---
layout: page
title: "Recursos"
permalink: "/recursos/"
header:
    image_fullwidth: "header.png"
---

Acá encontrarás escuelas, programas, videos, ofertas laborales y más...

<ul>
    {% for post in site.categories.recursos %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>