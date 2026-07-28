---
layout: home
title: Početna
---

Dobrodošli na moju stranicu! Ovdje pratim svoj napredak u 3D printanju i bojanju minijatura.

## Minis
{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})
*Objavljeno: {{ post.date | date: "%d.%m.%Y." }}*
{% endfor %}
