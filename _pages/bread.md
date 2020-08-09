---
layout: recipe
permalink: /bread/
title: Bread
image: bread
---

{% for bread in site.breads %}
<p><a href="{{ site.baseurl }}{{ bread.url }}">{{ bread.title }}</a></p>
{% endfor %}