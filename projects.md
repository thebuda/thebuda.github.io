---
title: Projects and Experiments
---

<ul>
  {% for projects in site.projects %}
    <li>
      <a href="{{ projects.url }}">{{ projects.title }}</a> - {{ projects.description }}
    </li>
  {% endfor %}
</ul>

<ul>
  {% for experiments in site.experiments %}
    <li>
      <a href="{{ experiments.url }}">{{ experiments.title }}</a> - {{ experiments.description }}
    </li>
  {% endfor %}
</ul>