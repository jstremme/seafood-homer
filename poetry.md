---
layout: page
title: "Poetry"
permalink: /poetry/
---

{% for post in site.categories.Poetry %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
