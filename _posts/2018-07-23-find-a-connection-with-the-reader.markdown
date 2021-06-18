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
.center {
  display: flex;
  justify-content: center;
}
.slider {
  width: 1500px;
  text-align: center;
  overflow: hidden;
}
.slides {
  display: flex;
  
  overflow-x: auto;
  overflow-y: hidden;
  scroll-snap-type: x mandatory;
  
  scroll-behavior: smooth;
  -webkit-overflow-scrolling: touch;
}
.slides::-webkit-scrollbar {
  width: 10px;
  height: 10px;
}
.slides::-webkit-scrollbar-thumb {
  background: #bbbbbb;
  border-radius: 10px;
}
.slides::-webkit-scrollbar-track {
  background: transparent;
}
.slides > div {
  scroll-snap-align: start;
  flex-shrink: 0;
  width: 750px;
  height: 750px;
  margin-right: 50px;
  border-radius: 10px;
  background: white;
  transform-origin: center center;
  transform: scale(1);
  transition: transform 0.5s;
  position: relative;
  
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 100px;
}
img {
  object-fit: contain;
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}
.slider > a {
  display: inline-flex;
  width: 1.5rem;
  height: 1.5rem;
  background: white;
  text-decoration: none;
  align-items: center;
  justify-content: center;
  border-radius: 50%;
  margin: 0 0 0.5rem 0;
  position: relative;
}
.slider > a:active {
  top: 1px;
}
.slider > a:focus {
  background: #000;
}
</style>

<div class="center">
  <div class="slider">
    <div class="slides">
      <div id="slide-1">
        <img src="/images/browse.png">
      </div>
      <div id="slide-2">
        <img src="/images/browse.png">
      </div>
      <div id="slide-3">
        <img src="/images/browse.png">
      </div>
      <div id="slide-4">
        <img src="/images/browse.png">
      </div>
      <div id="slide-5">
        <img src="/images/browse.png">
      </div>
    </div>
  </div>
</div>

<h1 style="color:#3e6913;">Header</h1>

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque volutpat ipsum et lacus bibendum, eget sollicitudin eros rhoncus. Morbi dignissim blandit urna, eget convallis purus accumsan sit amet. Vestibulum ipsum tellus, luctus at laoreet et, rhoncus ut sem. Suspendisse quam dolor, gravida nec mattis a, pretium nec mauris. Sed eget arcu augue. Vestibulum faucibus quis purus id fringilla. Duis ac ornare mi. Proin facilisis non lectus a tempor. Quisque sodales id risus sed porttitor. Aliquam sollicitudin erat egestas quam blandit pharetra. Maecenas velit diam, pretium vel tempor rhoncus, molestie eu dolor. Etiam ipsum mauris, dapibus vitae pellentesque vel, venenatis porttitor odio. Praesent nec dolor quis urna egestas commodo et sed felis. Cras aliquam, libero eget posuere consectetur, dui augue ornare neque, sit amet bibendum arcu eros a enim. Sed mauris ante, eleifend rutrum varius et, vulputate eu nunc.

