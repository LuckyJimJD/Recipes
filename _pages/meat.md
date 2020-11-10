---
layout: recipe
permalink: /meat/
title: Meat Dishes
image: cassoulet.png
---

{% for meat in site.meats %}
<p><a href="{{ site.baseurl }}{{ meat.url }}">{{ meat.title }}</a></p>
{% endfor %}