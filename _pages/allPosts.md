---
permalink: /allPosts/
layout: archive
title: ALL POSTS
published: true
entries_layout: grid
---
{% for post in site.posts limit: 20 %}
  {% include archive-single.html %}
{% endfor %}

background-image: url(assets/images/all.jpg);
background-position: center center;
background-repeat: no-repeat;
background-attachment: fixed;
background-size: cover;
background-color:#464646;


