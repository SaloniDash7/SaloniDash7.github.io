---
permalink: /allPosts/
layout: archive
title: ALL POSTS
published: true
---
{% for post in site.posts limit: 5 %}
  {% include archive-single.html %}
{% endfor %}