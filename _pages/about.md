---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## Recent posts
{% for post in site.posts %}
   - {{ post.date | date_to_string }} » [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}

