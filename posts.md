---
title: Content
permalink: /content/
---
<hr>
<br>
<ol reversed>
  {% for post in site.posts %}
    <li>
      <strong>{{ post.date }}, <a style="color:black;" href="{{ post.url }}">{{ post.title }}</a></strong>: {{ post.description }}
    </li>
  {% endfor %}
</ol>
