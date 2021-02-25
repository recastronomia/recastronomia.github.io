---
layout: page
title: "Recursos"
permalink: "/recursos/"
header:
    image_fullwidth: "header.png"
---

Acá encontrarás recursos muy útiles para tu carrera en astronomía. Escuelas de verano, pasantías, programas de pregrado y posgrados, ofertas laborales y consejos. 


<ul>
    {% for post in site.categories.recursos %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
