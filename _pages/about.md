---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div style="text-align: justify"> I am a <strong>Professor at <a href="https://www.imt-atlantique.fr">IMT Atlantique</a></strong> and a research scientist at <strong><a href="https://www.lab-sticc.fr">Lab-STICC</a></strong> in the field of <strong>Data Science and Computational Imaging</strong>. I am deeply involved in interdisciplinary research at the <strong>interface between data science and ocean science</strong>, especially space oceanography and marine ecology. My current research interests include <strong>deep learning for dynamical systems and applicationns to the understanding, analysis, simulation and reconstruction of ocean dynamics</strong>, especially using satellite ocean remote sensing data.
<img src="https://github.com/rfablet/rfablet.github.io/images/im_DataWave.jpg" width="384" align ="center">
</div>


## Recent posts
{% for post in site.posts %}
   - {{ post.date | date_to_string }} » [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}

