---
permalink: /
title: "Just a P.hD. student."
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

#Publications

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
