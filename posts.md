---
title: Posts
permalink: /posts/
---
<hr>
<ol reversed>
  {% for post in site.posts %}
    <li>
      <strong><a style="color:black;" href="{{ post.url }}">{{ post.title }}</a></strong>, {{ post.description }}
    </li>
  {% endfor %}
</ol>
