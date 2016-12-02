---
title: Staff
date: 2016-12-01 22:49:00 Z
---

<ul>
    {% for person in site.staff %}
    {% unless person.published == false %}
    <li>
        <span class="name">{{ person.title }}</span>
        <span class="role">{{ person.role }}</span>
        <span class="blurb">{{ person.blurb }}</span>
    </li>
    {% endunless %}
    {% endfor %}
</ul>