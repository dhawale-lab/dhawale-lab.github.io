---
title: Team
nav:
  order: 3
  tooltip: People
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our team comprises an interdisciplinary group of researchers with diverse backgrounds. 

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: current" %}
{% include list.html data="members" component="portrait" filters="role: phd, group: current" %}
{% include list.html data="members" component="portrait" filters="role: ra, group: current" %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: current" %}

{% include section.html background="images/lab.jpg" dark=true %}

{% include section.html %}

## Alumni
{% include list.html data="members" component="portrait" filters="group: alum" style="small" %}

{% capture content %}

{% endcapture %}

{% include grid.html style="square" content=content %}
