---
layout: default
title: Blog
---

<h1> Latest posts</h1>

<ul>
    {% for post in site.posts %}
      <li>
          <h2><a href = "{{ post.url }}">{{ post.title }}</a></h2>
      </li>
    {% endfor %}
</ul>