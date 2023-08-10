---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We are located within the [Centre for Neuroscience](https://cns.iisc.ac.in/) at the [Indian Institute of Science](https://iisc.ac.in/).
{:.center}

{%
  include button.html
  type="email"
  text="Email"
  tooltip="ashesh@iisc.ac.in"
  link="ashesh@iisc.ac.in"
%}
{%
  include button.html
  type="phone"
  text="Phone"
  tooltip="+91(80)22933753"
  link="+91-80-22933753"
%}
{%
  include button.html
  type="address"
  text="Google Maps"
  tooltip="Our location on Google Maps"
  link="https://goo.gl/maps/PBLHGx3p4W6xGYJ79"
%}

{% include section.html %}

### <i class="fa-solid fa-envelopes-bulk"></i>Mailing Address
{:.center}

<div align="center">
Centre for Neuroscience <br>
Indian Institute of Science <br> 
CV Raman Road, Malleswaram <br>
Bangalore 560012 <br> 
India <br>
</div>


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
  image="images/iisc/iisc-main-building.jpg"
  caption="Indian Institute of Science"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

