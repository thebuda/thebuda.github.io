---
title: "A list of recipes"
---

<ul>
  {% for exeriments in site.experiments %}
    <li>
      <a href="{{ experiments.url }}">{{ experiments.title }}</a>
    </li>
  {% endfor %}
</ul>