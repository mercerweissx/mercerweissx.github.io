---
layout: home
navlink: false
title: home
---
<h1>Welcome to <em>mercerweissx.com</em></h1>
<hr>
<br>
My name is Xavier Mercerweiss; this web log catalogs my personal essays and research projects. 

This website is not a virtual diary. Rather, I intend to sporadically publish complete writings on technology, philosophy, and education as dictated by my interests at any given time.

If you’d like to contact me for any reason, please do! I’d love to hear from you. I can be reached at ___mercerweissx@gmail.com___
<br>
<br>

{% unless site.posts == empty%}
  {% assign latest = site.posts.first %}
  <h1>Latest</h1>
  <hr>
  <br>
  <h2>{{ latest.title }}</h2>
  <p style="color: #828282;">{{ latest.date | date: "%B %-d, %Y"}}</p>
  <p>
    {{ latest.content }}
  </p>
{% endunless %}
