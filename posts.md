---
title: Posts
permalink: /posts/
---

<ol reversed>
  {% for post in site.posts %}
    <li>
      <strong><a style="color:black;" href="{{ post.url }}">{{ post.title }}</a></strong>, {{ post.description }}
    </li>
  {% endfor %}
</ol>
