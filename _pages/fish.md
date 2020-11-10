---
layout: recipe
permalink: /fish/
title: Fish 
image: fish.jpg
---

{% for seafood in site.seafoods %}
<p><a href="{{ site.baseurl }}{{ seafood.url }}">{{ seafood.title }}</a></p>
{% endfor %}