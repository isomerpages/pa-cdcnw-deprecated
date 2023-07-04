---
title: July At A Glance
permalink: /cohesion/july-2023/july-at-a-glance/
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

.col-1, .col-2, .col-3, .col-4, .col-5, .col-6, .col-7, .col-8, .col-9, .col-10, .col-11, .col-12 {float: left;}
.w-100 {width: 100%;}
.text-center {text-align: center;}

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
  <a href="https://northwest.cdc.gov.sg/cohesion/july-2023/july-at-a-glance">
    <img style="width: 100%; max-width: 100px; position: relative; padding-left: 10px;" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/nw-cohesion-logo-2023%201.gif">
  </a>
</div>

  <div style="background: #FFFFFF; margin: 30px 10px 0px; -webkit-border-radius: 35px; -moz-border-radius: 35px; border-radius: 35px;">
    <div style="width: 100%;">
      <img style="width: 100%; margin-top: 0px; -webkit-border-top-left-radius: 25px; -webkit-border-top-right-radius: 25px;-moz-border-radius-topleft: 25px; -moz-border-radius-topright: 25px; border-top-left-radius: 25px; border-top-right-radius: 25px;" class="" src="/images/Cohesion/July%202023/healthiersg-kv.gif">
    </div>

  <div style="background: #F9F9F9; padding: 30px 30px; -webkit-border-bottom-right-radius: 25px; -webkit-border-bottom-left-radius: 25px; -moz-border-radius-bottomright: 25px; -moz-border-radius-bottomleft: 25px; border-bottom-right-radius: 25px; border-bottom-left-radius: 25px;">
    <h2 style="color: #CE8EBE; font-weight: bold; font-size: x-large;">
      <strong>CrossFit Journey of 2 North&nbsp;West Residents</strong>
    </h2>
    <p style="font-size: 16px; line-height: 26px;">Age is just a number for our senior CrossFit enthusiasts in the North West FitnessX club. In this #kopitalk session, we speak to Eillron and Wendy to find out what motivated them to start their fitness journey, and how it has impacted their health for the&nbsp;better.</p>
    <div style="max-width: 100%; text-align: center; padding: 30px 15px 15px;"><a style="background: #CE8EBE; color: #FFFFFF; padding: 15px 25px; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem; font-size: medium; font-family: Arial, 'sans-serif;'; text-decoration: none; text-transform: uppercase; min-width: 150px;" href="https://northwest.cdc.gov.sg/cohesion/july-2023/kopi-talk-healthchamps"><em>Read On</em></a></div>
  </div>
  </div>



