---
layout: page
title: "Mentores"
permalink: "/mentores/"
header:
    image_fullwidth: "header.png"
---

En el 2020 inauguramos el programa de mentores cuyo fin es conectar 
astronomos en formacion con astronomos avanzados en sus carreras. El programa
esta enfocado en orientas a los estudiantes dutante el proceso de aplicacion a
programas de posgrado en astronomia.  

En esta pagina encontras todo lo relacionado a nuestro programa de mentores.

<ul>
    {% for post in site.categories.mentores %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
