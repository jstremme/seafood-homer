---
layout: page
title: "Poetry"
category: Poetry
permalink: /categories/poetry/
---

{% for post in site.categories.Poetry %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url | relative_url}}">{{ post.title }}</a></li>
{% endfor %}
