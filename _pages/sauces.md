---
layout: recipe
permalink: /sauces/
title: Sauces
image: pesto.jpg
---

{% for sauce in site.sauces %}
<p><a href="{{ site.baseurl }}{{ sauce.url }}">{{ sauce.title }}</a></p>
{% endfor %}