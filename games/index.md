---
layout: page
title: The Tower
permalink: /destiny/
---

# Reports from The Tower (Gaming)

Lore analysis, Raid mechanics, and thoughts on the current Destiny 2 meta.

{% for post in site.posts %}
  {% if post.categories contains "games" %}
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
  {% endif %}
{% endfor %}
