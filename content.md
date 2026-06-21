---
title: Content
permalink: /content/
---
<hr style="color: #E8E8E8; height: 1px;">
<br>
<ol reversed>
  {% for post in site.posts %}
    <li>
      {{ post.date | date: "%B %-d, %Y"}}, <strong><a style="color:black;" href="{{ post.url }}">{{ post.title }}</a></strong>: {{ post.description }}
    </li>
  {% endfor %}
</ol>
