---
layout: no_foot
permalink: /mains/
title: Main Dishes
---

![]({{ site.baseurl }}/assets/img/cassoulet.png)

{% for main in site.mains %}
<p><a href="{{ site.baseurl }}{{ main.url }}">{{ main.title }}</a></p>
{% endfor %}