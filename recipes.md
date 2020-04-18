---
layout: default
title: "A list of recipes"
---
# Recipe Collections

My full list of recipes I've digitized and uploaded.  Currently only sorted in alphabetical order.  Nothing fancy, just workable, simple, and printable.

<ul>
  {% for recipes in site.recipes %}
    <li>
      <a href="{{ recipes.url }}">{{ recipes.title }}</a>
    </li>
  {% endfor %}
</ul>

Here are also irect links to recipes I go back to again and again with no modification

<ul>
	<li>
		<a href="https://simple-nourished-living.com/wprm_print/44212">The Healthy Mess</a>
	</li>
	<li>
		<a href="https://www.hippressurecooking.com/pressure-cooker-risotto-in-7-minutes/"> Pressure Cooker Risotto </a>
	</li>
</ul>