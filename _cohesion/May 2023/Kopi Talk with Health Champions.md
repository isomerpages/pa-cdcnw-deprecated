---
title: Kopi Talk with Health Champions
permalink: /cohesion/may-2023/health-kopi-talk/
description: ""
third_nav_title: May 2023
---
<style>

p {
  font-family: 'Lato', sans-serif;
  font-size: 16px;
  line-height: 26px;
}

h1, h2, h3, h4, h5, h6, li {
  font-family: 'Lato', sans-serif;
  line-height: initial;
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

.slide-txt {font-size:  20px; color: #FFFFFF; font-weight: 600; padding: 10px 65px; margin-top: 0px; line-height: initial !important;}

@media only screen and (max-width: 767px) {
  [class*="col-"] {
    width: 100%;
  }

  .slider--cover .slider__inner {
    height: 600px !important;
  }

.slide-txt {font-size:  16px; color: #FFFFFF; font-weight: 600; padding: 10px 25px; margin-top: 0px; line-height: initial !important;}  
}



.timeline {
  border-left: 4px solid #cee2d7;
  border-bottom-right-radius: 4px;
  border-top-right-radius: 4px;
  background: rgba(255, 255, 255, 0.03);
  margin: 50px auto;
  letter-spacing: 0.5px;
  position: relative;
  line-height: 1.4em;
  font-size: 1.03em;
  padding: 50px;
  list-style: none;
  text-align: left;
  font-weight: 100;

}
.timeline h1,
.timeline h2,
.timeline h3 {
  letter-spacing: 1.5px;
  font-weight: 100;
  font-size: 1.4em;
}
.timeline .event {
  border-bottom: 1px dashed rgba(255, 255, 255, 0.1);
  padding-bottom: 25px;
  margin-bottom: 50px;
  position: relative;
  list-style: none;
}
.timeline .event:last-of-type {
  padding-bottom: 0;
  margin-bottom: 0;
  border: none;
}
.timeline .event:before,
.timeline .event:after {
  position: absolute;
  display: block;
  top: 0;
}
.timeline .event:before {
  left: -217.5px;
  color: rgba(255, 255, 255, 0.4);
  content: attr(data-date);
  text-align: right;
  font-weight: 100;
  font-size: 0.9em;
  min-width: 120px;
}
.timeline .event:after {
  box-shadow: 0 0 0 4px #0c6c37;
  left: -57.85px;
  background: #0c6c37;
  border-radius: 50%;
  height: 11px;
  width: 11px;
  content: "";
  top: 5px;
}

.carousel, .carousel2 {
    position: relative;
    margin-top: 26px;
}

.carousel-inner, .carousel-inner2 {
    position: relative;
    overflow: hidden;
    width: 100%;
}

.carousel-open:checked + .carousel-item, .carousel-open:checked + .carousel-item2 {
    position: static;
    opacity: 100;
}

.carousel-item, .carousel-item2 {
    position: absolute;
    opacity: 0;
    -webkit-transition: opacity 0.6s ease-out;
    transition: opacity 0.6s ease-out;
}

.carousel-item img, .carousel-item2 img {
    display: block;
    height: auto;
    max-width: 100%;
}

.carousel-control, .carousel-control2 {
    background: rgba(0, 0, 0, 0.28);
    border-radius: 50%;
    color: #fff;
    cursor: pointer;
    display: none;
    font-size: 40px;
    height: 40px;
    line-height: 35px;
    position: absolute;
    top: 50%;
    -webkit-transform: translate(0, -50%);
    cursor: pointer;
    -ms-transform: translate(0, -50%);
    transform: translate(0, -50%);
    text-align: center;
    width: 40px;
    z-index: 10;
}

.carousel-control.prev, .carousel-control2.prev {
    left: 2%;
}

.carousel-control.next, .carousel-control2.next  {
    right: 2%;
}

.carousel-control:hover, .carousel-control2:hover {
    background: rgba(0, 0, 0, 0.8);
    color: #aaaaaa;
}

#carousel-1:checked ~ .control-1,
#carousel-2:checked ~ .control-2,
#carousel-3:checked ~ .control-3,
#carousel-12:checked ~ .control-1,
#carousel-22:checked ~ .control-2,
#carousel-32:checked ~ .control-3,
#carousel-13:checked ~ .control-1,
#carousel-23:checked ~ .control-2,
#carousel-33:checked ~ .control-3  {
    display: block;
}

.carousel-indicators {
    list-style: none;
    margin: 0;
    padding: 0;
    position: absolute;
    bottom: 2%;
    left: 0;
    right: 0;
    text-align: center;
    z-index: 10;
    display: none;
}

.carousel-indicators li {
    display: inline-block;
    margin: 0 5px;
}

.carousel-bullet {
    color: #fff;
    cursor: pointer;
    display: block;
    font-size: 35px;
}

.carousel-bullet:hover {
    color: #aaaaaa;
}

#carousel-1:checked ~ .control-1 ~ .carousel-indicators li:nth-child(1) .carousel-bullet,
#carousel-2:checked ~ .control-2 ~ .carousel-indicators li:nth-child(2) .carousel-bullet,
#carousel-3:checked ~ .control-3 ~ .carousel-indicators li:nth-child(3) .carousel-bullet {
    color: #428bca;
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

.rounded20 {
  -webkit-border-radius: 20px;
  -moz-border-radius: 20px;
  border-radius: 20px;
}
  </style>


<article style="max-width: 800px; width: 100%; margin: auto;">

<div style="width: 100%; padding-top: 15px;">
  <a href="https://northwest.cdc.gov.sg/cohesion/may-2023/may-at-a-glance/">
    <img style="width: 100%; max-width: 100px; position: relative; padding-left: 10px;" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/nw-cohesion-logo-2023%201.gif">
  </a>
</div>

<div style="width: 100%;">
  <img style="width: 100%; max-width:" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/promoting-health-wellness.png">
  <img style="width: 100%; max-width:" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/championing-mental-wellness-title.png">
</div>

<div class="rounded20" style="max-width: 100%; padding: 30px 0px 0px;">
	<img style="width: 100%; margin-top: 0px;" class="rounded20" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/kv-kopitalk_compressed.gif">
  <!--<video class="rounded20" width="100%" height="" muted autoplay loop>
    <source src="images/kv-kopitalk_compressed.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>-->
</div>

<div style="max-width: 100%; padding: 30px 0px 0px;">
  <img style="width: 100%; margin-top: 0px;" class="rounded20" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/kendrick-quote.png">
</div>

<div style="padding: 30px 0px 0px;">
<img style="max-width: 100px; float: right; padding: 0px 0px 5px 20px;" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/kopi%20pic.png">
<h2 style="color: #B25694; font-weight: bold; font-size: x-large;">
  <strong>#KopiTalk with Kendrick Lau</strong>
</h2>
<p style="font-size: 16px; line-height: 26px;"><span style="font-weight: bold; color: #B25694;">The kind of kopi I like best is …</span> our traditional “kopi”, or black coffee with condensed milk and sugar, from our local coffee shop. Starting the morning with my usual cup of kopi is a great way to lift my mood and kickstart the day.  </p>

<img style="max-width: 180px; float: left; padding: 0px 20px 5px 0px;" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/reflexology.png"><p style="font-size: 16px; line-height: 26px;"><span style="font-weight: bold; color: #B25694;">When I’m not working, I like to …</span> enjoy a relaxing session of foot reflexology, together with my wife.</p>
<p style="font-size: 16px; line-height: 26px;"><span style="font-weight: bold; color: #B25694;">The last time I used my CDC Voucher, I spent it on … </span> hawker food! Hawkers are up before the crack of dawn to prepare tasty food for us. Let’s support these unsung heroes!</p>
</div>

<div style="padding: 0px 0px 0px;">
<img style="max-width: 300px; float: right; padding: 0px 0px 5px 20px;" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/moon%20pic.png">
<p style="font-size: 16px; line-height: 26px;"><span style="font-weight: bold; color: #B25694;">My favourite spots in the North-West are …</span> Bukit Panjang Plaza and Hillion Mall. These one-stop malls have everything you need and are a great place to shop, dine or hang out with family and friends. </p>

<p style="font-size: 16px; line-height: 26px;"><span style="font-weight: bold; color: #B25694;">My superpower is …</span> capturing photos of the moon with my telephoto lens. The realisation that we’re just a tiny piece in our vast universe is humbling. We’re all interconnected and part of the same universe. So, discover the world, appreciate life and have empathy for others.</p>
</div>

<div style="padding: 0px 0px 10px;">
<img style="max-width: 350px; float: left; padding: 0px 20px 5px 0px;" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/getaway.png"><p style="font-size: 16px; line-height: 26px; padding-top: 25px;"><span style="font-weight: bold; color: #B25694;">On my last getaway, I visited …</span>  Johor Bahru! I went there with my family to shop, visit the Ramadan bazaars and eat into my favourite fruit - durian! </p>

<p style="font-size: 16px; line-height: 26px;"><span style="font-weight: bold; color: #B25694;">Mental wellness means …</span>  spending effort to love yourself! When you treat yourself with kindness and respect, you’ll be happier and more content.</p>
</div>

<div style="padding: 30px 0px 5px;">
<img style="max-width: 280px; float: right; padding: 0px 0px 5px 20px;" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/home-visiting.png">
<p style="font-size: 16px; line-height: 26px;"><span style="font-weight: bold; color: #B25694;">I care for my mental health by …</span>  practising mindfulness. For instance, I use the “me” time while driving to pick up my children to stay present, focus on my breath and reflect on the positive things in my life. Whenever I overcome a challenging work or family-related episode, I’ll treat my family to a good meal or plan a fun family outing. A constant check and balance will go a long way in maintaining your mental health. </p>

<p style="font-size: 16px; line-height: 26px;"><span style="font-weight: bold; color: #B25694;">The best way to approach someone in distress is to …</span>   listen first before taking action. We must understand that each individual has their own unique challenge, situation or background. So, be patient, non-judgmental and always lend a listening ear first. Only then can we build up that bridge of trust and offer support. </p>
</div>

<div style="padding: 0px 0px 0px;">
<p style="font-size: 16px; line-height: 26px;"><span style="font-weight: bold; color: #B25694;">I’m inspired to reach out to others because …</span>  I believe we can all play a part, no matter how big or small, to make everyone’s life better. I often come across fellow residents in need during house visits with our grassroot advisor. Some have a hard time coping with life’s challenges. Mental health challenges can be invisible so it’s important to offer support if you know someone is having anxiety, worry or fear. </p>
</div>



<div style="padding: 20px 0px;">
<div style="width: 100%; background: #EBDFEC; padding: 0px 0px 0px;" class="rounded20">
  <div style="padding: 30px 40px;">
    <div style="padding: 0px 0px;">
        <p style="font-size: 16px; text-align: left; line-height: 24px; color: #000; margin: 10px 0px;"><strong>Mental Wellness @ North West</strong> aims to raise awareness about mental wellness in the community by building up a mental wellness support network. In 2023, the programme has been expanded to include <strong>Mental Wellness Ambassadors</strong> who will provide support to the community, drive mental wellness initiatives and help residents get access to mental health services early. <a style="font-weight: bold; color: #B25694;" target="_new" href="https://northwest.cdc.gov.sg/programmes/promoting-health-and-wellness/mental-wellness/">Find out more</a> about Mental Wellness @ North West.</p>
        <p style="font-size: 16px; text-align: left; line-height: 24px; color: #000; margin: 10px 0px;">If you’re a caregiver or resident who’d like to understand more about mental wellness, <a style="font-weight: bold; color: #B25694;" target="_new" href="https://northwest.cdc.gov.sg/files/FA_NWCDC_MentalHealthToolkit.pdf">download</a> the Mental Wellness @ North West Toolkit.</p>  
  </div>
</div>
</div>
</div>



<div style="padding: 20px 0px 0px; display: flex;" class="col-">&nbsp;</div>

<div style="width: 100%; background: #FB5C1F; border-radius: 30px; padding: 0px 0px; display: flex;">
  <div style="width: 100%; padding: 10px 10px; text-align: center; margin: auto;">
    <h1 style="font-family:  Arial; font-size: xx-large; font-weight: bold; color: #FFFFFF;"><em>Keep updated with our latest stories!</em></h1>
    <a style="text-decoration: none;" target="_new" href="https://go.gov.sg/subscribe-cohesion">
      <div style="font-family:  Arial; font-size: large; font-weight: bold; background: #FFFFFF; color: #FB5C1F; padding: 10px 15px; max-width: 320px; margin: auto; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem; text-decoration: none;"><em>Subscribe to Cohesion Magazine</em>
      </div>
    </a>

    <div style="width: 100%;">
    <div style="width: 100%; padding: 15px 10px; text-align: center;   display: flex;
  justify-content: center;
  align-items: center;">
      <span style="font-family: Arial; font-weight: bold; font-size: large; color: #FFFFFF;">Follow us on</span> <a target="_new" href="https://www.facebook.com/nwcdc/"><img style="padding: 5px 7px;" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/square-facebook.png"></a>
      <a target="_new" href="https://www.instagram.com/northwestcdc"><img style="padding: 5px 7px;" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/square-instagram.png"></a>
      <a target="_new" href="https://t.me/northwestcdc"><img style="padding: 5px 7px;" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/telegram.png"></a>
      <a target="_new" href="https://www.youtube.com/northwestcdc"><img style="padding: 5px 7px;" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/square-youtube.png"></a>
    </div>
    </div>

    <div style="width: 100%; text-align: right;"><img style="width: 25px;" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/nw-arrow.png"></div>

  </div>

</div>

<div style="padding: 40px 20px; text-align: center;">
  <h2 style="font-size: xx-large; font-weight: bold;"><em>Our Team</em></h2>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Adviser: Mayor Alex Yam</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Editorial Team: Michael Lau, Sim Chuan San, Steve Luo, Eric Liu, Melvin Tai, Charlene Koh</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Please send feedback, suggestions and comments to <a style="color: #000000; text-decoration: underline;" target="_new" href="mailto:northwest_cdc@pa.gov.sg">northwest_cdc@pa.gov.sg</a></p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Some articles in Cohesion are contributed by volunteers and are not necessarily opinions/comments by North West CDC.</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Reproduction in whole or in part is prohibited without prior permission from North West CDC.</p>
</div>


</article>