---
title: Projects and Experiments
layout: default
---

There's nothing more dangerous than an engineer with time on his hands.  Here are some things I've been working on:

*I am still in the process of moving files over from my old site, so check back later for a more complete listing.* 

## Projects
<ul>
  {% for projects in site.projects %}
    <li>
      <a href="{{ projects.url }}">{{ projects.title }}</a> - {{ projects.description }}
    </li>
  {% endfor %}
</ul>
## Exerpiments
<ul>
  {% for experiments in site.experiments %}
    <li>
      <a href="{{ experiments.url }}">{{ experiments.title }}</a> - {{ experiments.description }}
    </li>
  {% endfor %}
</ul>