---
layout: page
title: data-science
---

<h4>Posts Related To Data Science:</h4>

<ul>
{% for post in site.categories.data-science %}
    <li>{{ post.date | date: '%b %d, %Y' }} - <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
