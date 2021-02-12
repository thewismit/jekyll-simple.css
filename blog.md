---
layout: default
title: Blog | Seriously, you guys...
header: Blog
description: Welcome to my rants and raves. YMMV.
permalink: /blog/
---

{% for post in site.posts %}
  <p><a href="{{ post.url }}">{{ post.title }}</a><br>
  {{ post.description }}<br>
  ? {{ post.date | date_to_string }}</p>
{% endfor %}
