---
title: "文章"
permalink: /blogs/
---

<ul class="myposts">
{% for post in site.categories.blog %}
    <li><a href="{{ post.url }}">{{ post.title}}</a>
    <span class="postDate">{{ post.date | date: "%b %-d, %Y" }}</span>
    </li>
{% endfor %}
</ul>
