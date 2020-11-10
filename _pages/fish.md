---
layout: recipe
permalink: /fish/
title: Fish 
image: fish.png
---

{% for seafood in site.seafoods %}
<p><a href="{{ site.baseurl }}{{ seafood.url }}">{{ seafood.title }}</a></p>
{% endfor %}