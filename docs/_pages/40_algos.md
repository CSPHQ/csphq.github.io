---
title: "算法"
permalink: /algos/
---

这里列出的是算法，一个算法可能包括多个模型实现

<ul class="myposts">
{% for post in site.categories.algo %}
    <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title}}</a>
    <span class="postDate">{{ post.date | date: "%b %-d, %Y" }}</span>
    </li>
{% endfor %}
</ul>
