---
layout: archive
taxonomy: Machine-Learning
permalink: /categories/ml/
published: true
author_profile: false

---
<html>
  <head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>  
  body {
    background-image: url(/assets/images/ml-blur.jpg); 
    background-position: center center;
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: cover;
    background-color:#464646;
    min-height: 80vh
    } 
 .banner {
            height: 10vh;
            background-image: url(/assets/images/ml-title.png);
            background-repeat: no-repeat;
            background-size: 100% 100%;
            background-position: center center;
            position: relative;
            margin-top: 4vh
        }

  ul.topnav {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: hsla(0,0%,0%,0.6);
  }

  ul.topnav li {float: left;}

  ul.topnav li a {
    display: block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
  }

  ul.topnav li a:hover:not(.active) {hsla(0,0%,0%,0.8)}

  ul.topnav li a.active {color: rgba(48, 227, 202, 0.3);}

  ul.topnav li.right {float: right;}

  @media screen and (max-width: 600px) {
    ul.topnav li.right, 
    ul.topnav li {float: none;}
}

.main
{
  padding-right: 12vw;
  padding-left: 12vw;
}
.postsback
      {
            background-color: hsla(0,0%,0%,0.4);
            padding: inherit;
      }
 
  </style>
</head>

<body>
   <ul class = "topnav">
     <li>  <a href="https://salonidash7.github.io">HOME</a> </li>
     <li> <a href="https://salonidash7.github.io/categories/ml/">MACHINE LEARNING</a> </li>
     <li> <a href="https://salonidash7.github.io/categories/meditations/">MEDITATIONS</a> </li>
       </ul>
     
  <div class="main">
  <div class="banner" > </div>
  <!--<div class="line-up"></div>
  <div class="line-down"></div> -->
  <div class="postsback">
  <div class="entries-{{ page.entries_layout }}">
  {% include posts-category.html taxonomy=page.taxonomy type=page.entries_layout %}
  </div>
  </div>
  </div>
  </body>
</html>  
