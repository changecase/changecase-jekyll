---
layout: default
title: posts
---

Posts
=====

Blog posts on this site.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>