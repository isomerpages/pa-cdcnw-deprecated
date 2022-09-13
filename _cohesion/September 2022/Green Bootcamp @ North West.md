---
title: Green Bootcamp @ North West
permalink: /cohesion/September-2022/green-bootcamp-north-west/
description: ""
third_nav_title: September 2022
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

  </style>
</head>
<body>
<article style="max-width: 800px; width: 100%; margin: auto;">
<div style="width: 100%;">
  <img src="/images/cohesion_logo.gif" style="width: 100%; max-width: 133px; margin-left: -22px;">
</div>


<div>
  <img src="/images/bootcamp_03.jpg" style="width: 100%; margin-top: 0px;">
</div>

<p style="font-size: 16px; line-height: 26px; margin-top: 30px;"><img src="/images/bootcamp_07.jpg" style="width: 100%; max-width: 124px;" align="right" />
  Green Bootcamp @ North West was launched in July 2022, to provide a platform for youths to ideate and lead the way as green change makers in the community. Youths were pushed to think out of the box with this year's problem statement: How might your team influence the community to adopt sustainable practices into their daily lives? <br/><br/>This programme was made possible by a collaboration between North West CDC and the Growth & Opportunities (GO!) committee under the umbrella of NTU Welfare Services Club (WSC). GO! prides itself in raising awareness on various social issues such as sustainability, community impact, volunteerism, and more! Over 70 youths from various Institutes of Higher Learning (IHLs) joined the two-week hybrid bootcamp, where they went through a series of insightful talks and workshops.
</p>


  <ul class="timeline">
    <li class="event" style="font-size: 16px; line-height: 26px; margin-top: 0px;">
      <h3 style="color: #0c6c37; font-size: large; line-height: initial;"><b>18 to 22 July</b></h3>
      <p style="font-size: 16px; line-height: 26px; margin-top: 0px;">Participants were given access to recorded talks and workshops to equip themselves with useful knowledge and skills, such as critical thinking, details of green initiatives and programmes, and presentation skills, to prepare their proposals. </p>
    </li>
    <li class="event" style="font-size: 16px; line-height: 26px; margin-top: 0px;">
      <h3 style="color: #0c6c37; font-size: large; line-height: initial;"><b>23 July</b></h3>
      <p style="font-size: 16px; line-height: 26px; margin-top: 0px;">The participants gathered at NTU for physical activities and more workshops that introduced them to the green community in Singapore. Subject experts inspired the participants to think of solutions that could influence the community to take action towards climate change.</p>    
    </li>
    <li class="event" style="font-size: 16px; line-height: 26px; margin-top: 0px;">
      <h3 style="color: #0c6c37; font-size: large; line-height: initial;"><b>30 July</b></h3>
      <p style="font-size: 16px; line-height: 26px; margin-top: 0px;">20 proposals were whittled down to the final 10, which were pitted against each other during the final pitching.</p>

      <p style="font-size: 16px; line-height: 26px; margin: 5px 0px;"><b>Ideas ranged from:</b>
        <ul style="padding: 0px 0px;margin-left: 20px; margin-top: 0px;">
          <li style="list-style: disc; font-size: 16px; line-height: initial;">Incorporating food composting within the school syllabus</li> 
          <li style="list-style: disc; font-size: 16px; line-height: initial;">Producing a green game show to raise public awareness </li>
          <li style="list-style: disc; font-size: 16px; line-height: initial;">Transforming plastic waste into new products using 3D printing</li>
        </ul>
      </p>    
    </li>
  </ul>




<p style="font-size: 16px; line-height: 26px; margin-top: 30px;">Green Bootcamp @ North West truly showcased the creative thinking and determination of the youths who want to make a difference to the world we live in.</p>    

<p style="font-size: 16px; line-height: 26px; margin-top: 0px;">The top three teams were selected based on their proposal's creativity and feasibility. To help not only the top three teams but all participants bring their ideas to life, the CDC would be providing various avenues of support, such as funding the projects and connecting with partners who are subject matter experts. </p>

<h2 style="font-weight: bold; font-size: x-large;">Team Igloo - 1st Prize Winner</h2>


