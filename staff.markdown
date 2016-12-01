---
title: Staff
date: 2016-12-01 22:49:00 Z
---

<ul class="side-nav">
    {% for page in site.staff %}
    {% unless page.published == false %}
    <li>{{ page.title }}</li>
    {% endunless %}
    {% endfor %}
</ul>