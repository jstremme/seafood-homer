---
layout: page
title: "Data Science"
permalink: /data-science/
---

{% for post in site.categories.Data-Science %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
