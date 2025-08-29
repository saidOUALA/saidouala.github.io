---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div style="text-align: justify"> 

I am a <strong>Tenure-Track Professor (Chaire Professeur Junior) at <a href="https://www.imt-atlantique.fr">IMT Atlantique</a></strong> and a research scientist at <strong><a href="https://www.lab-sticc.fr">CNRS UMR-6285</a></strong></a></strong> and the <strong><a href="https://team.inria.fr/odyssey/">INRIA Odyssey team</a></a></strong>. My research focuses on leveraging data science, artificial intelligence, and computational methods to advance Earth system modeling. This includes developing new observational products, designing data assimilation techniques, and building predictive models that integrate physical knowledge with machine learning. My work aims to enhance the understanding and prediction of extreme events in the ocean, atmosphere, and climate.
  
## Recent posts
{% for post in site.posts %}
   - {{ post.date | date_to_string }} » [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}

