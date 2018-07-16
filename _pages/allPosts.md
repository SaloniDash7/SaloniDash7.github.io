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

<style>
html { height: 100% }
body
{
    margin: 0;
    padding: 0;
    height: 100%;
    overflow: auto;
    background-image: url(/assets/images/all.jpg);
    background-repeat: no-repeat;
    background-size: cover;
}
</style>`


