---
layout: default
title: "Alex Milligan's Blog"
---

# Hello, world.
This is my blog.

***
Posts:
<ul>
    {% for post in site.posts %}
<li>
    <a href="{{ post.url }}">{{ post.title }}</a>
</li>
    {% endfor %}
</ul>
