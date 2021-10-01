---
title: "模型"
permalink: /models/
---

这里列出的是模型，一个算法可能包括到多个模型，因为目标语言、训练数据和配置等不同

<ul class="myposts">
{% for post in site.categories.model %}
    <li>
        <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title}}</a>
    </li>
{% endfor %}
</ul>
