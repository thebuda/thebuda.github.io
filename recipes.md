---
layout: layout1
title: "A list of recipes"
---
# Recipe Collections

My full list of recipes I've digitized and uploaded.  CUrrently only sorted in alphabetical order.  Nothing fancy, just workable, simple, and printable.

<ul>
  {% for recipes in site.recipes %}
    <li>
      <a href="{{ recipes.url }}">{{ recipes.title }}</a>
    </li>
  {% endfor %}
</ul>