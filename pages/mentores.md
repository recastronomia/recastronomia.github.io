---
layout: page
title: "Mentores"
permalink: "/mentores/"
header:
    image_fullwidth: "header.png"
---

Acá encontrarás todo lo relacionado a nuestro programa de mentores:

<ul>
    {% for post in site.categories.mentores %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>