---
layout: home
navlink: false
---
# Welcome to _mercerweissx.com_
My name is Xavier Mercerweiss; this web log catalogs my personal essays and research projects. 

This website is not a virtual diary. Rather, I intend to sporadically publish complete writings on technology, philosophy, and education as dictated by my interests at any given time.

If you’d like to contact me for any reason, please do! I’d love to hear from you. I can be reached at ___mercerweissx@gmail.com___
<br>

# Latest Post
{% assign latest = site.posts.first %}
<h2>{{ latest.title }}</h2>
<h4><em>{{ latest.date | date: "%B %-d, %Y"}}</em></h4>
