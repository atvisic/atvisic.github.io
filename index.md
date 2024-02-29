---
layout: default
title: "Home"
---


**currently, the home page shows latest posts from any category**

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}
