---
layout: single
title: Mis peliculas favoritas
permalink: /peliculas
toc: true
---

{%- for post in site.categories["peliculas"]  %}
* [{{post.title}}]({{post.url}})
{% endfor %}
