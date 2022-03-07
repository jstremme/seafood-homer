---
layout: page
title: Film
permalink: /categories/film/
---

{% for post in site.categories.film %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url | relative_url}}">{{ post.title }}</a></li>
{% endfor %}
