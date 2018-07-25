---
title: 
layout: archive
permalink: /categories/meditations/
taxonomy: Meditations
published: true
author_profile: false
entries_layout: grid
---
<html>
  <head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style> 
  html { height: 100% } 
  body {
    margin: 0; 
    padding: 0; 
    height: 100%; 
    overflow: hidden; 
    background-image: url(/assets/images/meditations-blur-2.jpg); 
    background-repeat: no-repeat; 
    background-size: cover; 
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
   .line-up {
        height:0px;
        width:1px;
        border-bottom:3px solid #010326;
        position: absolute;
        left: 38%;
        top: 7%;
        -webkit-animation: increase 3s;
        -moz-animation:    increase 3s; 
        -o-animation:      increase 3s; 
        animation:         increase 3s; 
        animation-fill-mode: forwards;
      }

  .line-down {
    height:0px;
    width:1px;
    border-bottom:3px solid #010326;
    position: absolute;
    right: 30%;
    top: 18%;
    -webkit-animation: increase 3s;
    -moz-animation:    increase 3s; 
    -o-animation:      increase 3s; 
    animation:         increase 3s; 
    animation-fill-mode: forwards;
    animation-direction: backwards;
  }

  @keyframes increase {
  100% {
      width: 590px;
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
     
  <div class="main">
    <div class="entries-{{ page.entries_layout }}">
  {% include posts-category.html taxonomy=page.taxonomy type=page.entries_layout %}
</div>
  </div>
  </body>
</html>  
