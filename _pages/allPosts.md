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
