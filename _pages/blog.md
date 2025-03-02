---
title: Blog
permalink: /blog
---

## My Blog Posts

<ul>
  {% for post in site.posts %}
  <li>
    <h3><a href="{{ post.url }}" class="post-preview">{{ post.title }}</a></h3>
    {{ post.excerpt }}
  </li>
  {% endfor %}
</ul>