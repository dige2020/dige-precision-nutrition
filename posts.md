---
layout: default
title: 文章列表
---

<h1>文章列表</h1>

<ul>
{% for post in site.posts %}
  <li>
    <h3><a href="{{ site.baseurl }}/posts/{{ post.title | slugify }}/">{{ post.title }}</a></h3>
    <p class="date">{{ post.date | date: "%Y-%m-%d" }}</p>
    <p>{{ post.excerpt | strip_html | truncate: 100 }}</p>
  </li>
{% endfor %}
</ul>
