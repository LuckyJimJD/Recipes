---
layout: recipe
permalink: /mains/
title: Main Dishes
image: cassoulet.png
---

{% for main in site.mains %}
<p><a href="{{ site.baseurl }}{{ main.url }}">{{ main.title }}</a></p>
{% endfor %}