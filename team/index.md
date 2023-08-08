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
{% include list.html data="members" component="portrait" filters="role: postdoc" %}
{% include list.html data="members" component="portrait" filters="role: phd, group: " %}
{% include list.html data="members" component="portrait" filters="role: ra, group: " %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: " %}

{% include section.html background="images/lab.jpg" dark=true %}

{% include section.html %}

Alumni
{% include list.html data="members" component="portrait" filters="role: postdoc, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: phd, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: ra, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: alum" style="small" %}

{% capture content %}

{% endcapture %}

{% include grid.html style="square" content=content %}
