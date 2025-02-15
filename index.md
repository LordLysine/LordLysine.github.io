---
layout: default
title: @Lysine's Personal Blog
description: description to be completed...
---

# @Lysine's

welcome to my personal blog! :)

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
