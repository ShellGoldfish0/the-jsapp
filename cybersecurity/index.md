---
layout: page
title: Cybersecurity Blog
permalink: /cybersecurity/
---

# Cybersecurity Analysis & Research

This space is dedicated to technical deep-dives, reflections on my studies, and industry trends.

{% for post in site.posts %}
  {% if post.category == "cyber" %}
    <div class="post-summary">
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
      <p class="post-meta">{{ post.date | date: "%B %d, %Y" }}</p>
      {{ post.excerpt | strip_html | truncatewords: 30 }}
    </div>
  {% endif %}
{% endfor %}
