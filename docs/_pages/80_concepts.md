---
title: "概念"
permalink: /concepts/
---

这里列出的是一些概念，类似百科或者wiki

<ul class="myposts">
{% for post in site.categories.concept %}
    <li>
        <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title}}</a>
    </li>
{% endfor %}
</ul>
