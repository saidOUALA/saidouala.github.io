---
layout: archive
title: "Research Themes"
permalink: /projects/
author_profile: true
---

* **Computer vision and signal processing:** inverse problems, data-driven and learning-based models, texture analysis, motion analysis, bayesian and variational models, data assimilation, ....
* **Applications to marine ecology and oceanography:** ocean remote sensing, maritime tradic surveillance, submeso-to-mesoscale ocean dynamics, movement ecology, fish otoliths, fisheries acoustics, sonar seabed imaging,...

Projects
======
{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}
