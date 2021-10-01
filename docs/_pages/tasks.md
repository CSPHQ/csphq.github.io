---
title: "任务"
permalink: /tasks/
---

<ul class="myposts">
{% for post in site.categories.task %}
    <li><a href="{{ post.url }}">{{ post.title}}</a>
    <span class="postDate">{{ post.date | date: "%b %-d, %Y" }}</span>
    </li>
{% endfor %}
</ul>
