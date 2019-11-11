---
layout: layout1
title: "A list of recipes"
---

<ul>
  {% for recipes in site.recipes %}
    <li>
      <a href="{{ recipes.url }}">{{ recipes.title }}</a>
    </li>
  {% endfor %}
</ul>