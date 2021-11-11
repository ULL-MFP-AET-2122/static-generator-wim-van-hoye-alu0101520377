---
layout: single
title: mis publicaciones re docencia
permalink: /docencia
toc: true
---

{%- for post in site.categories["docencia"]  %}
* [{{post.title}}]({{post.url}})
{% endfor %}