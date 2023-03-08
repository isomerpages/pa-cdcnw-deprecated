---
title: Little Steps @ North West
permalink: /cohesion/March-2023/little-steps-nw/
description: ""
third_nav_title: March 2023
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


<article style="max-width: 800px; width: 100%; margin: auto;">
<div style="width: 100%;">
  <img src="https://d33wubrfki0l68.cloudfront.net/38c374fae164486a4173751d2a76bc91d4e07d4a/4b6f9/images/cohesion_logo.gif" style="width: 100%; max-width: 200px; z-index: 99; position: relative; margin-left: -20px;">
</div>

<div>
	<img src="/images/Cohesion/March%202023/uplifting.jpg" style="width: 100%; margin-top: 0px;">
</div>

<div>
  <img src="/images/Cohesion/March%202023/kv-uplifting.gif" style="width: 100%; margin-top: 0px;">
</div>

<div style="padding: 0px 0px 10px;">
<p style="font-size: 16px; line-height: 26px; word-spacing: 3px;">Little Steps @ North West provides financial support to needy families with young children so they can improve their child’s development.</p>  

<p style="font-size: 16px; line-height: 26px; word-spacing: 3px;">Up to the age of 6, children learn a lot about themselves and the world around them. These early years are critical for their development and lay the foundation for their futures.</p> 

<p style="font-size: 16px; line-height: 26px; word-spacing: 3px;">However, raising young children can be challenging for families with financial constraints. </p> 

<p style="font-size: 16px; line-height: 26px; word-spacing: 3px;">That’s where Little Steps @ North West comes in to help close this gap.</p>  
</div>

<div>
  <img src="/images/Cohesion/March%202023/about-little-steps.jpg" style="width: 100%; margin-top: 0px;">
</div>

<!--Box-->
<div style="padding: 0px 0px 0px;">
<div style="width: 100%; background: #F2F8F6; padding: 20px 0px 0px; -webkit-border-bottom-right-radius: 20px;
-webkit-border-bottom-left-radius: 20px;
-moz-border-radius-bottomright: 20px;
-moz-border-radius-bottomleft: 20px;
border-bottom-right-radius: 20px;
border-bottom-left-radius: 20px;">
  <div style="padding: 10px 40px;">


  <p style="font-size: 16px; line-height: 26px;">
    <ul style="padding: 0px 15px; line-height: 28px;">
      <li style="line-height: 30px; padding-bottom: 15px; list-style: none;">
        <strong style="color: #0C6C37; ">Who is eligible to receive the cash benefit?</strong><br/> 
        The grant is available to families with young children up to 6 years old who are living in the North West District and who are enrolled in the KidSTART Singapore programme.
      </li>
      <li style="line-height: 30px; padding-bottom: 15px; list-style: none;">
        <strong style="color: #0C6C37; ">How much is the cash support? </strong><br/> 
        Each child will receive $500 each year disbursed to the parents' or caregivers' bank accounts.  
      </li>
      <li style="line-height: 30px; padding-bottom: 15px; list-style: none;">
        <strong style="color: #0C6C37; ">What is the purpose of the cash relief? </strong><br/> 
        From baby necessities to essential school supplies, every bit of help comes goes a long way for these families. And when their material needs are met, they can then give their children the right environment to develop and flourish. 
      </li>
    </ul>
  </p> 
  </div>
</div>
</div>
<!--Box End-->


<div style="padding: 20px 0px 0px;">
<h2 style="color: #D5262B; font-weight: bold; font-size: x-large; margin-bottom: 0px;">
  <strong>Cash benefit provides immediate relief for families</strong>
</h2>
</div>

<div style="padding: 0px 0px;">
<p style="font-size: 16px; line-height: 26px;">Coinciding with the official launch of Little Steps @ North West on 14 January 2023, a trip to the Singapore Zoo was organised for the beneficiaries. We caught up with some of these parents to find out how they plan to use the cash grant they will receive.</p>  

<p style="font-size: 16px; line-height: 26px;">Jesleasha Ong, 43 years old is a single mother with a 3-year-old daughter. She is grateful for the amount of money received as raising her child alone is not easy. </p>
</div>


<div>
  <img src="/images/Cohesion/March%202023/jes.jpg" style="width: 100%; margin-top: 20px;">
</div>

<div style="padding: 20px 0px 0px;">
<p style="font-size: 16px; line-height: 26px;">Azlan, 50 years old and Linda, 46 years old have 6 children. While their 2 eldest children are working full time, this assistance scheme has been a major help to them with their 4 younger children.  </p>
</div>


<div>
  <img src="/images/Cohesion/March%202023/az.jpg" style="width: 100%; margin-top: 20px;">
</div>


<div>
  <img src="/images/Cohesion/March%202023/cash-assistance.png" class="rounded20" style="width: 100%; margin-top: 30px;">
</div>




<div style="padding: 20px 0px;">
<div class="rounded20" style="width: 100%; background: #E5F1ED; padding: 0px 0px 0px;">
  <div style="padding: 30px 40px;">
    <div style="padding: 0px 0px;">
      <p style="font-size: 18px; text-align: left; color: #0C6C37; margin: 0px 0px;"><strong>Give your kids the best start in life</strong>
      </p> 
        <p style="font-size: 16px; text-align: left; line-height: 26px; color: #000; margin: 10px 0px;">Families on the KidSTART SG programme will be enrolled onto the Little Steps @ North West programme. Eligible families will be notified by an email.</p>

<p style="font-size: 16px; text-align: left; line-height: 26px; color: #000; margin: 10px 0px;">For more information, visit <a href="https://go.gov.sg/nw-little-step" target="_new" style="color: #0C6C37; text-decoration: underline; font-weight: bold;">go.gov.sg/nw-little-step</a>. </p>  
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


<br/>
<br/>
</article>


