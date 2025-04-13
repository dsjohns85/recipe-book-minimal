---
layout: default
title: Home
---

# Welcome to Daniel's Recipe Book

Here are the recipes:

<ul>
  {% for recipe in site.recipes %}
    <li><a href="{{ recipe.url }}">{{ recipe.title }}</a></li>
  {% endfor %}
</ul>
