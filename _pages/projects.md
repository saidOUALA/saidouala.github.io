---
layout: archive
title: "Research Themes"
permalink: /projects/
author_profile: true
---

* **Generative models and data assimilation:** inverse problems, Bayesian and variational models, data assimilation....
* **Hybrid models:** Coupled data-driven / numerical models, physics-informed machine learning, multi-fidelity modeling....
* **Optimization methods for optimal control problems:** gradient-based and adjoint methods, inexact gradient descent, differentiable programming....
* **Remote sensing and earth system observing systems:** ocean remote sensing, maritime tradic surveillance, space oceanography...

Projects
======
{% include base_path %}
{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}
