---
layout: category
title: Research
---
Coming soon!

<div id="archives">
    {% for post in site.categories.research %}
    <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</div>