---
layout: default
title: Blog | Seriously, you guys...
header: Blog
description: Welcome to my rants and raves. YMMV.
permalink: /blog/
---
<table class="index">
{% for post in site.posts %}
  <tr><td><span class="arrow">▸</span></td><td><a href="{{ post.url }}">{{ post.title }}</a></td></tr>
  <!--<tr><td></td><td class="post-description">{{ post.description }}</td></tr>-->
  <tr><td></td><td class="date">Published on {{ post.date | date_to_string }}</td></tr>
  <tr class="px1-spacer"><td>&nbsp;</td></tr>
{% endfor %}
</table>
