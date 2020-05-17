---
layout: page
title: "Short Stories"
permalink: /short-stories/
---

{% for post in site.categories.Short-Stories %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url | relative_url}}">{{ post.title }}</a></li>
{% endfor %}
