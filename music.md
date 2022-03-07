---
layout: page
title: Music
permalink: /categories/music/
---

{% for post in site.categories.music %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url | relative_url}}">{{ post.title }}</a></li>
{% endfor %}
