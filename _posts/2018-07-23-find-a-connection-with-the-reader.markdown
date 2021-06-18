---
layout: post
title:  Lentl
date:   2018-07-24 15:01:35 +0300
image:  lentl-main.png
tags:   UI/UX
---
<h1 style="color:#3e6913;">Background</h1>
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque volutpat ipsum et lacus bibendum, eget sollicitudin eros rhoncus. Morbi dignissim blandit urna, eget convallis purus accumsan sit amet. Vestibulum ipsum tellus, luctus at laoreet et, rhoncus ut sem. Suspendisse quam dolor, gravida nec mattis a, pretium nec mauris. Sed eget arcu augue. Vestibulum faucibus quis purus id fringilla. Duis ac ornare mi. Proin facilisis non lectus a tempor. Quisque sodales id risus sed porttitor. Aliquam sollicitudin erat egestas quam blandit pharetra. Maecenas velit diam, pretium vel tempor rhoncus, molestie eu dolor. Etiam ipsum mauris, dapibus vitae pellentesque vel, venenatis porttitor odio. Praesent nec dolor quis urna egestas commodo et sed felis. Cras aliquam, libero eget posuere consectetur, dui augue ornare neque, sit amet bibendum arcu eros a enim. Sed mauris ante, eleifend rutrum varius et, vulputate eu nunc.

Vivamus tristique, ex non consequat condimentum, tellus tellus cursus nulla, in sollicitudin nisi sem ut odio. Cras congue neque nec neque pretium vestibulum nec sit amet justo. Vivamus lacinia interdum nunc nec sodales. Aenean ultrices cursus ex, non ultricies nisi finibus aliquet. Aliquam ac lorem enim. Etiam vel augue bibendum, tincidunt felis vel, egestas tortor. Duis eleifend orci nec dolor gravida eleifend quis vitae eros. Cras vel sem a nunc vehicula porta. Nulla felis mauris, tincidunt nec justo eu, luctus tincidunt ex. Praesent ut porttitor eros, sit amet luctus nisl. In fringilla pharetra ipsum, vitae porttitor tortor. Nulla maximus eros dolor, sit amet aliquet lorem consectetur vitae.

<h1 style="color:#3e6913;">Header</h1>

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque volutpat ipsum et lacus bibendum, eget sollicitudin eros rhoncus. Morbi dignissim blandit urna, eget convallis purus accumsan sit amet. Vestibulum ipsum tellus, luctus at laoreet et, rhoncus ut sem. Suspendisse quam dolor, gravida nec mattis a, pretium nec mauris. Sed eget arcu augue. Vestibulum faucibus quis purus id fringilla. Duis ac ornare mi. Proin facilisis non lectus a tempor. Quisque sodales id risus sed porttitor. Aliquam sollicitudin erat egestas quam blandit pharetra. Maecenas velit diam, pretium vel tempor rhoncus, molestie eu dolor. Etiam ipsum mauris, dapibus vitae pellentesque vel, venenatis porttitor odio. Praesent nec dolor quis urna egestas commodo et sed felis. Cras aliquam, libero eget posuere consectetur, dui augue ornare neque, sit amet bibendum arcu eros a enim. Sed mauris ante, eleifend rutrum varius et, vulputate eu nunc.

<style>
* {box-sizing:border-box}

/* Slideshow container */
.slideshow-container {
  max-width: 250px;
  position: relative;
  margin: auto;
}

/* Hide the images by default */
.mySlides {
  display: none;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  margin-top: -22px;
  padding: 16px;
  color: white;
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

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
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
</style>

<!-- Slideshow container -->
<div class="slideshow-container">

  <!-- Full-width images with number and caption text -->
  <div class="mySlides fade">
    <img src="10.jpg" style="width:50%">
  </div>

  <div class="mySlides fade">
    <img src="04.jpg" style="width:50%">
  </div>

  <div class="mySlides fade">
    <img src="03.jpg" style="width:50%">
  </div>

  <!-- Next and previous buttons -->
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>
</div>
<br>

<!-- The dots/circles -->
<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span>
  <span class="dot" onclick="currentSlide(2)"></span>
  <span class="dot" onclick="currentSlide(3)"></span>
</div>
