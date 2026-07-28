---
layout: home
title: Početna
---

Dobrodošli na moju stranicu! Ovdje pratim svoj napredak u 3D printanju i bojanju minijatura.

## Moje Minijature

{/* Ovdje ćemo izlistati tvoje radove */}
{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})
*Objavljeno: {{ post.date | date: "%d.%m.%Y." }}*
{% endfor %}
