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
  html,
  img {
    max-width: 60%;
  }
  .slider-container {
    height: 80%;
    width: 80%;
    position: relative;
    overflow: hidden;
    text-align: center;
  }
  .menu {
    position: absolute;
    left: 0;
    z-index: 900;
    width: 80%;
    bottom: 0;
  }
  .menu label {
    cursor: pointer;
    display: inline-block;
    width: 16px;
    height: 16px;
    background: #fff;
    border-radius: 50px;
    margin: 0 0.2em 1em;
  }
  .menu label:hover,
  .menu label:focus {
    background: #1c87c9;
  }
  .slide {
    width: 80%;
    height: 80%;
    position: absolute;
    top: 0;
    z-index: 10;
    padding: 8em 1em 0;
    background-size: cover;
    background-position: 50% 50%;
    transition: left 0s 0.75s;
  }
  [id^="slide"]:checked + .slide {
    left: 0;
    z-index: 100;
    transition: left 0.65s ease-out;
  }
  .slide-1 {
    background-image: "/images/03.jpg";
  }
  .slide-2 {
    background-image: "/images/10.jpg";
  }
  .slide-3 {
    background-image: "/images/04.jpg";
  }
</style>
<body>
  <div class="slider-container">
    <div class="menu">
      <label for="slide-dot-1"></label>
      <label for="slide-dot-2"></label>
      <label for="slide-dot-3"></label>
    </div>
    <input id="slide-dot-1" type="radio" name="slides" checked>
    <div class="slide slide-1"></div>
    <input id="slide-dot-2" type="radio" name="slides">
    <div class="slide slide-2"></div>
    <input id="slide-dot-3" type="radio" name="slides">
    <div class="slide slide-3"></div>
  </div>
</body>

<h1 style="color:#3e6913;">Header</h1>

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque volutpat ipsum et lacus bibendum, eget sollicitudin eros rhoncus. Morbi dignissim blandit urna, eget convallis purus accumsan sit amet. Vestibulum ipsum tellus, luctus at laoreet et, rhoncus ut sem. Suspendisse quam dolor, gravida nec mattis a, pretium nec mauris. Sed eget arcu augue. Vestibulum faucibus quis purus id fringilla. Duis ac ornare mi. Proin facilisis non lectus a tempor. Quisque sodales id risus sed porttitor. Aliquam sollicitudin erat egestas quam blandit pharetra. Maecenas velit diam, pretium vel tempor rhoncus, molestie eu dolor. Etiam ipsum mauris, dapibus vitae pellentesque vel, venenatis porttitor odio. Praesent nec dolor quis urna egestas commodo et sed felis. Cras aliquam, libero eget posuere consectetur, dui augue ornare neque, sit amet bibendum arcu eros a enim. Sed mauris ante, eleifend rutrum varius et, vulputate eu nunc.

