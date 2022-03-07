---
layout: page
title: Short Stories
permalink: /categories/short-stories/
---

{% for post in site.categories.short-stories %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url | relative_url}}">{{ post.title }}</a></li>
{% endfor %}
