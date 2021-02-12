---
layout: default
title: Blog | Seriously, you guys...
header: Blog
description: Ugh! I have no motivation.
permalink: /blog/
---

Welcome to my rants and raves. YMMV.

{% for post in site.posts %}
  <p><a href="{{ post.url }}">{{ post.title }}</a><br>
  {{ post.description }}<br>
  ? {{ post.date | date_to_string }}</p>
{% endfor %}
