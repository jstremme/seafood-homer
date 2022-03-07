---
layout: page
title: "Philosophy"
permalink: /philosophy/
---

{% for post in site.categories.Philosophy %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url | relative_url}}">{{ post.title }}</a></li>
{% endfor %}
