---
layout: page
title: Places
permalink: /categories/places/
---

{% for post in site.categories.places %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url | relative_url}}">{{ post.title }}</a></li>
{% endfor %}
