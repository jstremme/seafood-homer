---
layout: page
title: Machine Learning
permalink: /categories/machine-learning/
---

{% for post in site.categories.machine-learning %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url | relative_url}}">{{ post.title }}</a></li>
{% endfor %}
