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
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0">
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

  .sidenav {
      height: 100%;
      width: 0;
      position: fixed;
      z-index: 1;
      top: 0;
      left: 0;
      background-color: hsla(0,0%,0%,0.4);
      overflow-x: hidden;
      transition: 0.5s;
      padding-top: 60px;
  }
  .sidenav a {
      padding: 8px 8px 8px 32px;
      text-decoration: none;
      font-size: 25px;
      color: #f1f1f1;
      display: block;
      transition: 0.3s;
  }
  .sidenav a:hover {
      color:rgba(48, 227, 202, 0.3);
  }
  .sidenav .closebtn {
      position: absolute;
      top: 0;
      right: 25px;
      font-size: 36px;
      margin-left: 50px;
  }
  

@media screen and (max-height: 450px) {
  .sidenav {padding-top: 15px;}
  .sidenav a {font-size: 18px;}
  .main { padding-left: 0vw; padding-right: 0vw; }
}

.main
{
  padding-right: 14vw;
  padding-left: 14vw;
}
.postsback
      {
            background-color: hsla(0,0%,0%,0.4);
            
      }
 
 .menubtn
 {
  margin-left:0;
 }
 
  </style>
</head>

<body>
   <div id = "mySidenav" class = "sidenav">
     <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
     <a href="https://salonidash7.github.io">HOME</a> 
     <a href="https://salonidash7.github.io/categories/ml/">MACHINE LEARNING</a>
     <a href="https://salonidash7.github.io/categories/meditations/">MEDITATIONS</a>
       </div>
  <div id = "menu" class="menubtn">
  <span style="font-size:50px;cursor:pointer;background-color: black; padding: 46px 50px;" onclick="openNav()"><i class="fa fa-bars"></i></span>   
  </div>
  
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
  
  <script>
  function openNav() {
      document.getElementById("mySidenav").style.width = "16vw";
      document.getElementById("main").style.marginLeft = "4vw";
      document.getElementById("menu").style.marginLeft = "12vw";
  }
  function closeNav() {
      document.getElementById("mySidenav").style.width = "0";
      document.getElementById("main").style.marginLeft= "0";
      document.getElementById("menu").style.marginLeft = "12vw";
  }
  </script>
  </body>
</html>  
