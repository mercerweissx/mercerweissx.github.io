---
title: Content
layout: page
permalink: /content/
navlink: true
---
<ol reversed>
  {% for post in site.posts %}
    <li>
      {{ post.date | date: "%B %-d, %Y" }}, <strong><a href="{{ post.url }}">{{ post.title }}</a></strong>: {{ post.description }}
    </li>
  {% endfor %}
</ol>
