---
permalink: /allPosts/
layout: archive
title: 
published: true
entries_layout: grid
author_profile: false
---
<html>
  <head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
html { height: 100% }
body
{
    margin: 0;
    padding: 0;
    height: 100vh;
    overflow: hidden;
    background-image: url(/assets/images/all-blur2.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center center;
    position: relative;
  
    font-family: "Lato", sans-serif;
}

  .sidenav {
              height: 100%;
              width: 300px;
              position: fixed;
              z-index: 1;
              top: 0;
              left: 0;
              background-color: hsla(0,0%,0%,0.3);
              overflow: auto;
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
   div.content {
              margin-left: 300px; 
              font-size: 28px; 
              padding: 0px 10px;
            }  
    @media screen and (max-width: 700px) {
    .sidenav {
    width: 100%;
    height: auto;
    position: relative;
  }
  .sidenav a {float: left;}
  div.content {margin-left: 0;}
}

@media screen and (max-width: 400px) {
  .sidenav a {
    text-align: center;
    float: none;
  }
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
     
  <div class="content">
  <!--<div class="line-up"></div>
  <div class="line-down"></div> -->
    <div class="entries-{{ page.entries_layout }}">
      {% for post in site.posts limit: 20 %}
        {% include archive-single.html  %}
      {% endfor %}
      
  </div>
  </div>
  </body>
</html>  


