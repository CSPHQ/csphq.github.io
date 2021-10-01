---
title: "任务"
permalink: /tasks/
---

这里列出的是任务，例如CV、NLP等具体领域的具体任务

<ul class="myposts">
{% for post in site.categories.task %}
    <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title}}</a>
    <span class="postDate">{{ post.date | date: "%b %-d, %Y" }}</span>
    </li>
{% endfor %}
</ul>
