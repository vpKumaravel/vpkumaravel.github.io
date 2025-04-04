---
layout: default
title: Blogs
permalink: /blogs/
---

# Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <strong><a href="{{ post.url }}">{{ post.title }}</a></strong><br/>
      <small>{{ post.date | date: "%B %d, %Y" }}</small><br/>
      {{ post.excerpt }}
    </li>
    <hr/>
  {% endfor %}
</ul>

