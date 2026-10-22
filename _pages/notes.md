---
layout: archive
title: "Notes"
permalink: /notes/
---

AI-free writing / Escritura libre de IA. 

{% for post in site.notes %}
  {% include archive-single.html type="list" %}
{% endfor %}
