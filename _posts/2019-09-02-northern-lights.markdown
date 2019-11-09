---
title:  "Aurora Borealis"
subtitle: "Chasing the Northern Lights"
author: "Shwetha Ram"
avatar: "img/authors/profile_pic.PNG"
image: "img/northern_lights/northern_lights.jpg"
date:   2019-09-02 12:12:12
---

One night in Alaska, cruising around Fairbanks and Denali with my friends, I finally got to see...
 
I had seen the pictures. I had read up on the physics. On many a night, I had fallen asleep listening to Alan Sklar describing the [<span style="color:blue">wonder of northern lights</span>](https://www.youtube.com/watch?v=u2dxBkNnlXo). I had even had the chance to hear [<span style="color:blue">Dr. Laura Peticolas</span>](http://epo.sonoma.edu/group/laura-peticolas/) talk about her research on aurora at the University of Alaska during one of the [<span style="color:blue">SJAA</span>](https://www.sjaa.net) monthly astronomy talks. And of course, this goes without saying, I had dreamed. 

Then, one night in Alaska, cruising around Fairbanks and Denali with my friends, I finally got to see.

At first, they were only hazy gray bands spread over the sky - my eyes just couldn't integrate enough of the light to bring out the colors, although looking through an iPhone camera could reveal the beautiful green. Then, in the wee hours of the morning, as we were driving back to our lodge in Denali, the lights grew brighter and I could really see - the pink, the green, the purple. Interestingly, the best show happened just as we were parking our car at the lodge. I had heard that the aurora are most dynamic around the equinox and so they were, we witnessed a spectacular dance.

<!--Start image slideshow-->

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" type="text/css" href="css/slideshow.css">
</head>
<body>

<div class="slideshow-container">

<div class="northernLightsSlides fade">
  <div class="numbertext">1 / 4</div>
  <img src="img/northern_lights/northern_lights_1.jpg" style="width:100%">
</div>

<div class="northernLightsSlides fade">
  <div class="numbertext">2 / 4</div>
  <img src="img/northern_lights/northern_lights_2.jpg" style="width:100%">
</div>

<div class="northernLightsSlides fade">
  <div class="numbertext">3 / 4</div>
  <img src="img/northern_lights/northern_lights_3.jpg" style="width:100%">
</div>

<div class="northernLightsSlides fade">
  <div class="numbertext">4 / 4</div>
  <img src="img/northern_lights/northern_lights_4.jpg" style="width:100%">
</div>

<a class="prev" onclick="plusNorthernLights(-1)">&#10094;</a>
<a class="next" onclick="plusNorthernLights(1)">&#10095;</a>

</div>
<br>

<div style="text-align:center">
  <span class="dot" onclick="currentNorthernLights(1)"></span> 
  <span class="dot" onclick="currentNorthernLights(2)"></span> 
  <span class="dot" onclick="currentNorthernLights(3)"></span> 
  <span class="dot" onclick="currentNorthernLights(4)"></span> 
</div>

<script> 
var northernLightsIndex = 1;
showNorthernLights(northernLightsIndex);

function plusNorthernLights(n) {
  showNorthernLights(northernLightsIndex += n);
}

function currentNorthernLights(n) {
  showNorthernLights(northernLightsIndex = n);
}

function showNorthernLights(n) {
  var i;
  var slides = document.getElementsByClassName("northernLightsSlides");
  var dots = document.getElementsByClassName("dot");
  if (n > slides.length) {northernLightsIndex = 1}
  if (n < 1) {northernLightsIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[northernLightsIndex-1].style.display = "block";
  dots[northernLightsIndex-1].className += " active";
}
</script>

</body>
</html> 

<!--End image slideshow-->

As we were chasing the northern lights, I thought about how they can disappear anytime, or offer the best we've seen yet. We neither know how lasting the wonders of the present moment are, nor how beautiful the next one - it's all about living every moment to the fullest, anticipating colored lights on every turn of the road.
 
My only regret? Not having a good camera! That's for the next time, I guess.

