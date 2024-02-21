---
title: North West Youth Assembly
permalink: /cohesion/january-2023/nw-youthassembly/
description: ""
third_nav_title: January 2023
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

.video-container {position: relative; padding-bottom: 56.25%; padding-top: 30px; height: 0; overflow: hidden; }

.video-container iframe, .video-container object, .video-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }

video[poster]{
width:100%;
object-fit: cover;
}

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

</head>
<body>
<article style="max-width: 800px; width: 100%; margin: auto;">
<div style="width: 100%;">
  <img src="/images/cohesion-logo.gif" style="width: 100%; max-width: 200px; z-index: 99; position: relative; margin-left: -20px;">
</div>

<div>
	<img src="/images/Cohesion/Jan%202023/volunteerism-kv.gif" style="width: 100%; margin-top: 0px;">
</div>

<div style="padding: 0px 0px 10px;">
<p style="font-size: 16px; line-height: 26px; word-spacing: 3px; padding: 30px 0px;">North West Youth Assembly is a volunteer group comprising youth leaders between the ages of 14 and 35. Nominated by their secondary schools within the North West , YA leaders are empowered to make a difference by organising community programmes that can benefit residents. Bringing passion and commitment, these youth volunteers generously contribute their time to foster a closer community spirit. </p>   
</div>

<div style="padding: 0px 0px 0px;">
<h2 style="color: #D5262B; font-weight: bold; font-size: x-large;">
  <strong>Get to know the North West Youth Assembly’s new exco leaders!</strong>
</h2>
</div>

<div style="padding: 0px 0px;">
<p style="font-size: 16px; line-height: 26px; padding: 10px 0px 0px;">Recently, the YA welcomed its new Executive Committee for 2022 – 2024. They share their aspirations for YA moving forward, and what inspires them to give back to the community. </p> 

<div style="text-align: center; padding: 0px 0px;">
<div class="carousel">
    <div class="carousel-inner" style="-webkit-border-radius: 20px; -moz-border-radius: 20px; border-radius: 20px;">
        <input class="carousel-open" type="radio" id="carousel-1" name="carousel" aria-hidden="true" hidden="" checked="checked">
        <div class="carousel-item">
            <img src="/images/card-aubery.png" style="width: 100%;">
        </div>
        <input class="carousel-open" type="radio" id="carousel-2" name="carousel" aria-hidden="true" hidden="">
        <div class="carousel-item">
            <img src="/images/card-lagu.png" style="width: 100%;">
        </div>
        <input class="carousel-open" type="radio" id="carousel-3" name="carousel" aria-hidden="true" hidden="">
        <div class="carousel-item">
            <img src="/images/card-joe.png" style="width: 100%;">
        </div>
        <label for="carousel-3" class="carousel-control prev control-1">‹</label>
        <label for="carousel-2" class="carousel-control next control-1">›</label>
        <label for="carousel-1" class="carousel-control prev control-2">‹</label>
        <label for="carousel-3" class="carousel-control next control-2">›</label>
        <label for="carousel-2" class="carousel-control prev control-3">‹</label>
        <label for="carousel-1" class="carousel-control next control-3">›</label>
        <ol class="carousel-indicators">
            <li>
                <label for="carousel-1" class="carousel-bullet">•</label>
            </li>
            <li>
                <label for="carousel-2" class="carousel-bullet">•</label>
            </li>
            <li>
                <label for="carousel-3" class="carousel-bullet">•</label>
            </li>
        </ol>
    </div>
</div>
</div>

<div style="text-align: center; padding: 50px 0px 20px; display: inline-block;">
  <img src="/images/roles-ya.png" style="width: 100%; max-width: 100%; margin: 0px auto; -webkit-border-radius: 20px;
-moz-border-radius: 20px;
border-radius: 20px;">
</div>

