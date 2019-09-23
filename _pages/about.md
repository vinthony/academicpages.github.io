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

<link href='http://fonts.font.im/css?family=Bangers' rel='stylesheet' type='text/css'>

<style type="text/css">
  #main{
    margin-top: 0px;
    margin-bottom: 0px;
  }
  .page__inner-wrap{
    padding-left: 20px;
    background-color: #fff;
  }
  .page__footer{
    margin-top: 0px;
  }
	h1,h2,h3,h4,h5,h6{
		font-family: 'Bangers', serif;
    color: #77428D;
	}
	body{
    background-color:#f7f7f7;
    background-image:
    radial-gradient(circle at 100% 150%, #f7f7f7 24%, white 25%, white 28%, #f7f7f7 29%, #f7f7f7 36%, white 36%, white 40%, transparent 40%, transparent),
    radial-gradient(circle at 0    150%, #f7f7f7 24%, white 25%, white 28%, #f7f7f7 29%, #f7f7f7 36%, white 36%, white 40%, transparent 40%, transparent),
    radial-gradient(circle at 50%  100%, white 10%, #f7f7f7 11%, #f7f7f7 23%, white 24%, white 30%, #f7f7f7 31%, #f7f7f7 43%, white 44%, white 50%, #f7f7f7 51%, #f7f7f7 63%, white 64%, white 71%, transparent 71%, transparent),
    radial-gradient(circle at 100% 50%, white 5%, #f7f7f7 6%, #f7f7f7 15%, white 16%, white 20%, #f7f7f7 21%, #f7f7f7 30%, white 31%, white 35%, #f7f7f7 36%, #f7f7f7 45%, white 46%, white 49%, transparent 50%, transparent),
    radial-gradient(circle at 0    50%, white 5%, #f7f7f7 6%, #f7f7f7 15%, white 16%, white 20%, #f7f7f7 21%, #f7f7f7 30%, white 31%, white 35%, #f7f7f7 36%, #f7f7f7 45%, white 46%, white 49%, transparent 50%, transparent);
    background-size: 100px 50px;
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
<li>🚀 Intern FrondEnd Engineer, <i>Alibaba Group</i>, 2014 Summer, Hangzhou, China</li>
<li>🚀 Intern Algorithm Engineer, <i>HIKVision Research Institute</i>, 2018 Summer, HangZhou, China</li>
<li>🚀 Asian University Machine Learning Camp, <i>Jeju National University</i>, 2018 Summer, Jeju, Korea </li>
</ul>

<!-- Work Experience
=======
* Summer 2014: Web FrontEnd Engineer
  * Alibaba Group
  * Duties included: Taobao Moive -->

👾 Publications
=======
{% assign sorted_pages = site.publications | sort:"date"| reverse %}
  <ul style='padding-left:20px'>{% for post in sorted_pages %}
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


👾 Pervious Projects
=======
{% assign sorted_prev = site.teaching | sort:"date" | reverse %}
  <ul style='padding-left:20px'>{% for post in sorted_prev %}
    {% include archive-single-cv-projects.html %}
  {% endfor %}</ul>  


👾 Achievements
=======
{% include show_achievement.html %}
