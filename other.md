---
title: Miscellaneous
layout: default
---

# Miscellaneous content

Future home of cats and dogs that don't fit nicely in any packages

<ul>
  {% for projects in other.other %}
    <li>
      <a href="{{ other.url }}">{{ other.title }}</a> - {{ other.description }}
    </li>
  {% endfor %}
</ul>