<div style="padding: 20px 0px 20px;">
<div class="rounded20" style="width: 100%; background: #FFECD6; padding: 20px 0px 0px;">
  <div style="padding: 10px 40px;">
  <h2 style="color: #D5262B; font-weight: bold; font-size: x-large;">
    <strong>What does YA hope to achieve?</strong>
  </h2>
  <p style="font-size: 16px; line-height: 26px;">
    <ul style="padding: 0px 15px; line-height: 28px; background: #FFECD6;">
      <li style="line-height: 32px;"><strong>To connect people and bring the community together</strong></li>
      <li style="line-height: 32px;"><strong>Motivate youths to join our events and give back to society</strong></li>
      <li style="line-height: 32px;"><strong>Inspire volunteerism amongst youths</strong>
        <p style="padding: 0px; margin: 0px; font-weight: normal; font-size: 14px;">For example, the Kayak and Clean event that we organised allowed migrant workers and members of the community to bond while working together to remove litter from the sea. </p>
      </li>
    </ul>
  </p> 
  </div>
  <img src="/images/Cohesion/Jan%202023/ya1.png" style="width: 100%; position: inherit; bottom: 0; margin-top: -200px;">
</div>
</div>

<div class="slider slider--cover" style="height: auto; padding: 20px 0px;">
  <div class="slider__inner" style="background: #FB5C1F; border-radius: 30px;">
    <div style="position:absolute; left:0;"><img src="https://northwest.cdc.gov.sg/images/Cohesion/Sept%202022/quote_1.png"></div>
    <div style="position: absolute; bottom: 0; right: 0;"><img src="https://northwest.cdc.gov.sg/images/Cohesion/Sept%202022/quote_2.png"></div>
    <div class="slider__slides">
      <div class="slider__slide slider__slide--1">
                <div style="width:  100%; text-align: center; margin: 0; position: absolute; top: 50%; transform: translateY(-50%);"><p class="slide-txt"><em>Volunteering inspires curiosity to make things better in the community. I see that in my fellow volunteers. For example, for Lagu, it’s about how to plan a project and lead people while for Joe, it’s about thinking out of the box to improve things. Personally, YA has also given me the opportunity to interact with others and improve the way I think, talk and communicate with people.</em></p>
                <p style="font-size: 15px; line-height: initial; margin-top: 0px; color: #FFFFFF;"><em>- Aubery on what volunteering means to him</em></p>
                </div>
      </div>
    </div>
  </div>
</div>

<div style="text-align: center; padding: 20px 0px; display: inline-block;">
  <img src="/images/Cohesion/Jan%202023/Volunteer_1.png" class="rounde20" style="width: 100%; max-width: 100%; margin: 0px auto;">
</div>

<div style="text-align: center; padding: 20px 0px; display: inline-block;">
  <img src="/images/Cohesion/Jan%202023/Volunteer_2.png" class="rounde20" style="width: 100%; max-width: 100%; margin: 0px auto;">
</div>

<div style="text-align: center; padding: 20px 0px; display: inline-block;">
  <img src="/images/Cohesion/Jan%202023/Volunteer_3.png" class="rounde20" style="width: 100%; max-width: 100%; margin: 0px auto;">
</div>


<div style="padding: 20px 0px;">
<div class="rounded20" style="width: 100%; background: #FFECD6; padding: 20px 0px 30px;">
  <div style="padding: 10px 40px;">
  <div>
    
    <p style="color: #D5262B; font-weight: bold; font-size: x-large;">
      <img src="/images/Cohesion/Jan%202023/upcoming_icon.png" style="max-width: 40px; margin: -8px 10px 0px 0px; float: left;" align="left"><strong>Upcoming Projects in YA</strong>
    </p>
  </div>
  <p style="font-size: 16px; line-height: 26px; text-align: center;">
    There are quite a number of exciting projects coming up, including Service Weeks+ and a painting project with CampusImpact in Yishun. Look out for those!
  </p> 
  <hr/>
    <p style="font-size: 18px; line-height: 26px; text-align: center; color: #D5262B; font-weight: bold;">
    Check out our 22nd Young Leaders Camp held on 13-15 June 2022
    </p> 

    <div style="text-align: center; padding: 0px 0px 0px;">
    <div class="video-container">
      <iframe src="https://www.youtube.com/embed/7FlZ96boFUE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    </div>

  </div>
</div>
</div>


