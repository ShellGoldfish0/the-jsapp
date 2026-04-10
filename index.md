---
layout: default
title: Home
---

# Hello, I'm Jackson

<p class="subtitle">Cyber Student | Gamer</p>

---

## My Mission

I am focused on the intersection of complex systems, critical infrastructure defense, and threat intelligence. When I am not breaking down malware or configuring firewalls, I am diving deep into the intricate lore and challenging mechanics of Destiny 2, Ark, Marathon, Skyrim, Civilization, and More!

### Featured Projects

* **[Project Title 1: Home Lab Setup]** - (Link to Repo)
    * Designed and configured a complete home networking lab running multiple isolated subnets (DMZ, Management, etc.) utilizing pfSense and Proxmox.
* **[Project Title 2: Threat Intelligence Scripting]** - (Link to Repo)
    * Developed Python scripts to pull and process active threat feeds from OpenCTI, automating the generation of IoC lists.

---

### Current Musings (Latest Blog Posts)

Here’s what I’ve been thinking about:

{% assign posts = site.posts | limit: 3 %}
{% for post in posts %}
* [{{ post.title }}]({{ post.url }}) - *{{ post.date | date: "%b %d, %Y" }}*
{% endfor %}