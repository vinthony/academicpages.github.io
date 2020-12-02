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
<!-- <link href="https://fonts.googleapis.com/css?family=Berkshire+Swash" rel="stylesheet"> -->
<link href="https://fonts.googleapis.com/css?family=Stylish" rel="stylesheet">
<!-- <link href="https://fonts.googleapis.com/css?family=Inconsolata&display=swap" rel="stylesheet"> -->

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

<style type="text/css">
  body{
    line-height: 1em;
  }
  a{
    text-decoration: none;
  }
  .post-teaser{
    box-shadow: 3px 0px 3px #ccc;
  }
  a{
    color:#113285;
  }
  .links{
    color: #77428D;
    float: left;
    display: block;
    margin: 0 2px;
  }
  .author b{
    color: #77428D;
  }
</style>

{% include author-profile.html %}

👾 News
======
<ul class="news" style="list-style: none;width: 91%;">
<li>🎉  &nbsp;&nbsp;One paper is accepted by AAAI-21. <div style="float: right;">2020.12 </div> </li>
<li>🎉  &nbsp;&nbsp;One paper is accepted by ECCV 2020. <div style="float: right;">2020.07 </div> </li>
<li>🎉  &nbsp;&nbsp;I will join Huawei Noah's Ark Lab as a research intern. <div style="float: right;">2020.03 </div> </li>
<li>🎉  &nbsp;&nbsp;One paper is accepted by TIP! <div style="float: right;">2020.02 </div> </li>
<li>🎉  &nbsp;&nbsp;One paper is accepted by AAAI-20! <div style="float: right;">2019.11 </div></li>
</ul>

👾 Activities
=======
<ul style="list-style: none;width: 91%;">

<li>🚀 &nbsp;&nbsp;Intern FrondEnd Engineer, <i>Alibaba Group</i>, Hangzhou, China <div style="float: right;">2014.Summer </div></li>
<li>🚀 &nbsp;&nbsp;Intern Algorithm Engineer, <i>HIKVision Research Institute</i>, HangZhou, China <div style="float: right;"><div style="float: right;">2018.Summer </div> </div></li>
<li>🚀 &nbsp;&nbsp;Asian University Machine Learning Camp, <i>Jeju National University</i>, Jeju, Korea <div style="float: right;">2018.Summer</div></li>
<li>🚀 &nbsp;&nbsp;Research Intern, <i>Huawei Noah's Ark Lab</i>, Shenzhen, China <div style="float: right;">2020.3-11 </div></li>
</ul>


👾 Highlight Publications
=======
{% assign sorted_pages = site.publications | sort:"date"| reverse %}
<ul>
{% for post in sorted_pages %}
    {% include archive-single-cv.html %}
{% endfor %}
</ul>


👾 Friends
=======
<ul style="list-style: none;">
<li>👨‍🎓  If you are looking for Machine Tranlation papers, please checkout my friend <a href="https://sunbowliu.github.io/">Xuebo Liu</a>. </li>
</ul>


👾 Achievements
=======
{% include show_achievement.html %}

