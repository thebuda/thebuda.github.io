---
title: Miscellaneous
layout: default
---

# Miscellaneous content

Home of cats and dogs that don't fit nicely in any packages


<ul>
  {% for other in site.other %}
    <li>
      <a href="{{ other.url }}">{{ other.title }}</a> - {{ other.description }}
    </li>
  {% endfor %}
</ul>



