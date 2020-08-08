---
layout: recipe
permalink: /sweets/
title: Sweets
---

![]({{ site.baseurl }}/assets/img/caneles.png)

{% for sweet in site.sweets %}
<p><a href="{{ site.baseurl }}{{ sweet.url }}">{{ sweet.title }}</a></p>
{% endfor %}