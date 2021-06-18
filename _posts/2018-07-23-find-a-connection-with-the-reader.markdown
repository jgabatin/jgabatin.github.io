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
.slider {
  width: 500px;
  height: 300px;
  background-color: yellow;
  margin-left: auto;
  margin-right: auto;
  margin-top: 0px;
  text-align: center;
  overflow: hidden;
}
.image-container {
  width: 1500px;
  background-color: pink;
  height: 300px;
  clear: both;
  position: relative;
  -webkit-transition: left 2s;
  -moz-transition: left 2s;
  -o-transition: left 2s;
  transition: left 2s;
}
.slide {
  float: left;
  margin: 0px;
  padding: 0px;
  position: relative;
}
#slide-1:target ~ .image-container {
  left: 0px;
}
#slide-2:target ~ .image-container {
  left: -500px;
}
#slide-3:target ~ .image-container {
  left: -1000px;
}
.buttons {
  position: relative;
  top: -20px;
}
.buttons a {
  display: inline-block;
  height: 15px;
  width: 15px;
  border-radius: 50px;
  background-color: lightgreen;
}
</style>

<body>
  <div class="slider">
    <span id="slide-1">
      <div class="image-container">
        <img src="/images/03.jpg" class="slide" width="100" height="100" />
      </div>
    </span>
    <span id="slide-2">
      <div class="image-container">
        <img src="/images/03.jpg" class="slide" width="100" height="100" />
      </div>
    </span>
    <span id="slide-3">
      <div class="image-container">
        <img src="/images/03.jpg" class="slide" width="100" height="100" />
      </div>
    </span>

    <div class="buttons">
      <a href="#slide-1"></a>
      <a href="#slide-2"></a>
      <a href="#slide-3"></a>
    </div>
  </div>
</body>
