---
title: Staff
date: 2016-12-01 22:49:00 Z
---

<ul>
    {% for person in site.staff %}
    {% unless person.published == false %}
    <li>
        <div class="name">{{ person.title }}</div>
        <div class="role">{{ person.role }}</div>
        <div class="blurb">{{ person.blurb }}</div>
    </li>
    {% endunless %}
    {% endfor %}
</ul>