<div style="width: 100%;">
  
  <div class="col-6">
    <div style="max-width: 100%; padding: 10px 10px;">
    <div style="background: #FFFFFF; margin: 30px 0px 0px; -webkit-border-radius: 25px; -moz-border-radius: 25px; border-radius: 25px;">
  <div style="width: 100%;">
    <img style="width: 100%; margin-top: 0px; -webkit-border-top-left-radius: 25px; -webkit-border-top-right-radius: 25px;-moz-border-radius-topleft: 25px; -moz-border-radius-topright: 25px; border-top-left-radius: 25px; border-top-right-radius: 25px;" class="" src="/images/Cohesion/July%202023/volunteers-edm-kv.jpg">
  </div>
  <div style="background: #F9F9F9; padding: 30px 30px; -webkit-border-bottom-right-radius: 25px; -webkit-border-bottom-left-radius: 25px; -moz-border-radius-bottomright: 25px; -moz-border-radius-bottomleft: 25px; border-bottom-right-radius: 25px; border-bottom-left-radius: 25px; min-height: 370px;">
    <h2 style="color: #BB1415; font-weight: bold; font-size: x-large;">
      <strong>Volunteers Bring Fun and Food to Those in&nbsp;Need</strong>
    </h2>
    <p style="font-size: 16px; line-height: 26px;">This Service Weeks, on top of running the Pop-Up Market to distribute food packs to needy residents, over 100 parent volunteers and students from Northland Primary School came together to organise a fun-filled carnival for Nee Soon South residents living in the public rental flats.</p>
    <div style="max-width: 100%; text-align: center; padding: 30px 15px 15px;"><a style="background: #BB1415; color: #FFFFFF; padding: 15px 25px; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem; font-size: medium; font-family: Arial, 'sans-serif;'; text-decoration: none; text-transform: uppercase; min-width: 150px;" href="https://northwest.cdc.gov.sg/cohesion/july-2023/sw-volunteersdayout"><em>Find Out More</em></a></div>
  </div>
  </div>
  </div>
  </div>

  <div class="col-6">
  <div style="max-width: 100%; padding: 10px 10px;">
    <div style="max-width: 100%; padding: 0px 0px 0px; background: #FFFFFF; margin: 30px 0px 0px; -webkit-border-radius: 25px; -moz-border-radius: 25px; border-radius: 25px;">
  <div style="width: 100%;">
    <img style="width: 100%; margin-top: 0px; -webkit-border-top-left-radius: 25px; -webkit-border-top-right-radius: 25px;-moz-border-radius-topleft: 25px; -moz-border-radius-topright: 25px; border-top-left-radius: 25px; border-top-right-radius: 25px;" class="" src="/images/Cohesion/July%202023/go-green-kv-4.gif">
  </div>
  <div style="background: #F9F9F9; padding: 30px 30px; -webkit-border-bottom-right-radius: 25px; -webkit-border-bottom-left-radius: 25px; -moz-border-radius-bottomright: 25px; -moz-border-radius-bottomleft: 25px; border-bottom-right-radius: 25px; border-bottom-left-radius: 25px; min-height: 370px; position: relative;">
    <h2 style="color: #0C6C37; font-weight: bold; font-size: x-large;">
      <strong>Join our #GetGreen Challenge Towards a Sustainable Future</strong>
    </h2>
    <p style="font-size: 16px; line-height: 26px;">Discover how practicing simple green habits by joining our various Green programmes can make a positive impact on the environment. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
    </p> 

    <div style="max-width: 100%; text-align: center; padding: 30px 15px 15px;"><a style="background: #0C6C37; color: #FFFFFF; padding: 15px 25px; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem; font-size: medium; font-family: Arial, 'sans-serif;'; text-decoration: none; text-transform: uppercase; min-width: 150px;" href="https://northwest.cdc.gov.sg/cohesion/july-2023/getgreen-challenge"><em>Join Now</em></a>
    </div>

  </div>
  </div>
    </div>
  </div>

</div>


<div style="max-width: 100%; padding: 10px 0px;" class="col-12">
  <div style="background: #FFFFFF; margin: 30px 10px 0px; -webkit-border-radius: 35px; -moz-border-radius: 35px; border-radius: 35px;">
    <div style="width: 100%;">
      <img style="width: 100%; margin-top: 0px; -webkit-border-top-left-radius: 25px; -webkit-border-top-right-radius: 25px;-moz-border-radius-topleft: 25px; -moz-border-radius-topright: 25px; border-top-left-radius: 25px; border-top-right-radius: 25px;" class="" src="/images/Cohesion/July%202023/planting-seeds-kv.jpg">
    </div>

  <div style="background: #F9F9F9; padding: 30px 30px; -webkit-border-bottom-right-radius: 25px; -webkit-border-bottom-left-radius: 25px; -moz-border-radius-bottomright: 25px; -moz-border-radius-bottomleft: 25px; border-bottom-right-radius: 25px; border-bottom-left-radius: 25px;">
    <h2 style="color: #283F94; font-weight: bold; font-size: x-large;">
      <strong>Planting Seeds of Empathy Through Community Initiatives  </strong>
    </h2>
    <p style="font-size: 16px; line-height: 26px;">Students from Woodlands Secondary School learn the importance of empathy through meaningful interactions with vulnerable residents and initiating ground-up projects funded by the North West WeCare Fund.</p>
    <div style="max-width: 100%; text-align: center; padding: 30px 15px 15px;">
      <a style="background: #283F94; color: #FFFFFF; padding: 15px 25px; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem; font-size: medium; font-family: Arial, 'sans-serif;'; text-decoration: none; text-transform: uppercase; min-width: 150px;" href="https://northwest.cdc.gov.sg/cohesion/july-2023/nw-wcf">
        <em>Discover More</em>
      </a>
    </div>
  </div>
  </div>
</div>



