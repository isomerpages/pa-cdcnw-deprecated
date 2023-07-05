---
title: "Service Weeks: Volunteer's Day Out"
permalink: /cohesion/july-2023/sw-volunteersdayout/
description: ""
third_nav_title: July 2023
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

.w-100 {max-width: 100% !important;}

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
  <a href="https://northwest.cdc.gov.sg/cohesion/july-2023/july-at-a-glance">
    <img style="width: 100%; max-width: 100px; position: relative; padding-left: 10px; float:left !important; padding-bottom: 20px;" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/nw-cohesion-logo-2023%201.gif">
  </a>
</div>

<div style="width: 100%;">
  <img style="width: 100%; max-width:" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/enabling-partnerships-volunteerism.png">
  <img style="width: 100%; max-width:" src="/images/Cohesion/July%202023/volunteers.png">
</div>

<div class="rounded20" style="max-width: 100%; padding: 30px 0px 0px;">
	<img style="width: 100%; margin-top: 0px;" class="rounded20" src="/images/Cohesion/July%202023/volunteers-kv.png">
</div>

<div style="padding: 30px 0px;">
<p style="font-size: 16px; line-height: 26px;">To celebrate their 35th Anniversary, Northland Primary School and its dedicated group of parent volunteers organised a carnival for residents living in the public rental units at Nee Soon South, on top of volunteering at the North West Service Weeks Pop-Up Market to distribute food packs.</p>

<p style="font-size: 16px; line-height: 26px;">For mother and daughter team, Mrs Ho and Charis, it was a fun day out giving back to the community together.</p>
</div>

<div style="padding: 0px 0px 0px;">
<h2 style="color: #D5262B; font-weight: bold !important; font-size: x-large; margin: 0px 0px;">
  <strong>Meet Our Volunteer</strong>
</h2>
</div>

<div class="rounded20" style="max-width: 100%; padding: 20px 0px;">
  <img style="width: 100%; margin-top: 0px;" class="rounded20" src="/images/Cohesion/July%202023/volunteers-quote.png">
  <figcaption style="text-align: center; padding: 5px 5px;" class="w-100"><i>Mrs Ho, NPS PSG volunteer and her daughter Charis Ho</i></figcaption> 
</div>

<div class="rounded20" style="max-width: 100%; padding: 30px 0px 0px;">
  <img style="width: 100%; margin-top: 0px;" class="rounded20" src="/images/Cohesion/July%202023/service-weeks-picture.jpg">
</div>

<div style="padding: 20px 0px; margin: 30px 0px 0px;">
<div style="width: 100%; background: #F5E1E0; padding: 0px 0px 0px;" class="rounded20">
  <div style="padding: 20px 20px 40px;">
    <div style="padding: 0px 0px;">
      <img style="width: 100%; padding: 0px 0px 10px; max-width: 60px; display: inline-flex;" src="/images/Cohesion/July%202023/quote%20inverted%20commas%20.png">

        <div style="padding: 20px 40px;" class="w-100">
        <p style="font-size: 16px; text-align: left; line-height: 24px; color: #000; margin: 10px 0px;"><strong>Through the PSG, we have participated in many community outreach activities, including previous editions of Service Weeks where we delivered festive care packs to the residents in the nearby public rental units.</strong></p> 

        <p style="font-size: 16px; text-align: left; line-height: 24px; color: #000; margin: 10px 0px;"><strong>Besides volunteering at the Pop-Up Market, the PSG wanted to add some fun to the event as part of NPS' 35th anniversary celebrations. We roped in fellow parent volunteers and students to assist with the logistics at the Pop-Up Market as well as to organise a fun-filled carnival for the residents. Over 100 students and volunteers came together to help out in the various roles including ushering, registration, packing, replenishing the food items, acting as a personal shopper to the residents, and manning the various booths at the carnival. My younger daughter, who is in P6 this year also helped out at the carnival.</strong> 
        </p>

        <p style="font-size: 16px; text-align: left; line-height: 24px; color: #000; padding: 20px 0px 0px;">
          <strong>Mrs Carol Ho</strong><br>
          <i>PSG Exco Member, Northland Primary School</i>  
        </p>
        </div>

      <div style="width: 25px; text-align: right; float: right;
    display: inline-flex;
    margin-bottom: 30px;"><img style="width: 25px;" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/nw-arrow.png"></div>
  </div>
</div>
</div>
</div>

<div style="padding: 20px 0px;">
<div style="width: 100%; background: #F5E1E0; padding: 0px 0px 0px; display: flex;" class="rounded20">

