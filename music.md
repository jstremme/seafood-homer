---
layout: page
title: "Music"
permalink: /music/
---

{% for post in site.categories.Music %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
