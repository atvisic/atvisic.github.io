---
title: Projects
layout: page
---

why is there no title next to the icon..?

<ul>
  {% for post in site.categories.projects %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>