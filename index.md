---
layout: index
title: Open Science Codefest 2014
---
{% include JB/setup %}

<div><p>&nbsp</p></div>
<div class="container-fluid">
  <div class="row-fluid">
    <div class="span3 text-box centered">
      <i class="fa fa-lightbulb-o fa-3x"></i>
      <h4>Design</h4>
      <p>Collaborate with others to conceive, extend, and design software for open science.</p>
    </div>
    <div class="span3 text-box centered">
      <i class="fa fa-code fa-3x"></i>
      <h4>Code</h4>
      <p>Put ideas into reality in real time. Prototype open source software for science with others.</p>
    </div>
    <div class="span3 text-box centered">
      <i class="fa fa-comments fa-3x"></i>
      <h4>Discuss</h4>
      <p>Explore software needs for environmental science, find solutions to vexing software issues.</p>
    </div>
    <div class="span3 text-box centered">
      <i class="fa fa-flask fa-3x"></i>
      <h4>Analyze</h4>
      <p>Integrate, analyze, and model scientific data to solve pressing environmental issues.</p>
    </div>
  </div>
</div>

<div class="title" id="sessions">
  <i class="fa fa-coffee">
  </i>
  Sessions
</div> 

The Codefest is [yours to customize, organize, and create](http://en.wikipedia.org/wiki/Unconference), with the goal of allowing groups with shared interests to connect organically and to work on projects of mutual interest. The conference will be organized to stimulate productivity and community building, while giving ample opportunities for collaborative coding and design sessions, [ignite talks](http://en.wikipedia.org/wiki/Lightning_talk) that promote communication among participants as activities unfold, and birds-of-a-feather discussions.

<div class="hidden-phone">
  <ul class="posts">
    {% for post in site.posts limit:15 %}
      <li class="posts-title"><span class="alignleft"><a href="{{ BASE_PATH }}{{ post.url }}"><b>{{ post.title }}</b></a> (<a href="{{ BASE_PATH }}categories#{{ post.category }}-ref">{{ post.category }}</a>)</span> <span class="alignright">{{ post.date | date_to_string }}</span></li>
    {% endfor %}
  </ul>
</div>

<div class="title" id="categories">
  <i class="fa fa-sitemap">
  </i>
  Session Categories
</div> 
<div>
    <p>Sessions are categorized into the type of activity involved, and we expect sessions in Data Science, Coding, Design, Discussion, Lightning talks, and others.  We envision sessions covering data science, data management, research data analysis, software for modeling, model coupling, and data-model integration.  Whether you are into [R](http://r-project.org), [scietific python](http://python.org), or any other language, we expect many Code for Science hacks, where people can conceive of and prototype new science software, extend existing systems, and design new packages. The current types of activities currently are:
    <ul class="tag_box inline">
      {% assign categories_list = site.categories %}
      {% include JB/categories_list %}
    </ul>
</div>

<div class="title" id="sponsors">
  <i class="fa fa-university">
  Sponsors
  </i>
</div> 
<div class="container-fluid">
  <div class="row-fluid">
    <div class="span3 text-box">
      <p><a href="http://isees.nceas.ucsb.edu">ISEES</a><br />
         Logo here.
      </p>
    </div>
    <div class="span3 text-box">
      <p><a href="http://www.nceas.ucsb.edu">NCEAS</a><br />
          <img src="{{ HOME_PATH }}assets/img/logo-nceas-white.png" />
      </p>
    </div>
    <div class="span3 text-box">
      <p><a href="http://example.com">WSSI</a><br />
         Logo here.
      </p>
    </div>
    <div class="span3 text-box">
      <p><a href="http://example.com">RENCI</a><br />
      </p>
    </div>
  </div>
</div>

