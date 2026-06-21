---
title: Posts
permalink: /posts/
---

<ol>
  {% for post in site.posts %}
    <li>
      <strong><a href="{{ post.url }}">{{ post.title }}</a></strong>, {{ post.description }}
    </li>
  {% endfor %}
</ol>
