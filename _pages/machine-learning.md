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
  body 
  { 
  background-image: url(/assets/images/ml-blur.jpg) ;
  background-position: center center;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
  background-color:#464646;
  min-height: 80vh
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
    width: 0;
    position: fixed;
    z-index: 1;
    top: 0;
    left: 0;
    background-color: hsla(0,0%,0%,0.3);
    overflow-x: hidden;
    transition: 0.5s;
    padding-top: 60px;
}
.sidenav a {
    padding: 8px 8px 8px 32px;
    text-decoration: none;
    font-size: 25px;
    color: #818181;
    display: block;
    transition: 0.3s;
}
.sidenav a:hover {
    color: #f1f1f1;
}
.sidenav .closebtn {
    position: absolute;
    top: 0;
    right: 25px;
    font-size: 36px;
    margin-left: 50px;
}
.main {
              margin-left: 30vh; 
              font-size: 4vh; 
              padding: 0px 10px;
            }  
@media screen and (max-height: 450px) {
  .sidenav {padding-top: 15px;}
  .sidenav a {font-size: 18px;}
}
  </style>
</head>

<body>
   
   <div id="mySidenav" class="sidenav">
     <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
     <a href="https://salonidash7.github.io/#">HOME</a>
     <a href="https://salonidash7.github.io/categories/ml/">MACHINE LEARNING</a>
     <a href="https://salonidash7.github.io/categories/meditations/">MEDITATIONS</a>
    </div>
     
  <div id="main">
  <span style="font-size:30px;cursor:pointer" onclick="openNav()">&#9776; MENU</span>
  <div id="banner" > </div>
  <!--{% include feature_row id="feature_row1" type="left" %}
  {% include feature_row id="feature_row2" type="left" %}  -->
  <div class="entries-{{ page.entries_layout }}">
  {% include posts-category.html taxonomy=page.taxonomy type=page.entries_layout %}
  </div>
  </div>
  <script>
    function openNav() {
        document.getElementById("mySidenav").style.width = "250px";
        document.getElementById("main").style.marginLeft = "250px";
    }
    function closeNav() {
        document.getElementById("mySidenav").style.width = "0";
        document.getElementById("main").style.marginLeft= "0";
    }
</script>
  </body>
</html>  
    
