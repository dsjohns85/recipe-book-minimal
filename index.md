---
layout: default
title: Home
---

# Welcome to Daniel's Recipe Book

Here are the recipes:

<ul class="recipe-list">
{% for recipe in site.recipes %}
  <li><a href="{{ recipe.url | relative_url }}">{{ recipe.title }}</a></li>
{% endfor %}
</ul>
