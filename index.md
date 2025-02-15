---
layout: default
title: HOME
---

# {{ site.title }} 📝

{{ site.description }}

---

## Latest
{% for post in site.posts limit:5 %}
  <div class="post-preview">
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <small>{{ post.date | date: "%Y-%m-%d" }}</small>
    <p>{{ post.excerpt | strip_html | truncate: 100 }}</p>
  </div>
{% endfor %}

[See All Posts →](/archive)
