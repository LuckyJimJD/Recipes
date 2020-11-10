---
layout: recipe
permalink: /drinks/
title: Drinks
image: apple-kvass.jpg
---

{% for drink in site.drinks %}
<p><a href="{{ site.baseurl }}{{ drink.url }}">{{ drink.title }}</a></p>
{% endfor %}