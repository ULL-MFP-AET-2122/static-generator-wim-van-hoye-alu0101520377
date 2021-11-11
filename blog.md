---
layout: single
title: mis publicaciones re Blog
permalink: /blog
toc: true
---

{%- for post in site.categories["blog"]  %}
* [{{post.title}}]({{post.url}})
{% endfor %}