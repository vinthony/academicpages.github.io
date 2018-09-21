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
	body{
		font-family: 'Stylish', sans-serif;
	}

i{
  font-weight:bold
}
</style>



👾 Education
=======
<ul style="list-style: none;">
<li>🎓 B.S. in Computer Science, <i>Xidian University</i>, 2011-2015</li>
<li>🎓 M.S. in Computer Science, <i>University of Macau</i>, 2015-2018</li>
<li>🎓 Ph.D in Computer Science, <i>University of Macau</i>, from 2018 Fall </li>
</ul>

👾 Activity
=======
<ul style="list-style: none;">
<li>🚀 FrondEnd Engineer, <i>Alibaba Group</i>, 2014 Summer, Hangzhou, China</li>
<li>🚀 Algorithm Engineer, <i>HikVision Research Institute</i>, 2018 Summer, HangZhou, China</li>
<li>🚀 Asian University Machine Learning Camp, <i>Jeju National University</i>, 2018 Summer, Jeju, Korea </li>
</ul>

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

<div style='padding-left:20px'>
  <div class='activity-item'>
    <div></div>
  </div>
  <div class='activity-item'>
    <div></div>
  </div>
  <div class='activity-item'>
    <div></div>
  </div>
</div>

👾 Toy Projects
=======
  <ul style='padding-left:20px'>{% for post in site.teaching %}
    {% include archive-single-cv-projects.html %}
  {% endfor %}</ul>  

👾 Weight
=======
{% include show_health.html %}

👾 Go to gym?
=======
{% include show_gym.html %}
