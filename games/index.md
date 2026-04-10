---
layout: default
title: The Tower
permalink: /destiny/
---

# Reports from The Tower (Gaming)

Lore analysis, Raid mechanics, and thoughts on the current Destiny 2 meta.

{% for post in site.posts %}
  {% if post.category == "destiny" %}
    <div class="post-summary">
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
      <p class="post-meta">{{ post.date | date: "%B %d, %Y" }}</p>
      {{ post.excerpt | strip_html | truncatewords: 30 }}
    </div>
  {% endif %}
{% endfor %}