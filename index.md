---
layout: default
title: @Lysine's Personal Blog
description: description to be completed...
---

# {{ page.title }} ✨

{{ page.description }}

---

## Latest
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> 
      <small>({{ post.date | date: "%Y-%m-%d" }})</small>
    </li>
  {% endfor %}
</ul>
