---
layout: default
title: The Tower
permalink: /games/
---

# Welcome to The Tower

This is my gaming blog. If the build works, you will see this text.

{% for post in site.posts %}
  {% if post.categories contains "games" %}
  * [{{ post.title }}]({{ post.url | relative_url }})
  {% endif %}
{% endfor %}
