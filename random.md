---
layout: page
title: "Random"
permalink: /random/
---

{% for post in site.categories.Random %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
