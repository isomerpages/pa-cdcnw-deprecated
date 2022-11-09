---
title: Understanding Dengue
permalink: /cohesion/November-2022/nea-dengue/
description: ""
third_nav_title: November 2022
---
<html>
<head>
<style>
p {
	font-family: 'Lato', sans-serif;
	font-size: 16px;
	line-height: 26px;
}

h1, h2, h3, h4, h5, h6, li {
  font-family: 'Lato', sans-serif;
}

.col-1 {width: 8.33%;}
.col-2 {width: 16.66%;}
.col-3 {width: 25%;}
.col-4 {width: 33.33%;}
.col-5 {width: 41.66%;}
.col-6 {width: 50%;}
.col-7 {width: 58.33%;}
.col-8 {width: 66.66%;}
.col-9 {width: 75%;}
.col-10 {width: 83.33%;}
.col-11 {width: 91.66%;}
.col-12 {width: 100%;}

@media only screen and (max-width: 768px) {
  [class*="col-"] {
    width: 100%;
  }
}

.slider {
  position: relative;
  max-width: 100%;
  max-height: 100%;
  margin: 0 auto;
}
.slider:hover .slider__radiobox-label--prev,
.slider:hover .slider__radiobox-label--next {
  opacity: 1;
}
.slider:hover .slider__radiobox-label--prev {
  left: 2%;
}
.slider:hover .slider__radiobox-label--next {
  right: 2%;
}
.slider--cover {
  width: 100vw;
}
.slider--fixed {
  width: 600px;
  height: 400px;
}
.slider--proportional {
  width: 100%;
  height: auto;
}

.slider__inner {
  position: relative;
  margin: 0 auto;
  overflow: hidden;
  background: #ddd;
}
.slider--cover .slider__inner {
  width: 100%;
  height: 300px;
}
.slider--fixed .slider__inner {
  width: 100%;
  height: 100%;
}
.slider--proportional .slider__inner {
  width: 100%;
  height: 0;
}
.slider--proportional-4x3 .slider__inner {
  padding-top: 75%;
}
.slider--proportional-5x4 .slider__inner {
  padding-top: 80%;
}
.slider--proportional-16x9 .slider__inner {
  padding-top: 56.25%;
}

.slider__slides {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1;
  width: 400%;
  height: 100%;
  overflow-y: hidden;
  transition: margin-left 0.4s;
}

.slider__slide {
  display: block;
  float: left;
  position: relative;
  width: 25%;
  height: 100%;
}
.slider__slide img {
  width: 100%;
  height: 100%;
  -o-object-fit: cover;
     object-fit: cover;
}

.slider__radiobox-label {
  display: block;
  position: absolute;
  z-index: 2;
  cursor: pointer;
}
.slider__radiobox-label--item {
  bottom: 6%;
  left: 50%;
  transform: translateX(-50%);
  padding: 6px;
  border-radius: 50%;
  background: white;
  opacity: 0.3;
  transition: opacity 0.2s;
}
.slider__radiobox-label--item:hover {
  opacity: 0.5;
}
.slider__radiobox-label--item-1 {
  margin-left: -36px;
}
.slider__radiobox-label--item-2 {
  margin-left: -12px;
}
.slider__radiobox-label--item-3 {
  margin-left: 12px;
}
.slider__radiobox-label--item-4 {
  margin-left: 36px;
}
.slider__radiobox-label--prev, .slider__radiobox-label--next {
  display: none;
  top: 50%;
  transform: translateY(-50%);
  height: 0;
  border: 10px solid #FFF;
  border-top-color: transparent;
  border-bottom-color: transparent;
  opacity: 0;
  transition: left 0.2s, right 0.2s, opacity 0.2s;
}
.slider__radiobox-label--prev {
  left: -2%;
  border-left: 0;
  border-right-width: 17px;
}
.slider__radiobox-label--next {
  right: -2%;
  border-right: 0;
  border-left-width: 17px;
}

.slider__radiobox {
  display: none;
}
.slider__radiobox--1:checked ~ .slider__slides {
  margin-left: 0;
}
.slider__radiobox--2:checked ~ .slider__slides {
  margin-left: -100%;
}
.slider__radiobox--3:checked ~ .slider__slides {
  margin-left: -200%;
}
.slider__radiobox--4:checked ~ .slider__slides {
  margin-left: -300%;
}
.slider__radiobox--1:checked + .slider__radiobox-label--item-1, .slider__radiobox--2:checked + .slider__radiobox-label--item-2, .slider__radiobox--3:checked + .slider__radiobox-label--item-3, .slider__radiobox--4:checked + .slider__radiobox-label--item-4 {
  opacity: 1;
}
.slider__radiobox--1:checked ~ .slider__radiobox-label--prev-4, .slider__radiobox--1:checked ~ .slider__radiobox-label--next-2, .slider__radiobox--2:checked ~ .slider__radiobox-label--prev-1, .slider__radiobox--2:checked ~ .slider__radiobox-label--next-3, .slider__radiobox--3:checked ~ .slider__radiobox-label--prev-2, .slider__radiobox--3:checked ~ .slider__radiobox-label--next-4, .slider__radiobox--4:checked ~ .slider__radiobox-label--prev-3, .slider__radiobox--4:checked ~ .slider__radiobox-label--next-1 {
  display: block;
}

  </style>
