---
layout: page
title : Blog
header : Blog
group: navigation
---

<ul class="posts">
  {% for post in site.posts %}
    <li>{{ post.date | date_to_string }} » {{ post.title }}</li>
  {% endfor %}
</ul>
