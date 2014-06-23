---
layout: index
title: Open Science Codefest 2014
---
{% include JB/setup %}

<div><p>&nbsp</p></div>
<div class="container-fluid">
  <div class="row-fluid">
    <div class="span3 text-box">
      <h4>Design</h4>
      <p>Collaborate with others to conceive, extend, and design software for open science.</p>
    </div>
    <div class="span3 text-box">
      <h4>Code</h4>
      <p>Put ideas into reality in real time. Prototype open source software for science with others.</p>
    </div>
    <div class="span3 text-box">
      <h4>Discuss</h4>
      <p>Explore software needs for environmental science, find solutions to vexing software issues.</p>
    </div>
    <div class="span3 text-box">
      <h4>Analyze</h4>
      <p>Integrate, analyze, and model scientific data to solve pressing environmental issues.</p>
    </div>
  </div>
</div>

<div class="title" id="activities">
  <i class="icon-coffee">
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

<div class="title" id="activities">
  <i class="icon-coffee">
  </i>
  Categories
</div> 
    - Data science
    - Data management
    - Research data analysis
    - Software for modeling and model integration
    - Sustainable software

## Potential Sessions

    - Code for Science hacking groups

        - conceive and hack new projects
        - extend existing systems
        - design new packages

    - Software techniques

        - Intro to {python, Java, R, ...}
        - Version control
        - Software testing

    - Science data management techniques

- [Hotel and Venue](venue)

- [Organizers](organizers)

<div class="title" id="sponsors">
  <i class="icon-coffee">
  </i>
  Sponsors
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
         Logo here.
      </p>
    </div>
    <div class="span3 text-box">
      <p><a href="http://example.com">WSSI</a><br />
         Logo here.
      </p>
    </div>
    <div class="span3 text-box">
      <p><a href="http://example.com">RENCI</a><br />
         Logo here.
      </p>
    </div>
  </div>
</div>