<div class="carousel">
    <div class="carousel-inner">
        <input class="carousel-open" type="radio" id="carousel-1" name="carousel" aria-hidden="true" hidden="" checked="checked">
        <div class="carousel-item">
            <img src="/images/team1-slide1.jpg" style="width: 100%;" />
        </div>
        <input class="carousel-open" type="radio" id="carousel-2" name="carousel" aria-hidden="true" hidden="">
        <div class="carousel-item">
            <img src="/images/team1-slide2.png" style="width: 100%;" />
        </div>
        <input class="carousel-open" type="radio" id="carousel-3" name="carousel" aria-hidden="true" hidden="">
        <div class="carousel-item">
            <img src="/images/team1-slide3.png" style="width: 100%;" />
        </div>
        <label for="carousel-3" class="carousel-control prev control-1">&#8249;</label>
        <label for="carousel-2" class="carousel-control next control-1">&#8250;</label>
        <label for="carousel-1" class="carousel-control prev control-2">&#8249;</label>
        <label for="carousel-3" class="carousel-control next control-2">&#8250;</label>
        <label for="carousel-2" class="carousel-control prev control-3">&#8249;</label>
        <label for="carousel-1" class="carousel-control next control-3">&#8250;</label>
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



<p style="font-weight: bold; font-size: 16px; line-height: 26px; ">Project Summary</p>
<p style="font-size: 16px; line-height: 26px; margin-top: 0px;">The winning team of the Green Bootcamp @ North West, Team Igloo, which comprised a mix of budding doctors and engineers, shared their aspiration of eradicating inefficient energy usage. The team developed a product that uses a thermoelectrical device to simultaneously cool and circulate water through a mattress pad, keeping the surface cool for users to sleep on.   </p>



<div class="slider slider--cover">

  <div class="slider__inner" style="background: #008500; border-radius: 30px;">
    <input checked type="radio" name="slider__radiobox" id="slider__radiobox--1" class="slider__radiobox slider__radiobox--1">
    <label for="slider__radiobox--1" class="slider__radiobox-label slider__radiobox-label--item slider__radiobox-label--item-1" style="visibility: hidden;"></label>
    <label for="slider__radiobox--2" class="slider__radiobox-label slider__radiobox-label--next slider__radiobox-label--next-2"></label>
    <input type="radio" name="slider__radiobox" id="slider__radiobox--2" class="slider__radiobox slider__radiobox--2">
    <label for="slider__radiobox--2" class="slider__radiobox-label slider__radiobox-label--item slider__radiobox-label--item-2" style="visibility: hidden;"></label>
    <label for="slider__radiobox--1" class="slider__radiobox-label slider__radiobox-label--prev slider__radiobox-label--prev-1"></label>

    <div style="position:absolute; left:0;"><img src="/images/Cohesion/Sept%202022/quote_1.png"></div>
    <div style="position: absolute; bottom: 0; right: 0;"><img src="/images/Cohesion/Sept%202022/quote_2.png"></div>
    <div class="slider__slides">
      <div class="slider__slide slider__slide--1" >
        <div style="width:  100%; text-align: center; margin: 0; position: absolute; top: 50%; transform: translateY(-50%);"><p class="slide-txt"><em>The excessive use of air-conditioning has become a norm in Singapore. Why do we need the whole room to be cooled if we are only sleeping on our beds? This triggered us to come up with the idea of Igloo. Participating in the Green Bootcamp was an excellent platform for us to network and meet other like-minded individuals. The feedback we received from the judges was also very valuable for us to continue improving our product.</em></p>
          <p style="font-size: 16px; line-height: initial; margin-top: 0px; color: #FFFFFF; padding-bottom: 30px;"><em><span style="font-size: 16px;">-Matthew Chew, Co-lead</span><br/>
<span style="font-size: 15px;">Team Igloo - 1st Prize Winner</span></em></p>
        </div>
      </div>
      <div class="slider__slide slider__slide--2">
        <div style="width:  100%; text-align: center; margin: 0; position: absolute; top: 50%; transform: translateY(-50%);"><p class="slide-txt"><em>The opportunity to meet the other teams, who came from various backgrounds, was very eye-opening for us. It was interesting to see the different approaches taken, some from an environment engineering perspective, some from a marketing point-of-view, or from a software angle.</em></p>
          <p style=" font-size: 16px; line-height: initial; margin-top: 0px; color: #FFFFFF;"><em><span style="font-size: 16px;">-Victoria, Co-lead</span><br/>
<span style="font-size: 15px;">Team Igloo - 1st Prize Winner</span></em></p>
        </div>
      </div>

    </div>
  </div>
</div>


<h2 style="font-weight: bold; font-size: x-large;">Team Dispose & Compose - 2nd Prize Winner</h2>



