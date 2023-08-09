---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

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

