---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

For links to preprints see:
* <u><a href= "https://www.researchgate.net/profile/Ronan_Fablet"> My researchgate profile.</a> </a> 
* <u><a href= "https://haltools.archives-ouvertes.fr/Public/afficheRequetePubli.php?idHal=ronan-fablet-all&CB_auteur=oui&CB_titre=oui&CB_article=oui&langue=Anglais&tri_exp=annee_publi&tri_exp2=typdoc&tri_exp3=date_publi&ordre_aff=TA&Fen=Aff&css=../css/VisuRubriqueEncadre.css"> My hal profile.</a> </a> 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
