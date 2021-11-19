---
layout: single
title: mis publicaciones re educación
permalink: /educacion
toc: true
---

{%- for post in site.categories["educacion"]  %}
* [{{post.title}}]({{post.url}})
{% endfor %}