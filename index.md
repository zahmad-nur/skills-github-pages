---
layout: default
title: Zahra Ahmads CV Blog
email: zahra.nur.ahmad@outlook.com
---
<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> — {{ post.date | date_to_string }}
    </li>
  {% endfor %}
</ul>
---
