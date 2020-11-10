---
layout: recipe
permalink: /soup/
title: Soup
image: soup.jpg
---

{% for soup in site.soups %}
<p><a href="{{ site.baseurl }}{{ soup.url }}">{{ soup.title }}</a></p>
{% endfor %}