<div style="width: 100%;" class="w-100">

    <div style="padding: 20px 10px; width: 100%; display: inline-block;" class="w-100">

      <div style="float: left; text-align: center;" class="col- col-3">
        <img style="max-width: 120px; padding: 0px 5px 0px 5px;" src="/images/Cohesion/July%202023/service-icon.png">
      </div>

      <div style="float: left; padding-top: 15px;" class="col- col-9">
      <p style="font-size: 18px; font-weight: bold; text-align: left; color: #D5262B; margin: 0px 0px; line-height: initial;">
      Curious about how Service Weeks and the Pop-Up Markets work?
      </p> 

      <p style="font-size: 16px; line-height: 26px; padding-top: 0px;
    margin-top: 10px;">Find out more about North West Service Weeks <a style="font-weight: bold; color: #D5262B;" target="_new" href="https://northwest.cdc.gov.sg/cohesion/march-2023/nw-serviceweeks/">here!</a></p> 
      </div>
  </div>
</div>
</div>
</div>




<div style="padding: 20px 0px;">
<div style="width: 100%; background: #F5E1E0; padding: 0px 0px 0px;" class="rounded20">
  <div style="padding: 30px 40px;">
    <div style="padding: 0px 0px;">
      <p style="font-size: 20px; font-weight: bold; text-align: left; color: #D5262B; margin: 0px 0px;"><strong>Join Club-100 and volunteer for a good cause! </strong>
      </p> 

      <p style="font-size: 16px; text-align: left; line-height: 24px; color: #000; margin: 10px 0px;">Did you know that North West Service Weeks is funded by <a style="font-weight: bold; color: #D5262B;" target="_new" href="https://northwest.cdc.gov.sg/programmes/connecting-the-community/club100-northwest/">Club-100 @ North West</a>? Founded by a community of passionate do-gooders, Club-100 members are united by a shared mission to give back to vulnerable residents in the North West District. Members of the club contribute at least $100 each month, which goes towards the North West Food Aid Fund.</p> 

      <p style="font-size: 16px; text-align: left; line-height: 24px; color: #000; margin: 10px 0px;">To join Club-100 as an individual or corporate member, or to volunteer your time and donate for a good cause, email us at <a style="font-weight: bold; color: #D5262B;" target="_new" href="mailto:northwestcdc_partnerships@pa.gov.sg">northwestcdc_partnerships@pa.gov.sg</a>.</p> 

  </div>
</div>
</div>
</div>






<!--Footer-->
<div style="padding: 20px 0px 0px; display: flex;" class="col-">&nbsp;</div>

<div style="width: 100%; background: #FB5C1F; border-radius: 30px; padding: 0px 0px; display: flex;">
  <div style="width: 100%; padding: 30px 10px 8px; text-align: center; margin: auto;">
    <h1 style="font-family:  Arial; font-size: xx-large; font-weight: bold; color: #FFFFFF; letter-spacing: normal !important;"><em>Keep updated with our latest stories!</em></h1>
    <a href="https://go.gov.sg/subscribe-cohesion" target="_new" style="text-decoration: none;">
      <div style="font-family:  Arial; font-size: large; font-weight: bold; background: #FFFFFF; color: #FB5C1F; padding: 10px 15px; max-width: 320px; margin: auto; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem; text-decoration: none;"><em>Subscribe to Cohesion Magazine</em>
      </div>
    </a>

    <div style="width: 100%;">
    <div style="width: 100%; padding: 15px 10px; text-align: center;   display: flex; justify-content: center; align-items: center;">
      <span style="font-family: Arial; font-weight: bold; font-size: large; color: #FFFFFF;">Follow us on</span>
      <a style="line-height: normal !important; margin-bottom: 0px !important;" href="https://www.facebook.com/nwcdc/" target="_new"><img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/square-facebook.png" style="padding: 5px 7px;"></a>
      <a style="line-height: normal !important; margin-bottom: 0px !important;" href="https://www.instagram.com/northwestcdc" target="_new"><img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/square-instagram.png" style="padding: 5px 7px;"></a>
      <a style="line-height: normal !important; margin-bottom: 0px !important;" href="https://t.me/northwestcdc" target="_new"><img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/telegram.png" style="padding: 5px 7px;"></a>
      <a style="line-height: normal !important; margin-bottom: 0px !important;" href="https://www.youtube.com/northwestcdc" target="_new"><img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/square-youtube.png" style="padding: 5px 7px;"></a>
    </div>
    </div>

    <div style="width: 100%; text-align: right;"><img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/nw-arrow.png" style="width: 25px; display: inline-block !important;"></div>

  </div>

</div>

<div style="padding: 40px 20px; text-align: center;">
  <h2 style="font-size: xx-large; font-weight: bold;"><em>Our Team</em></h2>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Adviser: Mayor Alex Yam</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Editorial Team: Michael Lau, Sim Chuan San, Steve Luo, Eric Liu, Melvin Tai, Charlene Koh</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Please send feedback, suggestions and comments to <a style="color: #000000; text-decoration: underline;" target="_new" href="mailto:northwest_cdc@pa.gov.sg">northwest_cdc@pa.gov.sg</a></p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Some articles in Cohesion are contributed by volunteers and are not necessarily opinions/comments by North&nbsp;West&nbsp;CDC.</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Reproduction in whole or in part is prohibited without prior permission from North West CDC.</p>
</div>
<!--Footer End-->


</article>


