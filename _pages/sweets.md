---
layout: recipe
permalink: /sweets/
title: Sweets
image: canneles.png
---

{% for sweet in site.sweets %}
<p><a href="{{ site.baseurl }}{{ sweet.url }}">{{ sweet.title }}</a></p>
{% endfor %}