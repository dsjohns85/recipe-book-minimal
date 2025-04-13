---
layout: default
title: Home
---

# Welcome to Daniel's Recipe Book

Here are the recipes:

<ul>
{% for recipe in site.recipes %}
  <li>
    URL: {{ recipe.url }}  
    <br>
    <a href="{{ recipe.url }}">Click to Test Link</a>
  </li>
{% endfor %}
</ul>
