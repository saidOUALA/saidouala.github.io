---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div style="text-align: justify"> I am a **Professor at <a href="https://www.imt-atlantique.fr">IMT Atlantique</a>** and a research scientist at **<a href="https://www.lab-sticc.fr">Lab-STICC</a>** in the field of **Data Science and Computational Imaging**. I am deeply involved in interdisciplinary research at the **interface between data science and ocean science**, especially space oceanography and marine ecology. My current research interests include **deep learning for dynamical systems and applicationns to the understanding, analysis, simulation and reconstruction of ocean dynamics**, especially using satellite ocean remote sensing data.</div>


## Recent posts
{% for post in site.posts %}
   - {{ post.date | date_to_string }} » [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}

