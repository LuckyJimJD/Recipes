---
layout: recipe
permalink: /bread/
title: Bread
---

![]({{ site.baseurl }}/assets/img/bread.png)


{% for bread in site.breads %}
<p><a href="{{ site.baseurl }}{{ bread.url }}">{{ bread.title }}</a></p>
{% endfor %}