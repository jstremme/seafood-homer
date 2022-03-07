---
layout: page
title: "Music"
category: Music
permalink: /categories/music/
---

{% for post in site.categories.Music %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url | relative_url}}">{{ post.title }}</a></li>
{% endfor %}
