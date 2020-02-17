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
<link href="https://fonts.googleapis.com/css?family=Inconsolata&display=swap" rel="stylesheet">

<style type="text/css">
  #main{
    margin-top: 0px;
    margin-bottom: 0px;
    background:#fff;
    /* box-shadow: 0px 10px 10px #aaa; */
    padding:20px;
    width:1060px;
  }
  .page{
    width:100%;
  }
  .page__inner-wrap{
    background-color: #fff;
  }
  .page__footer{
    margin-top: 0px;
  }
  .news{
    color: #77428D;
  }
	h1,h2,h3,h4,h5,h6{
		font-family: 'Stylish', serif;
    font-weight:bolder;
    color: #77428D;
    margin-bottom:0px;
	}
	body{
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
h1 ul{
  margin: 5px 0px;
  padding-left:0px;
  margin-bottom:30px;
}
</style>
{% include author-profile.html %}

👾 News
======
<ul class="news" style="list-style: none;">
<li>🎉 [2020.02] One paper is accepted by TIP!</li>
<li>🎉 [2019.11] One paper is accepted by AAAI-20!</li>
</ul>

👾 Activities
=======
<ul style="list-style: none;">
<li>🚀 Intern FrondEnd Engineer, <i>Alibaba Group</i>, 2014 Summer, Hangzhou, China</li>
<li>🚀 Intern Algorithm Engineer, <i>HIKVision Research Institute</i>, 2018 Summer, HangZhou, China</li>
<li>🚀 Asian University Machine Learning Camp, <i>Jeju National University</i>, 2018 Summer, Jeju, Korea </li>
</ul>


👾 Highlight Publications
=======
{% assign sorted_pages = site.publications | sort:"date"| reverse %}
<ul>
{% for post in sorted_pages %}
    {% include archive-single-cv.html %}
{% endfor %}
</ul>



👾 Other Projects
=======
{% assign sorted_prev = site.teaching | sort:"date" | reverse %}
<ul>
{% for post in sorted_prev %}
    {% include archive-single-cv-projects.html %}
{% endfor %}
</ul>  

👾 Visitors
=======
{% include show_earth.html %}

👾 Achievements
=======
{% include show_achievement.html %}

