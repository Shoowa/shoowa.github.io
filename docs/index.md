---
layout: default
---
<ul>
    {% for post in site.posts limit: 5 %}
            <h2><a href="{{ post.url | absolute_url }}">{{ post.title }}</a></h2>
            <p>{{ post.excerpt }}</p><br>
    {% endfor %}
</ul>
