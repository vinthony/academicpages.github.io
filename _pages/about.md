---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

<style type="text/css">
	h1,h2,h3,h4,h5,h6{
		font-family: 'Berkshire Swash', serif;
	}

</style>

👾 Education
=======
* B.S. in Computer Science, <i>Xidian University</i>, 2011-2015
* M.S. in Computer Science, <i>University of Macau</i>, 2015-2018
* Ph.D in Computer Science, <i>University of Macau</i>, from 2018 Fall 

<!-- Work Experience
=======
* Summer 2014: Web FrontEnd Engineer
  * Alibaba Group
  * Duties included: Taobao Moive -->

👾 Publications
=======
  <ul style='padding-left:20px'>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

👾 Toy Projects
=======
  <ul style='padding-left:20px'>{% for post in site.teaching %}
    {% include archive-single-cv-projects.html %}
  {% endfor %}</ul>  
