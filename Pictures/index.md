---
title: Pictures
nav:
  order: 4
  tooltip: Lab Life
---

# {% include icon.html icon="fa-solid fa-camera" %}Lab Pictures

Assorted pictures inside and outside the lab.

{% include section.html %}

{% capture content %}
  {%
    include figure.html
    image="images/lablife/kayaking-manipal-2022.jpg"
    caption="Kayaking in Manipal, 2022"
  %}
  {%
    include figure.html
    image="images/lablife/makalidurga-hike-2023.jpg"
    caption="Hike to Makalidurga, 2023"
  %}
  {%
    include figure.html
    image="images/lablife/open-day-2023-1.jpg"
    caption="IISc Open Day, 2023"
  %}
  {%
    include figure.html
    image="images/lablife/open-day-2023-2.jpg"
    caption="IISc Open Day, 2023"
  %}
  {%
    include figure.html
    image="images/lablife/open-day-2023-3.jpg"
    caption="IISc Open Day, 2023"
  %}
{% endcapture %}

{%
  include grid.html
  content=content
  style="square"
%}
