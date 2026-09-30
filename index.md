---
layout: default
title: AK's Notes
---

# AK's Notes

A public place for my thoughts, ideas, and things I'm learning.

Written by AK 💗 ✅

## Thoughts

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url | relative_url }})

{{ post.date | date: "%B %d, %Y" }}

{% endfor %}
