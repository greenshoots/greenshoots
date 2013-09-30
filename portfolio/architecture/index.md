---
title: "Architectural photos and images - Portfolio"
section: portfolio
layout: default

---

Architecture
======================
{{ site.tags.architecture | size }} items in portfolio.

{% for image in site.tags.architecture %}
<a href="../..{{ image.url }}/"><img src="../../assets/thumbs/{{ image.photo }}" alt="{{ image.title }}" style="margin: 5px" /></a>
{% endfor %}