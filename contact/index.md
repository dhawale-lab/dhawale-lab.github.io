---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We are located within the [Centre for Neuroscience](https://cns.iisc.ac.in/) at the [Indian Institute of Science](https://iisc.ac.in/). 
Ashesh's office is in room A-012 and other lab members work out of B-007 on the ground floor of the CNS building.

{%
  include button.html
  type="email"
  text="ashesh@iisc.ac.in"
  link="ashesh@iisc.ac.in"
%}
{%
  include button.html
  type="phone"
  text="+91(80)2293-3753"
  link="+91-80-22933753"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps"
  link="https://goo.gl/maps/PBLHGx3p4W6xGYJ79"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/iisc/CNS.jpg"
  caption="Centre for Neuroscience"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Indian Institute of Science"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

