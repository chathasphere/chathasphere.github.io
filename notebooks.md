---
layout: page
title: Notebooks
---
A collection of writings on whatever I'm thinking about.

<div id="archives">
    {% for post in site.categories.notebook %}
    <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</div>