<div style="padding: 20px 0px;">
<div class="rounded20" style="width: 100%; background: #FDF2F3; padding: 0px 0px 0px;">
  <img src="/images/Cohesion/Jan%202023/ya-quick-facts.png" style="max-width:100%;">
  <div style="padding: 30px 40px;">
    <div style="padding: 0px 0px 10px;">
      <p style="font-size: 18px; text-align: left; color: #D5262B; margin: 0px 0px;"><strong>What it is</strong>
      </p> 
        <p style="font-size: 16px; text-align: left; line-height: initial; color: #000; margin: 10px 0px;">
        A platform for youths to make an impact in society 
        </p> 
    </div>
    <div style="padding: 0px 0px 10px;">
      <p style="font-size: 18px; text-align: left; color: #D5262B; margin: 0px 0px;"><strong>How to join</strong>
      </p> 
        <p style="font-size: 16px; text-align: left; line-height: initial; color: #000; margin: 10px 0px;">
        Be nominated by your secondary school within the North West District 
        </p> 
    </div>
    <div style="padding: 0px 0px 10px;">
      <p style="font-size: 18px; text-align: left; color: #D5262B; margin: 0px 0px;"><strong>What you will do</strong>
      </p> 
        <p style="font-size: 16px; text-align: left; line-height: initial; color: #000; margin: 10px 0px;">
        Run events and interact with members of the community 
        </p> 
    </div>
    <div style="padding: 0px 0px 10px;">
      <p style="font-size: 18px; text-align: left; color: #D5262B; margin: 0px 0px;"><strong>What you will learn</strong>
      </p> 
        <p style="font-size: 16px; text-align: left; line-height: initial; color: #000; margin: 10px 0px;">
        Develop project management skills including how to coordinate resources, plan, publicise and organise events. 
        </p> 
    </div>
    <div style="padding: 0px 0px 10px;">
      <p style="font-size: 18px; text-align: left; color: #D5262B; margin: 0px 0px;"><strong>How you will benefit</strong>
      </p> 
      <ul style="padding-left: 15px;">
        <li>Make new friends</li> 
<li>Develop valuable skills</li> 
<li>Gain confidence</li>
<li>Develop a sense of purpose</li> 
<li>Be part of a community </li>
      </ul>
        <p style="font-size: 16px; text-align: left; line-height: initial; color: #000; margin: 10px 0px;">
        <strong>Find out more about YA <a href="https://www.instagram.com/nwyouth_assembly/?hl=en" target="_new" style="color: #000;">here</a>. </strong>
        </p> 
    </div>

</div>
</div>

<div style="padding: 20px 0px;">
<div class="rounded20" style="width: 100%; background: #F7D4D5; padding: 0px 0px 0px;">
  <div style="padding: 30px 40px;">
    <div style="padding: 0px 0px;">
      <p style="font-size: 18px; text-align: left; color: #D5262B; margin: 0px 0px;"><strong>You too can help!</strong>
      </p> 
        <p style="font-size: 16px; text-align: left; line-height: initial; color: #000; margin: 10px 0px;">Through our various projects, North West CDC provides opportunities for volunteers to contribute&nbsp;to&nbsp;society.</p>  

        <p style="font-size: 16px; text-align: left; line-height: initial; color: #000; margin: 10px 0px;">Contact us through <a href="northwestcdc_partnerships@pa.gov.sg" target="_new" style="color: #000; font-weight: bold;">northwestcdc_partnerships@pa.gov.sg</a> to find out how you can join us 
as&nbsp;a&nbsp;volunteer. </p> 
    </div>
  </div>
</div>
</div>



<div class="col-" style="padding: 20px 0px 0px; display: flex;">&nbsp;</div>

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

<div style="padding: 40px 20px; text-align: center;">
  <h2 style="font-size: xx-large; font-weight: bold;"><em>Our Team</em></h2>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Adviser: Mayor Alex Yam</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Editorial Team: Michael Lau, Sim Chuan San, Steve Luo, Eric Liu, Melvin Tai, Charlene Koh</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Please send feedback, suggestions and comments to <a href="mailto:northwest_cdc@pa.gov.sg" target="_new" style="color: #000000; text-decoration: underline;">northwest_cdc@pa.gov.sg</a></p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Some articles in Cohesion are contributed by volunteers and are not necessarily opinions/comments by North West CDC.</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Reproduction in whole or in part is prohibited without prior permission from North West CDC.</p>
</div>



</article>



</body>
</html>