<div style="max-width: 100%; padding: 10px 0px;" class="col-12">
  <div style="background: #f9f9f9; margin: 30px 10px 0px; -webkit-border-radius: 25px; -moz-border-radius: 25px; border-radius: 25px;">
    <div style="width: 100%;">
      <div style="background: #FE5D1F; margin: 30px 0px 0px; -webkit-border-top-left-radius: 25px; -webkit-border-top-right-radius: 25px; -moz-border-radius-topleft: 25px; -moz-border-radius-topright: 25px; border-top-left-radius: 25px; border-top-right-radius: 25px;">
        <div style="text-align: center; display: flex; justify-content: center; align-items: center; margin: 0px auto; padding: 15px 15px; color: #FFFFFF; text-transform: uppercase; font-size:  x-large; font-family: Arial, 'sans-serif';"><em>What's Up</em> <img style="padding: 0px 10px; max-width: 30px;" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/nw-arrow.png"></div>
      </div>
    </div>

    <div style="width: 100%; padding: 10px 0px; display: inline-block;">

    <div class="col-12 w-100">
      <div class="col-4 text-center">
        <div style="padding: 30px 20px 0px;">
          <img style="max-width: 120px;" src="/images/Cohesion/July%202023/skillsfuture.png">
        </div>
      </div>
      <div class="col-8">
        <div style="padding: 10px 2rem;">
          <h2 style="color: #FE5D1F; font-family: Arial, 'sans-serif'; margin-bottom: 0px;"><em>SkillsFuture Festival @ North West  </em></h2>
          <h4 style="color: #FE5D1F; font-family: Arial, 'sans-serif'; margin-top: 10px;">15-16 Jul 2023 | 10am - 7pm (Sat), 10am - 4pm (Sun) Kampung Admiralty Community Plaza</h4>
          <p style="font-size: 16px; line-height: 26px; padding-right: 5px;">Take that next step to advance your career and check out the SkillsFuture Festival @ North West! We’ve planned an interesting line-up of workshops and talks to elevate your lifelong learning journey and boost your career prospects. Get personalised advice from our SkillsFuture and Career Ambassadors, participate in walk-in job interviews and discover valuable upskilling initiatives!  </p>
          <div style="max-width: 100%; text-align: left; padding: 30px 0px;">
            <a style="background: #FE5D1F; color: #FFFFFF; padding: 15px 25px; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem; font-size: medium; font-family: Arial, 'sans-serif;'; text-decoration: none; text-transform: uppercase; min-width: 150px;" href="https://go.gov.sg/sfanorthwest">
              <em>Sign Up Now</em>
            </a>
          </div>
        </div>
      </div>
      <hr style="margin: 0px 30px; border: thin solid #ebebeb;">
    </div>

    <div class="col-12 w-100">
      <div class="col-4 text-center">
        <div style="padding: 30px 20px 0px;">
          <div style="background-image: url('/images/Cohesion/July%202023/sg58%20national%20day.gif'); background-color: #f9f9f9; background-blend-mode: darken; min-height: 120px; background-repeat: no-repeat; background-size: contain;  max-width: 120px; width: 100%; margin: auto;">

      </div>
          <!--<img src="/images/Cohesion/July%202023/sg58%20national%20day.gif" style="max-width: 120px;">-->
        </div>
      </div>
      <div class="col-8">
        <div style="padding: 10px 2rem;">
          <h2 style="color: #FE5D1F; font-family: Arial, 'sans-serif';"><em>Join us in celebrating Singapore's 58th National Birthday!</em></h2>
          <p style="font-size: 16px; line-height: 26px; padding-right: 5px; letter-spacing: 0.2px;">Share your heartfelt video wishes for our nation's birthday and stand a chance to win exciting prizes! Hurry, deadline is 31&nbsp;July&nbsp;2023!<br><br> 
