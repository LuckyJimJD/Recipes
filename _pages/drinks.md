---
layout: recipe
permalink: /mains/
title: Main Dishes
image: cassoulet.png
---

{% for drink in site.drinks %}
<p><a href="{{ site.baseurl }}{{ drink.url }}">{{ drink.title }}</a></p>
{% endfor %}