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
    box-shadow: 0px 10px 10px #aaa;
    background-color: #ccc;
    padding-right: 0px;
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
    background-color:black;
		font-family: 'Stylish', sans-serif;
	}
  .page{
    padding: 0px;
  }
  .page__meta{
    margin-top: 0px;
  }
  .page__footer{
    background-color: #333;
    border: none;
  }
  .page__title{
    margin:0;
  }
  .sidebar{
    margin:0 auto;
  }

i{
  font-weight:bold
}
</style>

<h1 style="padding-top: 20px;">👾 Education </h1>
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


👾 Highlight Publications
=======
{% assign sorted_pages = site.publications | sort:"date"| reverse %}
  <ul style='padding-left:20px'>{% for post in sorted_pages %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>



👾 Other Projects
=======
{% assign sorted_prev = site.teaching | sort:"date" | reverse %}
  <ul style='padding-left:20px'>{% for post in sorted_prev %}
    {% include archive-single-cv-projects.html %}
  {% endfor %}</ul>  


👾 Achievements
=======
{% include show_achievement.html %}
