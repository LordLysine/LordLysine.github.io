---
layout: page
title: All Posts
---
## Archive
{% for post in site.posts %}
  <div>
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p>{{ post.date | date_to_string }}</p>
  </div>
{% endfor %}
