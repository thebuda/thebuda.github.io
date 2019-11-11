---
layout: layout1
title: "Projects and Experiments"
---

<ul>
  {% for experiments in site.experiments %}
    <li>
      <a href="{{ experiments.url }}">{{ experiments.title }}</a> - {{ experiments.experiment_description }}
    </li>
  {% endfor %}
</ul>