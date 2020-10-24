---
layout: default
---


<script type="text/javascript" src="https://platform.linkedin.com/badges/js/profile.js" async defer></script>
<head>
    
    
    <style>
    
    * {box-sizing: border-box}
.mySlides {display: none}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
  text-align:center; 

}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: black;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}
/* Position the "prev button" to the left */

.prev {
  left: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: #ffffff;
}

/* Caption text */
.text {
  color: #000000;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
  background: #f2f2f2
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .prev, .next,.text {font-size: 11px}
}
    
    
    {
        box-sizing: border-box;
    }
    /* Set additional styling options for the columns*/
[class*="col-"] {
  float: left;
}


/* For mobile phones: */
#[class*="col-"] {
  width: 100%;
}


@media only screen and (min-width: 960px) {
  /* For desktop: */
  .col-1 {width: 40%;}
  .col-2 {width: 60%;}

}

@media screen and (max-width: 900px) {
    .tableauCV {
        display: none !important;
    }
}



.float-container {
}

.float-child {
    width: 50%;
    float: left;
}  

        
.button {
  font-family : inherit;
  border: none;
  color: white;
  padding: 16px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  transition-duration: 0.4s;
  cursor: pointer;
}

.m-left {
  margin-left: 280px;
}
.button {
  background-color: #f2f2f2; 
  color: black; 
  border: 2px solid black;
}
.button:hover {
  background-color: #666666;
  color: white;
}
.header img {
  float: left;
  height: 50px;
  border: 0px
}
.header h2 {
  position: relative;
  top: 30px;
  left: 10px;
}
.row::after {
  content: "";
  clear: both;
  display: table;
}

    </style>
 </head>
 <body>

 </body>
<section class = "inner-medium">
 <h2>Power BI</h2>
<div class="slideshow-container">

<div class="mySlides fade">
  <div class="numbertext"></div>
    <a href = "./powerbi/seattle-crime"><img src="seattle-crime.png" style="width:100%"></a>
  <div class="text">Seattle Crime Trends</div>
</div>

<div class="mySlides fade">
  <div class="numbertext"></div>
    <a href = "./powerbi/covid-dashboard"><img src="covid-dashboard.png" style="width:100%"></a>
  <div class="text">COVID-19 Progression by Country</div>
</div>



<a class="prev" onclick="plusSlides(-1)">&#10094;</a>
<a class="next" onclick="plusSlides(1)">&#10095;</a>

</div>
<br>

<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
</div>

<script>
var slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
}
</script>
</section>

 <section class = "inner-medium">
    
     <p>My first experience with Power BI was at my summer internship at Icertis - a contact management software as a service company. I got tasked to replace a whiteboard where people would sometimes update metrics relating to Marketing engagement with two TV screens showing several up to date dashboards. It was a great project where I could really learn by doing and implement new features as they were being released (such as Dataflows)</p>
    <p>From that point onwards, everytime I have some question that can be answered with data one of the main tools I use is Power BI. Above you can see some example of projects where I have started with some curiosity and ended up with a dashboard</p>
 
 </section>
