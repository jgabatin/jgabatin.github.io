---
layout: post
title:  Lentl
date:   2018-07-24 15:01:35 +0300
image:  lentl-main.png
tags:   UI/UX
---
<style>
.center {
  display: flex;
  justify-content: center;
}
.slider {
  width: 1200px;
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
  flex-shrink: 1;
  width: 500px;
  height: 500px;
  margin-right: 5px;
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
img.slideimg {
  object-fit: contain;
  position: absolute;
  top: 0;
  left: 0;
  width: 95%;
  height: 95%;
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

<h1 style="color:#3e6913;">Overview</h1>

My Role: Market Research, UI/UX Design, Front-End Development
Team: Ideator
Time: 2 Weeks
Tools: React Native, Expo

<h1 style="color:#3e6913;">Project Details</h1>

Lentl is a P2P luxury rental service that allows users to rent and try premium apparel across an assortment of labels without having to spend hundreds in retail price. Users on the platform have the ability to rent (Lentee) or list their own items for rent on the marketplace (Lenter).
<br>
Though fashion trends are always changing, the rise of ‘fast fashion’ has made purchasing designer apparel a financially questionable choice for the average young adult looking to splurge on luxury items. A majority of these individuals may be uninterested in high fashion as a whole, but the popularity of social media influencers has inevitably caused an increase in desire for brands like Gucci, Dior, etc. 

<h1 style="color:#3e6913;">Challenge</h1>

While there are already existing clothing rental platforms, a quick Google search shows that most, if not all of these marketplaces are catered towards a broad market revolving around casualwear or women’s dresses. Further, there are currently no mobile apps that are dedicated to providing a peer-to-peer rental service for both men and women within the high fashion domain. 

<h1 style="color:#3e6913;">Solution</h1>

The ideator and I collaborated extensively in researching the upscale fashion space, interviewing select peers, and developing a product roadmap. Based on our findings and after getting a rough estimate of our SOM, we decided to hone in on affordability and accessibility as the service’s key value proposition. Given these factors, I designed and developed the user-facing side of the app to optimize for usability and adaptability.

<h1 style="color:#3e6913;">Market Landscape</h1>

<div class="center">
  <img src="/images/lentl-comp.jpg" width="65%" height="65%">
</div>

<div class="center">
  <img src="/images/lentl-market.jpg" width="65%" height="65%">
</div>

<h1 style="color:#3e6913;">User Research Findings</h1>

As someone who is relatively familiar with the luxury goods industry based on past research, but has never actually bought any products due to the financial barrier (does cologne count?), the responses we received from peers were what I had expected. Despite status being the biggest motivator, young adults want to wear unique, higher quality products without paying half a month’s rent for a single item.
<br>
I drafted two personas based on the details gathered from the interviews and two different scenarios that would prompt a user to acquire or lend their apparel

<div class="center">
  <div class="slider">
    <div class="slides">
      <div id="slide-1">
        <img src="/images/browse.png" class="slideimg">
      </div>
      <div id="slide-2">
        <img src="/images/browse.png" class="slideimg">
      </div>
    </div>
  </div>
</div>

<div class="center">
  <div class="slider">
    <div class="slides">
      <div id="slide-1">
        <img src="/images/browse.png" class="slideimg">
      </div>
      <div id="slide-2">
        <img src="/images/browse.png" class="slideimg">
      </div>
      <div id="slide-3">
        <img src="/images/browse.png" class="slideimg">
      </div>
    </div>
  </div>
</div>

<div class="center">
  <div class="slider">
    <div class="slides">
      <div id="slide-1">
        <img src="/images/browse.png" class="slideimg">
      </div>
      <div id="slide-2">
        <img src="/images/browse.png" class="slideimg">
      </div>
      <div id="slide-3">
        <img src="/images/browse.png" class="slideimg">
      </div>
    </div>
  </div>
</div>

<br>

<h1 style="color:#3e6913;">Header</h1>

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque volutpat ipsum et lacus bibendum, eget sollicitudin eros rhoncus. Morbi dignissim blandit urna, eget convallis purus accumsan sit amet. Vestibulum ipsum tellus, luctus at laoreet et, rhoncus ut sem. Suspendisse quam dolor, gravida nec mattis a, pretium nec mauris. Sed eget arcu augue. Vestibulum faucibus quis purus id fringilla. Duis ac ornare mi. Proin facilisis non lectus a tempor. Quisque sodales id risus sed porttitor. Aliquam sollicitudin erat egestas quam blandit pharetra. Maecenas velit diam, pretium vel tempor rhoncus, molestie eu dolor. Etiam ipsum mauris, dapibus vitae pellentesque vel, venenatis porttitor odio. Praesent nec dolor quis urna egestas commodo et sed felis. Cras aliquam, libero eget posuere consectetur, dui augue ornare neque, sit amet bibendum arcu eros a enim. Sed mauris ante, eleifend rutrum varius et, vulputate eu nunc.

