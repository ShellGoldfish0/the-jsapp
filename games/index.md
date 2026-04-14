---
layout: default
title: The Tower
permalink: /games/
---

# Welcome to The Tower

This is the gaming blog. Check out some posts on Destiny 2

{% for post in site.posts %}
  {% if post.categories contains "games" %}
  * [{{ post.title }}]({{ post.url | relative_url }})
  {% endif %}
{% endfor %}
