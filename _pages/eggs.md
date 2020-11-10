---
layout: recipe
permalink: /eggs/
title: Eggs
image: shakshuka.jpg
---

{% for egg in site.eggs %}
<p><a href="{{ site.baseurl }}{{ egg.url }}">{{ egg.title }}</a></p>
{% endfor %}