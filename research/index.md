---
title: Research
nav:
  order: 1
  tooltip: Projects
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research

Our research seeks to uncover the neural mechanisms underlying learning of complex behaviours.

{% include section.html %}

## Projects

{% capture text %}
Mastering a new skill requires the brain to not only learn which action to enact in a given situation, but also how to improve the quality and precision of a chosen movement to meet a task-specific performance goal. This requires the brain to learn in continuous, often high-dimensional, motor spaces where the number of “choices” is much greater than in decision-making tasks. This is a computationally challenging problem but one at which the brain excels in comparison to artificial agents such as robots. We are investigating the contribution of cortical and basal ganglia circuits to trial-and-error motor learning using a task that trains rats to adapt a simple ballistic movement along a single kinematic dimension. 

{:.left}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  title="How does the brain learn in continuous motor spaces?"
  text=text
%}

{% capture text %}
How the brain learns by trial-and-error is best understood in simple choice tasks. Less is known about how the brain learns in more complex, real-world environments. Faced with a larger array of choices, the brain must employ efficient strategies to explore available options and determine the optimal choice. We have designed multi-choice foraging tasks for rats to uncover these learning strategies and are investigating the role of prefrontal cortex and basal ganglia circuits in their implementation.

{:.right}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  title="How does the brain efficiently solve complex decision-making tasks?"
  text=text
  flip=true
%}

{% capture text %}
Despite its importance to brain development, little is known about the neural basis of play and how it guides plasticity in brain areas responsible for social, cognitive, and motor skills in adulthood. We seek to identify the neural circuits underlying play behaviour during juvenescence and adolescence. We also want to understand the impact of play on development of frontal cortex, an important locus for skilled behaviour, and the neural mechanisms by which play influences later learning in adulthood. 

{:.left}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  title="Development and long-term impact of play behaviour"
  text=text
%}

{% include section.html %}

## Funding

{% capture content %}
  {%
    include figure.html
    image="images/funders/iisc.png"
    caption="IISc Start-up Funds"    
  %}
  {%
    include figure.html
    image="images/funders/serb.png"
    caption="DST SERB"
  %}
{% endcapture %}

{%
  include grid.html
  content=content
  style="square"
%}