<div class="carousel">
    <div class="carousel-inner">
        <input class="carousel-open" type="radio" id="carousel-12" name="carousel2" aria-hidden="true" hidden="" checked="checked">
        <div class="carousel-item">
            <img src="/images/team2-slide1.jpg" style="width: 100%;" />
        </div>
        <input class="carousel-open" type="radio" id="carousel-22" name="carousel2" aria-hidden="true" hidden="">
        <div class="carousel-item">
            <img src="/images/team2-slide2.png" style="width: 100%;" />
        </div>
        <input class="carousel-open" type="radio" id="carousel-32" name="carousel2" aria-hidden="true" hidden="">
        <div class="carousel-item">
            <img src="/images/team2-slide3.png" style="width: 100%;" />
        </div>
        <label for="carousel-32" class="carousel-control prev control-1">&#8249;</label>
        <label for="carousel-22" class="carousel-control next control-1">&#8250;</label>
        <label for="carousel-12" class="carousel-control prev control-2">&#8249;</label>
        <label for="carousel-32" class="carousel-control next control-2">&#8250;</label>
        <label for="carousel-22" class="carousel-control prev control-3">&#8249;</label>
        <label for="carousel-12" class="carousel-control next control-3">&#8250;</label>
        <ol class="carousel-indicators">
            <li>
                <label for="carousel-12" class="carousel-bullet">•</label>
            </li>
            <li>
                <label for="carousel-22" class="carousel-bullet">•</label>
            </li>
            <li>
                <label for="carousel-32" class="carousel-bullet">•</label>
            </li>
        </ol>
    </div>
</div>


<p style="font-weight: bold; font-size: 16px; line-height: 26px;">Project Summary</p>
<p style="font-size: 16px; line-height: 26px; margin-top: 0px;">Food waste is a growing problem in Singapore, and in hopes to educate their peers on the harmful consequences of food wastage, the team came up with the idea of composting food waste into viable bio-materials that can be used to grow more food. Incorporating education and the cultivation of a habit, the DIY Home Composting Kits would be readily available in schools for youths to take home.  </p>

<div class="slider slider--cover" style="height: auto; padding: 20px 0px;">
  <div class="slider__inner" style="background: #008500; border-radius: 30px;">
    <div style="position:absolute; left:0;"><img src="/images/Cohesion/Sept%202022/quote_1.png"></div>
    <div style="position: absolute; bottom: 0; right: 0;"><img src="/images/Cohesion/Sept%202022/quote_2.png"></div>
    <div class="slider__slides">
      <div class="slider__slide slider__slide--1" >
                <div style="width:  100%; text-align: center; margin: 0; position: absolute; top: 50%; transform: translateY(-50%);"><p class="slide-txt"><em>It's never too late, and it's never too small, to start making changes to live a greener life. Sustainability and a green lifestyle are journeys, not destinations. Setbacks are normal, but for the sake of those that come after us, we must not give up our efforts.</em></p>
                <p style="color: #FFFFFF; line-height: initial;"><em><span style="font-size: 16px; line-height: initial; margin-top: 0px;">-Derrick, Team Leader</span><br/>
<span style="font-size: 15px;">Team Dispose and Compose - 2nd Prize Winner </span></em></p>
                </div>
      </div>
    </div>
  </div>
</div>



<h2 style="font-weight: bold; font-size: x-large;">Team BYOC Buddy - 3rd Prize Winner</h2>

<div class="carousel">
    <div class="carousel-inner">
        <input class="carousel-open" type="radio" id="carousel-13" name="carousel3" aria-hidden="true" hidden="" checked="checked">
        <div class="carousel-item">
            <img src="/images/team3-slide1.jpg" style="width: 100%;" />
        </div>
        <input class="carousel-open" type="radio" id="carousel-23" name="carousel3" aria-hidden="true" hidden="">
        <div class="carousel-item">
            <img src="/images/team3-slide2.png" style="width: 100%;" />
        </div>
        <input class="carousel-open" type="radio" id="carousel-33" name="carousel3" aria-hidden="true" hidden="">
        <div class="carousel-item">
            <img src="/images/team3-slide3.png" style="width: 100%;" />
        </div>
        <label for="carousel-33" class="carousel-control prev control-1">&#8249;</label>
        <label for="carousel-23" class="carousel-control next control-1">&#8250;</label>
        <label for="carousel-13" class="carousel-control prev control-2">&#8249;</label>
        <label for="carousel-33" class="carousel-control next control-2">&#8250;</label>
        <label for="carousel-23" class="carousel-control prev control-3">&#8249;</label>
        <label for="carousel-13" class="carousel-control next control-3">&#8250;</label>
        <ol class="carousel-indicators">
            <li>
                <label for="carousel-13" class="carousel-bullet">•</label>
            </li>
            <li>
                <label for="carousel-23" class="carousel-bullet">•</label>
            </li>
            <li>
                <label for="carousel-33" class="carousel-bullet">•</label>
            </li>
        </ol>
    </div>
