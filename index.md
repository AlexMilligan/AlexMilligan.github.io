---
layout: default
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


{% include testing.html %}


{% include yt.html id="dQw4w9WgXcQ" %}

