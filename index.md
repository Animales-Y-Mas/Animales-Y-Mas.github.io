---
title: Home
layout: base
---

<div class="blog-post">
    {% for post in site.posts %}
    <a href="{{ post.url | prepend: site.baseurl | prepend: site.url }}">{{ post.title }}</a>
    <h1><i class="fas fa-calendar-alt"></i>{{ post.date }}<h1>
    {% endfor -%}
</div>
