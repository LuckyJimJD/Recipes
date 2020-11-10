---
layout: recipe
permalink: /sauces/
title: Sauces
image: cassoulet.png
---

{% for sauce in site.sauces %}
<p><a href="{{ site.baseurl }}{{ sauce.url }}">{{ sauce.title }}</a></p>
{% endfor %}