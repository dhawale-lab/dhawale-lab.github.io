---
title: Lab Life
nav:
  order: 4
  tooltip: Pictures
---

# {% include icon.html icon="fa-solid fa-feather-pointed" %}Lab Life

Assorted pictures of life inside and outside the lab.

{% include section.html %}

{% capture content %}
  {%
    include figure.html
    image="images/group-photo.jpg"
    caption="The team at our annual Christmas party, 2025"
  %}
  
  {% include figure.html ... %}
  {% include figure.html ... %}
  {% include figure.html ... %}
  {% include figure.html ... %}
  {% include figure.html ... %}
{% endcapture %}

{%
  include grid.html
  content=content
  style="square"
%}