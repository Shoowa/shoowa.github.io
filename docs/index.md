---
layout: default
---

# Alright, alright, alright

<ul>
    {% for post in site.posts limit: 5 %}
            <h2>{{ post.title }}</h2><br>
            <a href="{{ post.url | absolute_url }}">Read</a><br>
    {% endfor %}
</ul>
