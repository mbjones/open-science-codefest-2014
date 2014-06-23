---
layout: index
title: Open Science Codefest 2014
---
{% include JB/setup %}

<div class="title" id="activities">
  <i class="icon-coffee">
  </i>
  Activities
</div> 
- Design
- Code
- Discuss
- Analyze

<div class="title" id="activities">
  <i class="icon-coffee">
  </i>
  Proposed Sessions
</div> 

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

<div class="title" id="activities">
  <i class="icon-coffee">
  </i>
  Conference organization
</div> 

The Codefest will not be run like a typical science confererence, but instead will incorporate elements of an [unconference](http://en.wikipedia.org/wiki/Unconference), with the goal of allowing groups with shared interests to connect organically and to work on projects of mutual interest. The conference will be organized to stimulate productivity and community building, while giving ample opportunities for [ignite talks](http://en.wikipedia.org/wiki/Lightning_talk) that promote communication among participants as activities unfold.

- [Hotel and Venue](venue)

- [Organizers](organizers)

<div class="title" id="sponsors">
  <i class="icon-coffee">
  </i>
  Sponsors
</div> 
    - [ISEES](http://isees.nceas.ucsb.edu)
    - [NCEAS](http://www.nceas.ucsb.edu)
    - WSSI
    - RENCI

