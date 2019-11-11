---
title: Miscellaneous
layout: default
---

# Miscellaneous content

Future home of cats and dogs that don't fit nicely in any packages

## Posts and Articles

<ul>
  {% for other in site.other %}
    <li>
      <a href="{{ other.url }}">{{ other.title }}</a> - {{ other.description }}
    </li>
  {% endfor %}
</ul>

## My Twitter Feed

<a class="twitter-timeline" href="https://twitter.com/thebuda?ref_src=twsrc%5Etfw">Tweets by thebuda</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>