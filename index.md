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

---

# first include test
{% include testing.html %}

# video 1
{% include yt.html id="dQw4w9WgXcQ" %}

# video 2
{% include yt2.html id="dQw4w9WgXcQ" %}
