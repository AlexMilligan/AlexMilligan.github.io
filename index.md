---
layout: default
title: Alex Milligan
---

# Hello, world.
This is my blog.

<ul>
    {% for post in site.posts %}
<li>
    <a href="{{ post.url }}">{{ post.title }}</a>
</li>
    {% endfor %}
</ul>
