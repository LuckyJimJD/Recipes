---
layout: recipe
permalink: /grains/
title: Dumplings, Noodles, & Rice
image: risotto.jpg
---

{% for grain in site.grains %}
<p><a href="{{ site.baseurl }}{{ grain.url }}">{{ grain.title }}</a></p>
{% endfor %}