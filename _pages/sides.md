---
layout: recipe
permalink: /sides/
title: Side Dishes
image: brussel_sprouts.png
---

{% for side in site.sides %}
<p><a href="{{ site.baseurl }}{{ side.url }}">{{ side.title }}</a></p>
{% endfor %}