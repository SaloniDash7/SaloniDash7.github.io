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
              width: 30vh;
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
              font-size: 3vh;
              color:#f1f1f1 ;
              display: block;
              transition: 0.3s;
          }
          
   .sidenav a:hover {
              color: rgba(48, 227, 202, 0.3);
          }
   .main {
              margin-left: 30vh; 
              font-size: 4vh; 
              padding: 0px 10px;
            }  
    @media screen and (max-width: 700px) {
    .sidenav {
    width: 100%;
    height: auto;
    position: relative;
    }
      .sidenav a {float: left;}
      div.main {margin-left: 0;}
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
     <a href="https://salonidash7.github.io/categories/ml/">MACHINE LEARNING</a>
     <a href="https://salonidash7.github.io/categories/meditations/">MEDITATIONS</a>
    </div>
     
  <div id="main">
  <div id="banner" > </div>
  <!--{% include feature_row id="feature_row1" type="left" %}
  {% include feature_row id="feature_row2" type="left" %}  -->
  <div class="entries-{{ page.entries_layout }}">
  {% include posts-category.html taxonomy=page.taxonomy type=page.entries_layout %}
  </div>
  </div>
  
  </body>
</html>  
    
