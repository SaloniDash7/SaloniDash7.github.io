---
title: 
layout: archive
taxonomy: Machine-Learning
classes: wide
permalink: /categories/ml/
feature_row1:
  - image_path: assets/images/all-rs.jpg
    alt: "THEORY"
    title: "THEORY"
    excerpt: "THEORETICAL POSTS"
    url: /allPosts/
    btn_label: "VISIT"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/meditations-rs.jpg
    alt: "CODE"
    title: "JUST SHOW ME THE CODE"
    excerpt: "PRACTICAL STUFF"
    url: /categories/meditations/
    btn_label: "VISIT"
    btn_class: "btn--primary"
published: true
author_profile: false

---
<html>
  <head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style> 
  html { height: 100% } 
  body 
  { 
  background-image: url(/assets/images/ml-blur.jpg) ;
  background-position: center center;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
  background-color:#464646;
  height: 100vh;
    }
  #banner {
            height: 10vh;
            background-image: url(/assets/images/ml-title.png);
            background-repeat: no-repeat;
            background-size: 60% 95%;
            background-position: center center;
            position: relative;
        }
  .sidenav {
              height: 100%;
              width: 300px;
              position: fixed;
              z-index: 1;
              top: 0;
              left: 0;
              background-color: hsla(0,0%,0%,0.3);
              overflow-x: hidden;
              transition: 0.5s;
              padding-top: 20px;
          }
          
   .sidenav a {
              padding: 8px 8px 8px 32px;
              text-decoration: none;
              font-size: 25px;
              color:#f1f1f1 ;
              display: block;
              transition: 0.3s;
          }
          
   .sidenav a:hover {
              color: rgba(48, 227, 202, 0.3);
          }
   .main {
              margin-left: 300px; 
              font-size: 28px; 
              padding: 0px 10px;
            }  
   
  </style>
</head>

<body>
   <div id="mySidenav" class="sidenav">
     <a href="https://salonidash7.github.io/#">HOME</a>
     <a href="https://salonidash7.github.io/allPosts/">ALL</a>
     <a href="https://salonidash7.github.io/categories/meditations/">MEDITATIONS</a>
     <a href="https://salonidash7.github.io/categories/ml/">MACHINE LEARNING</a>
        </div>
     
  <div class="main">
  <div id="banner"> </div>
  <!--{% include feature_row id="feature_row1" type="right" %}
  {% include feature_row id="feature_row2" type="left" %} -->
  {% include posts-category.html taxonomy=page.taxonomy type=page.entries_layout %} 
  
  </div>
  </body>
</html>  
    
