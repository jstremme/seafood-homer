---
layout: page
title: Philosophy
permalink: /categories/philosophy/
---

{% for post in site.categories.philosophy %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url | relative_url}}">{{ post.title }}</a></li>
{% endfor %}
