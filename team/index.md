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
{% include list.html data="members" component="portrait" filters="role: intern, group: current" %}
{% include list.html data="members" component="portrait" filters="role: staff, group: current" %}


{% include section.html dark=true %}
{%
  include button.html
  icon="fa-solid fa-user-plus"
  text="Positions"
  link="positions"
  style="button"
%}

{%
  include button.html
  icon="fa-solid fa-camera"
  text="Lab Pictures"
  link="pictures"
  style="button"
%}

{% include section.html %}

## Alumni
{% include list.html data="members" component="portrait" filters="role: postdoc, group: alum" %}
{% include list.html data="members" component="portrait" filters="role: phd, group: alum" %}
{% include list.html data="members" component="portrait" filters="role: ra, group: alum" %}
{% include list.html data="members" component="portrait" filters="role: undergrad, group: alum" %}
{% include list.html data="members" component="portrait" filters="role: intern, group: alum" %}
{% include list.html data="members" component="portrait" filters="role: staff, group: alum" %}

{% capture content %}

{% endcapture %}

{% include grid.html style="square" content=content %}
