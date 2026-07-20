---
layout: home
navlink: false
---
<h1>Welcoe to <em>mercerweissx.com</em></h1>
My name is Xavier Mercerweiss; this web log catalogs my personal essays and research projects. 

This website is not a virtual diary. Rather, I intend to sporadically publish complete writings on technology, philosophy, and education as dictated by my interests at any given time.

If you’d like to contact me for any reason, please do! I’d love to hear from you. I can be reached at ___mercerweissx@gmail.com___
<br>
<br>

{% assign latest = site.posts.first %}
{% if latest %}
  <h1>Latest</h1>
  <h2>{{ latest.title }}</h2>
  <h4><em>{{ latest.date | date: "%B %-d, %Y"}}</em></h4>
  <hr>
{% else %}
  <h1 style="color: red;">No posts!</h1>
{% endif %}
