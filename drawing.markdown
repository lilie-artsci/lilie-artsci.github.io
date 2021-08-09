---
layout: page
permalink: /drawing/
title: Drawings
---

{% for post in site.categories.drawing %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
