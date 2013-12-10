---
layout: default
---
我的博客
=====
<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a>&nbsp;&raquo;&nbsp;<small>published</small><span>&nbsp;{{ post.date | date_to_string }}</span></li>
  {% endfor %}
</ul>