</head>
<body>
<article style="max-width: 800px; width: 100%; margin: auto;">
<div style="width: 100%;">
  <img src="https://d33wubrfki0l68.cloudfront.net/38c374fae164486a4173751d2a76bc91d4e07d4a/4b6f9/images/cohesion_logo.gif" style="width: 100%; max-width: 133px; z-index: 99; position: relative; margin-left: -22px;">
</div>

<div>
	<img src="images/dengue-kv.jpg" style="width: 100%; margin-top: 0px;">
</div>

<div style="padding: 20px 0px;">
<p style="font-size: 16px; line-height: 26px;">Since the start of 2022, there has been a surge in dengue cases due to the high Aedes aegypti mosquito population detected in the community and the circulation of the previously uncommon Dengue virus serotype 3 (DENV-3) .
</p>
</div>

<div>
  <img src="images/saw2-kv.jpg" style="width: 100%; margin: 0px auto;">
</div>

<div style="padding: 20px 0px;">
<h2 style="color: #D5262B; font-weight: bold; font-size: x-large;"><strong>Unlike Covid-19, there is no effective vaccine against dengue.</strong></h2>

<p style="font-size: 16px; line-height: 26px; word-spacing: 3px;">So everyone needs to play their part to BLOCK dengue by depriving mosquitoes of potential breeding habitats. Residents, especially those in dengue cluster areas, are also encouraged to protect themselves with the S-A-W actions.
</p>
</div>





<div class="col-" style="padding: 20px 0px 0px; display: flex;">&nbsp;</div>

<!--CTA Megaphone-->
<div style="width: 100%; background: #fb6e36; border-radius: 30px; padding: 20px 0px; display: flex;">
  <div style="padding: 10px 10px; text-align: center; margin: auto;">
  <div class="col-5" style="float: left; text-align: center;">
    <img src="https://northwest.cdc.gov.sg/images/Cohesion/Sept%202022/megaphone.png" style="width: 100%; max-width: 270px; margin: auto;">
  </div>
  <div class="col-7" style="float: left; text-align: center;">
    <div>
      <a href="https://go.gov.sg/subscribe-cohesion" target="_new" style="cursor: default;"><img src="https://northwest.cdc.gov.sg/images/Cohesion/Sept%202022/subscribe-cta.png" style="width: 100%; max-width: 397px;"></a>
    </div>


<div style="width: 100%; margin: 0px auto; text-align: center;">
<div style="margin: 0px auto; display: inline-block;">
  <div style="float:left; max-width: 128px;">
  <img src="https://northwest.cdc.gov.sg/images/Cohesion/Sept%202022/follow-us.png" style="max-width: 128px;">
  </div>
  <div style="float:left; max-width: 47px;">
  <a href="https://www.facebook.com/nwcdc/" target="_new"><img src="https://northwest.cdc.gov.sg/images/Cohesion/Sept%202022/fb.png" style="max-width: 39px;"></a>
  </div>
  <div style="float:left; max-width: 49px;">
  <a href="https://www.instagram.com/northwestcdc" target="_new"><img src="https://northwest.cdc.gov.sg/images/Cohesion/Sept%202022/ig.png" style="max-width: 40px;"></a>
  </div>
  <div style="float:left; max-width: 41px;">
  <a href="https://t.me/northwestcdc" target="_new"><img src="https://northwest.cdc.gov.sg/images/Cohesion/Sept%202022/tg.png" style="max-width: 46px;"></a>
  </div>
  <div style="float:left; max-width: 48px;">
  <a href="https://www.youtube.com/northwestcdc" target="_new"><img src="https://northwest.cdc.gov.sg/images/Cohesion/Sept%202022/yt.png" style="max-width: 53px;"></a>
  </div>
</div>
</div>

  </div>
  </div>
</div>
<!--CTA Megaphone End-->

<!--Footer-->
<div style="padding: 40px 20px; text-align: center;">
  <h2 style="font-size: xx-large; font-weight: bold;"><em>Our Team</em></h2>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Adviser: Mayor Alex Yam</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Editorial Team: Michael Lau, Sim Chuan San, Steve Luo, Eric Liu, Melvin Tai, Charlene Koh</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Please send feedback, suggestions and comments to <a href="mailto:northwest_cdc@pa.gov.sg" target="_new" rel="noopener noreferrer" data-auth="NotApplicable" data-safelink="true" style="color: #000000; text-decoration: underline;">northwest_cdc@pa.gov.sg</a></p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Some articles in Cohesion are contributed by volunteers and are not necessarily opinions/comments by North West CDC.</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Reproduction in whole or in part is prohibited without prior permission from North West CDC.</p>
</div>
<!--Footer End-->

<br/>
<br/>
</article>
</body>
</html>