Visit our social pages for submission details.</p>
          <div style="max-width: 100%; text-align: left; padding: 30px 0px;">
            <a style="background: #FE5D1F; color: #FFFFFF; padding: 15px 25px; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem; font-size: medium; font-family: Arial, 'sans-serif;'; text-decoration: none; text-transform: uppercase; min-width: 150px;" target="_new" href="#">
              <em>Join Now</em>
            </a>
          </div>
        </div>
      </div>
      <hr style="margin: 0px 30px; border: thin solid #ebebeb;">
    </div>

    <div class="col-12 w-100">
      <div class="col-4 text-center">
        <div style="padding: 30px 20px 0px;">
          <img style="max-width: 120px;" src="/images/Cohesion/July%202023/july-happening.png">
        </div>
      </div>
      <div class="col-8">
        <div style="padding: 10px 2rem;">
          <h2 style="color: #FE5D1F; font-family: Arial, 'sans-serif'; margin-bottom: 0px;"><em>What's happening in July  </em></h2>

          <p style="font-size: 16px; line-height: 26px; padding-right: 5px;">Don’t miss out on other exciting activities in the North West community this July. Check out our social post for upcoming programmes such as Green Bootcamp @ North West and FAM&nbsp;K @ North West that you won’t want to miss! Subscribe to our Facebook page to stay updated on events happening in your&nbsp;neighbourhood!</p>
          <div style="max-width: 100%; text-align: left; padding: 30px 0px;">
            <a style="background: #FE5D1F; color: #FFFFFF; padding: 15px 25px; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem; font-size: medium; font-family: Arial, 'sans-serif;'; text-decoration: none; text-transform: uppercase; min-width: 150px;" target="_new" href="#">
              <em>Check It Out</em>
            </a>
          </div>
        </div>
      </div>
    </div>

    </div>

  </div>
</div>


<div style="max-width: 100%; padding: 30px 0px 40px; display: block;" class="col-12">
  <div class="col-12">
    <div style="padding: 0px 10px;">
      <div style="width: 100%; background: #FB5C1F; border-radius: 30px; padding: 0px 0px 20px; display: flex;">
        <div style="width: 100%; padding: 10px 10px; text-align: center; margin: auto;">
          <h1 style="font-family:  Arial; font-size: xx-large; font-weight: bold; color: #FFFFFF;"><em>Know an interesting or inspiring story?</em></h1>
          <a style="text-decoration: none;" target="_new" href="https://go.gov.sg/subscribe-cohesion">
            <div style="font-family:  Arial; font-size: large; font-weight: bold; background: #FFFFFF; color: #FB5C1F; padding: 15px 15px; max-width: 200px; margin: auto; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem; text-decoration: none; text-transform: uppercase;"><em>Tell Us More</em>
            </div>
          </a>
        </div>
      </div>
    </div>
  </div>
</div>


</article>

<div style="display: inline-block; width: 100%;">

    <div style="max-width: 800px; width: 100%; margin: auto;">

    <div style="width: 100%; padding: 15px 0px; text-align: center;">
      <div><em><h2 style="color: #331E16; font-family: Arial, 'sans-serif';">For the latest events and happenings,<br><span style="text-transform: uppercase;">Follow Us On</span></h2></em></div>
      <a target="_new" href="https://www.facebook.com/nwcdc/"><img style="padding: 5px 7px;" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/square-facebook-orange.png"></a>
      <a target="_new" href="https://www.instagram.com/northwestcdc"><img style="padding: 5px 7px;" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/square-instagram-orange.png"></a>
      <a target="_new" href="https://t.me/northwestcdc"><img style="padding: 5px 7px;" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/telegram-orange.png"></a>
      <a target="_new" href="https://www.youtube.com/northwestcdc"><img style="padding: 5px 7px;" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/square-youtube-orange.png"></a>
    </div>

    </div>

<div style="max-width: 800px; width: 100%; margin: auto; text-align: center;">
  <div style="width: 100%; padding: 20px 0px;">
  <h2 style="font-size: xx-large; font-weight: bold;"><em>Our Team</em></h2>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Adviser: Mayor Alex Yam</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px; padding: 0px 20px;">Editorial Team: Michael Lau, Sim Chuan San, Steve Luo, Eric Liu, Melvin&nbsp;Tai, Charlene&nbsp;Koh</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px; padding: 0px 20px;">Please send feedback, suggestions and comments to <a style="color: #000000; text-decoration: underline;" target="_new" href="mailto:northwest_cdc@pa.gov.sg">northwest_cdc@pa.gov.sg</a></p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px; padding: 0px 20px;">Some articles in Cohesion are contributed by volunteers and are not necessarily opinions/comments by North&nbsp;West&nbsp;CDC.</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px; padding: 0px 20px;">Reproduction in whole or in part is prohibited without prior permission from North&nbsp;West&nbsp;CDC.</p>
  </div>
</div>

</div>