</div>

<p style="font-weight: bold; font-size: 16px; line-height: 26px;">Project Summary</p>
<p style="font-size: 16px; line-height: 26px; margin-top: 0px;">To tackle the issue of increased use of disposable food packaging, the team proposed a national strategy to infuse sustainability into our local hawker culture. Their proposal outlines a multi-phased approach, starting with the introduction of a standard set of reusable containers for customers to take-away food from their favourite hawker stalls, creating new social and behavioural habits within the community. The second phase will set up an infrastructure that encourages and incentivises the use of reusable containers and utensils, followed by establishing a legislation for a nationwide ban on disposables.</p>

<div class="slider slider--cover" style="height: auto; padding: 20px 0px;">
  <div class="slider__inner" style="background: #008500; border-radius: 30px;">
    <div style="position:absolute; left:0;"><img src="/images/Cohesion/Sept%202022/quote_1.png"></div>
    <div style="position: absolute; bottom: 0; right: 0;"><img src="/images/Cohesion/Sept%202022/quote_2.png"></div>
    <div class="slider__slides">
      <div class="slider__slide slider__slide--1" >
                <div style="width:  100%; text-align: center; margin: 0; position: absolute; top: 50%; transform: translateY(-50%);"><p class="slide-txt"><em>Our idea comes from our core belief that big changes start with small ones. I don't think any of us can be considered truly environmentally-friendly, but we do try our best. Taking big steps can be very challenging, but small actions can add up, such as using reusable utensils!</em></p>
                <p style="color: #FFFFFF; line-height: initial; margin-top: 0px;"><em><span style="font-size: 15px;">-James, Team Leader</span><br/>
<span style="font-size: 15px; line-height: initial; margin-top: 0px;">Team BYOC Buddy - 3rd Prize Winner</span></em></p>
                </div>
      </div>
    </div>
  </div>
</div>



<div class="col-" style="padding: 20px 0px; display: flex;">&nbsp;</div>

<div style="width: 100%; background: #fb6e36; border-radius: 30px; padding: 20px 0px; display: flex;">
  <div style="padding: 10px 10px; text-align: center; margin: auto;">
  <div class="col-5" style="float: left; text-align: center;">
    <img src="/images/Cohesion/Sept%202022/megaphone.png" style="width: 100%; max-width: 290px; margin: auto;">
  </div>
  <div class="col-7" style="float: left; text-align: center;">
    <div>
      <a href="https://go.gov.sg/subscribe-cohesion" target="_new" style="cursor: default;"><img src="/images/Cohesion/Sept%202022/subscribe-cta.png" style="width: 100%; max-width: 397px;"></a>
    </div>


<div style="width: 100%; margin: 0px auto; text-align: center;">
<div style="margin: 0px auto; display: inline-block;">
  <div style="float:left; max-width: 128px;">
  <img src="/images/Cohesion/Sept%202022/follow-us.png" style="max-width: 128px;">
  </div>
  <div style="float:left; max-width: 47px;">
  <a href="https://www.facebook.com/nwcdc/" target="_new"><img src="/images/Cohesion/Sept%202022/fb.png" style="max-width: 39px;"></a>
  </div>
  <div style="float:left; max-width: 49px;">
  <a href="https://www.instagram.com/northwestcdc" target="_new"><img src="/images/Cohesion/Sept%202022/ig.png" style="max-width: 40px;"></a>
  </div>
  <div style="float:left; max-width: 41px;">
  <a href="https://t.me/northwestcdc" target="_new"><img src="/images/Cohesion/Sept%202022/tg.png" style="max-width: 46px;"></a>
  </div>
  <div style="float:left; max-width: 48px;">
  <a href="https://www.youtube.com/northwestcdc" target="_new"><img src="/images/Cohesion/Sept%202022/yt.png" style="max-width: 53px;"></a>
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
</body>
</html>