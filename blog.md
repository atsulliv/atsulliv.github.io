---
layout: default
title: Blog
permalink: /blog/
---

{% for post in site.posts %}
  <a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}
