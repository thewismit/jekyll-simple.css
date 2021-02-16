---
title: Seriously, you guys... {}
header: Seriously, you guys... {}
description: A fantastical idiot's rantings and ravings.
permalink: /
layout: default
---
<table class="index">
{% for post in site.posts %}
  <tr><td><span class="arrow">▸</span></td><td><a href="{{ post.url }}">{{ post.title }}</a></td></tr>
  <tr><td></td><td class="post-description">{{ post.description }}</td></tr>
  <tr><td></td><td class="date">Published on {{ post.date | date_to_string }}</td></tr>
  <tr><td>&nbsp;</td></tr>
{% endfor %}
</table>

<a rel="me" href="https://psynergy.io/@thewismit"></a>
