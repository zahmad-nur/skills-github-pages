---
layout: default
title: Home
---

# Welcome

## Blog Posts
Number of posts: {{ site.posts.size }}
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
