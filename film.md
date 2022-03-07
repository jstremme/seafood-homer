---
layout: page
title: "Film"
category: Film
permalink: /film/
---

{% for post in site.categories.Film %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url | relative_url}}">{{ post.title }}</a></li>
{% endfor %}
