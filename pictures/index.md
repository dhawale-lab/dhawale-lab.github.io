---
title: Pictures
---

# {% include icon.html icon="fa-solid fa-camera" %}Lab Pictures

Assorted pictures inside and outside the lab.

{% include section.html %}

{% capture content %}
  {%
    include figure.html
    image="images/lablife/kayaking-manipal-2022.jpg"
    caption="Kayaking in Manipal, 2022"
    link="images/lablife/kayaking-manipal-2022.jpg"
  %}
  {%
    include figure.html
    image="images/lablife/makalidurga-hike-2023.jpg"
    caption="Hike to Makalidurga, 2023"
    link="images/lablife/makalidurga-hike-2023.jpg"
    
  %}
  {%
    include figure.html
    image="images/lablife/lab-dinner-2023.jpg"
    caption="Lab dinner, March 2023"
    link="images/lablife/lab-dinner-2023.jpg"
    
  %}
  {%
    include figure.html
    image="images/lablife/open-day-2023-1.jpg"
    caption="IISc Open Day, 2023"
    link="images/lablife/open-day-2023-1.jpg"
  %}
  {%
    include figure.html
    image="images/lablife/open-day-2023-2.jpg"
    caption="IISc Open Day, 2023"
    link="images/lablife/open-day-2023-2.jpg"
  %}
  {%
    include figure.html
    image="images/lablife/open-day-2023-3.jpg"
    caption="IISc Open Day, 2023"
    link="images/lablife/open-day-2023-3.jpg"
  %}
  {%
    include figure.html
    image="images/lablife/rishika-surgery.jpg"
    link="images/lablife/rishika-surgery.jpg"
  %}
{% endcapture %}

{%
  include grid.html
  content=content
  style="square"
%}
