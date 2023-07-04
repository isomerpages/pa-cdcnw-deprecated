---
title: North West WeCare Fund
permalink: /cohesion/july-2023/nw-wcf/
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

.w-100 {max-width: 100% !important;}

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
  <img style="width: 100%; max-width: 100px; position: relative;" alt="North West Cohesion" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/nw-cohesion-logo-2023%201.gif">
</div>

<div style="width: 100%;">
  <img style="width: 100%; max-width:" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/uplifting-the-community.png">
  <img style="width: 100%; max-width:" src="/images/Cohesion/July%202023/planting-seeds.png">
</div>

<div style="padding: 0px 0px 0px;">
<p style="font-size: 16px; line-height: 26px;">Building Empathy is one of Woodlands Secondary School (WDL)'s core values, to fulfil its mission in Nurturing Enduring Hearts and Creative Minds Ready to Serve Society.</p> 

<p style="font-size: 16px; line-height: 26px;">As part of WDL's Learning for Life Programme (LLP), every Woodlander (as the school's students are called) is given the platform to develop the skills and mindset to serve the community. Here, we have two Woodlander  journal their experiences in several ground-up initiatives supported by the North West WeCare Fund.</p>   

<p style="font-size: 16px; line-height: 26px;">Before planning their initiatives, the students participated in Ngee Ann Polytechnic's Dialogue in the Dark. The programme offers a unique and effective platform for the students to experience everyday situations - in complete darkness. With the experience, the students build stronger empathy and deeper understanding for the vulnerable in our community, to better plan their initiatives.</p>
</div>

<div style="max-width: 100%; padding: 15px 25px;">
  <img style="width: 100%; margin-top: 0px;" class="" src="/images/Cohesion/July%202023/jeffrey-saw.jpg">
</div>
<div style="max-width: 100%; padding: 15px 25px;">
  <img style="width: 100%; margin-top: 0px;" class="" src="/images/Cohesion/July%202023/eint-myo.jpg">
</div>

<div style="max-width: 100%; padding: 25px 0px 0px;">
  <img style="width: 100%; margin-top: 0px;" class="" src="/images/Cohesion/July%202023/starting-our-journey.png">
  <div style="-webkit-border-bottom-right-radius: 25px; -webkit-border-bottom-left-radius: 25px; -moz-border-radius-bottomright: 25px; -moz-border-radius-bottomleft: 25px; border-bottom-right-radius: 25px; border-bottom-left-radius: 25px; background: #A3D9EA;" class="w-100">
    <div style="padding: 25px 25px 35px; margin: 0px 0px;" class="w-100">
      <img style="width: 100%; margin-top: 0px; padding: 0px 0px 15px;" class="" src="/images/Cohesion/July%202023/journey1.png">
      
      <div style="padding: 10px 10px;" class="w-100">
      <img style="width: 100%; max-width: 103px; margin-top: 0px; padding: 0px 0px 15px;" class="" src="/images/Cohesion/July%202023/thumb-eint.png">
      <p style="margin: 0px 0px;">Today, we visited Dialogue in the Dark at Ngee Ann Poly. I went with an open mind, as I didn't know what to expect. Blindfolded, we relied on our other senses to complete tasks, revealing the challenges faced by the visually impaired in doing everyday things such as writing or crossing the road. The experience taught me to be grateful for what we have. It instilled empathy, helping me to better understand the struggles of others.</p>
      </div>

      <div style="padding: 10px 10px;" class="w-100">
      <img style="width: 100%; max-width: 103px; margin-top: 0px; padding: 0px 0px 15px;" class="" src="/images/Cohesion/July%202023/thumb-jeffrey.png">
      <p style="margin: 0px 0px;">Dialogue in the Dark was a unique and interesting experience, unlike other activities I'd done as a Youth Ambassador. We entered a room that was in complete darkness. With totally no vision, we had to navigate daily tasks such as crossing the road, buying food, eating and drinking. This experience allowed me to empathise with the visually impaired. I believe it will help me in my future interactions with people from all walks of life in the community. </p>
      </div>

    </div>
  </div>
</div>

<div style="max-width: 100%; padding: 25px 15px 0px;">
  <img style="width: 100%; margin-top: 0px;" class="" src="/images/Cohesion/July%202023/infusing.png">
</div>

<div style="max-width: 100%; padding: 25px 0px 0px;">
  <div style="-webkit-border-radius: 25px; -moz-border-radius: 25px; border-radius: 25px; background: #D7F3FC;" class="w-100">

    <div style="padding: 25px 25px 35px; margin: 0px 0px;" class="w-100">

      <img style="width: 100%; margin-top: 0px; padding: 0px 0px 15px;" class="" src="/images/Cohesion/July%202023/visit2.png">
      <img style="width: 100%; margin-top: 0px; padding: 0px 0px 15px;" class="" src="/images/Cohesion/July%202023/journey2.png">

      <div style="padding: 10px 10px;" class="w-100">
      <img style="width: 100%; max-width: 103px; margin-top: 0px; padding: 0px 0px 15px;" class="" src="/images/Cohesion/July%202023/thumb-jeffrey.png">
      <p style="margin: 0px 0px;">For the visit to the Sunlove Active Ageing Centre @ Marsiling, we planned various activities that we could do together with the elderly, such as ping pong, bingo, cup stacking, recycling old tees into tote bags, arts and crafts, and seated exercises. I organised the arts and crafts activities so we could also have conversations at the same time. It felt a lot like chatting with a grandparent, as they shared interesting stories! The visit concluded with us cooking porridge for the elderly - totally supervised of course! </p>
      </div>

    </div>

  </div>
</div>

<div style="max-width: 100%; padding: 25px 0px 0px;">
  <div style="-webkit-border-radius: 25px; -moz-border-radius: 25px; border-radius: 25px; background: #A3D9EA;" class="w-100">

    <div style="padding: 25px 25px 35px; margin: 0px 0px;" class="w-100">

      <img style="width: 100%; margin-top: 0px; padding: 0px 0px 15px;" class="" src="/images/Cohesion/July%202023/visit3.png">
      <img style="width: 100%; margin-top: 0px; padding: 0px 0px 15px;" class="" src="/images/Cohesion/July%202023/journey3.png">

      <div style="padding: 10px 10px;" class="w-100">
      <img style="width: 100%; max-width: 103px; margin-top: 0px; padding: 0px 0px 15px;" class="" src="/images/Cohesion/July%202023/thumb-eint.png">
      <p style="margin: 0px 0px;">The Block Party at Blocks 3 and 4 was a heartwarming occasion for the elderly residents. We set up game booths featuring traditional games, giant Jenga, bowling and more. An arts and crafts station offered sand art activity and Nagomi pastel art. Plus, there was plenty of delicious food. The karaoke session brought the most joy as the residents sang with gusto!  It was a wonderful way to end the school year, creating special memories for everyone.</p>
      </div>

      <div style="padding: 10px 10px;" class="w-100">
      <img style="width: 100%; max-width: 103px; margin-top: 0px; padding: 0px 0px 15px;" class="" src="/images/Cohesion/July%202023/thumb-jeffrey.png">
      <p style="margin: 0px 0px;">Visiting the senior residents from Blocks 3 and 4 is always full of fun and laughter. And one of the elderly that I had interacted with during the arts and crafts station at the Sunlove community was also at the Block Party! It was great to reconnect with her. There was popcorn, games and karaoke at the party. It was quite a fun-filled day for them and seeing their happy faces was also very fulfilling for&nbsp;us. </p>
      </div>

    </div>

  </div>
</div>


<div style="max-width: 100%; padding: 25px 0px 0px;">
  <div style="-webkit-border-radius: 25px; -moz-border-radius: 25px; border-radius: 25px; background: #D7F3FC;" class="w-100">

    <div style="padding: 25px 25px 35px; margin: 0px 0px;" class="w-100">

      <img style="width: 100%; margin-top: 0px; padding: 0px 0px 15px;" class="" src="/images/Cohesion/July%202023/visit4.png">
      <img style="width: 100%; margin-top: 0px; padding: 0px 0px 15px;" class="" src="/images/Cohesion/July%202023/journey4.png">

      <div style="padding: 10px 10px;" class="w-100">
      <img style="width: 100%; max-width: 103px; margin-top: 0px; padding: 0px 0px 15px;" class="" src="/images/Cohesion/July%202023/thumb-eint.png">
      <p style="margin: 0px 0px;">I joined the trip to Hort Park so I could better connect with the elderly. During the garden tour, those who were avid gardeners enjoyed the stories about the flowers and plants. At the terrarium workshop, we helped them make their own creations. Despite the initial language barrier, some of the elderly graciously switched to English so I could better understand them. It was a rewarding day that allowed me to listen and engage with them on a deeper level. </p>
      </div>

    </div>

  </div>
</div>

<div style="max-width: 100%; padding: 25px 0px 0px;">
  <img style="width: 100%; margin-top: 0px;" class="" src="/images/Cohesion/July%202023/reflections.jpg">
<div style="max-width: 100%; padding: 0px 0px;">
  <div style="-webkit-border-bottom-right-radius: 25px; -webkit-border-bottom-left-radius: 25px; -moz-border-radius-bottomright: 25px; -moz-border-radius-bottomleft: 25px; border-bottom-right-radius: 25px; border-bottom-left-radius: 25px; background: #EFF2FF;" class="w-100">

    <div style="padding: 25px 25px 35px; margin: 0px 0px;" class="w-100">

      <div style="padding: 10px 10px;" class="w-100">
      <img style="width: 100%; max-width: 103px; margin-top: 0px; padding: 0px 0px 15px;" class="" src="/images/Cohesion/July%202023/thumb-eint.png">
      <p style="margin: 0px 0px;">Participating in these experiences has been meaningful and eye-opening. Dialogue in the Dark helped me develop empathy for the visually impaired. The Hort Park trip deepened my bond with the elderly while the Block Party strengthened intergenerational connections taught me the importance of social cohesion and support. Overall, these experiences were meaningful and taught me valuable lessons. </p>
      </div>

      <div style="padding: 10px 10px;" class="w-100">
      <img style="width: 100%; max-width: 103px; margin-top: 0px; padding: 0px 0px 15px;" class="" src="/images/Cohesion/July%202023/thumb-jeffrey.png">
      <p style="margin: 0px 0px;">As a Youth Ambassador, I found fulfilment and enrichment in community engagement. Interacting with the elderly taught me to be more flexible and adaptable. Dialogue in the Dark highlighted the importance of putting myself in the shoes of the visually impaired and understand the problems that they face. By simply being present, engaging with the elderly in everyday activities and listening to their stories, we can make a difference in our own unique ways. </p>
      </div>

    </div>

  </div>
</div>
</div>

<div style="max-width: 100%; padding: 25px 0px 0px;">
  <img style="width: 100%; margin-top: 0px;" class="" src="/images/Cohesion/July%202023/april-quote.jpg">
</div>



<div style="padding: 20px 0px;">
<div style="width: 100%; background: #DFE2EF; padding: 0px 0px 0px;" class="rounded20">
  <div style="padding: 30px 40px;">
    <div style="padding: 0px 0px;">

        <p style="font-size: 16px; text-align: left; line-height: 24px; color: #000; margin: 10px 0px;">Ground-up initiatives can help foster greater understanding and empathy for others by creating opportunities for direct interaction and shared experiences.</p> 

        <p style="font-size: 16px; text-align: left; line-height: 24px; color: #000; margin: 10px 0px;">The North West WeCare Fund has supported Woodlands Secondary School in its Learning for Life programmes by helping to fund the following initiatives: </p>

        <ul style="padding: 0px 20px 0px 15px;">
          <li style="font-size: 16px; text-align: left; line-height: 24px; color: #000; padding-bottom: 10px;">Training for Youth Ambassadors at Dialogue in the Park at Ngee Ann Polytechnic (20&nbsp;October 2022)</li>

          <li style="font-size: 16px; text-align: left; line-height: 24px; color: #000; padding-bottom: 10px;">WDL Cares @ North West where students organised a Block Party (18 November) and brought residents from the Rental Blocks 3 and 4 at Marsiling Division to Hort Park (6&nbsp;December 2022) for them to bond as a community. </li>

          <li style="font-size: 16px; text-align: left; line-height: 24px; color: #000;">Care for Elderly @ North West where students visited seniors at Sunlove Active Ageing Centre @ Marsiling to befriend and interact with them through meaningful activities. (14&nbsp;July)</li>
        </ul>

        <p style="font-size: 16px; text-align: left; line-height: 24px; color: #000; margin: 10px 0px;">Find out more about the North West WeCare Fund <a style="font-weight: bold; color: #283F94;" target="_new" href="https://go.gov.sg/nw-wecare-fund">here</a>.</p>

  </div>
</div>
</div>
</div>


<!--Footer-->
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
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Some articles in Cohesion are contributed by volunteers and are not necessarily opinions/comments by North&nbsp;West&nbsp;CDC.</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Reproduction in whole or in part is prohibited without prior permission from North West CDC.</p>
</div>
<!--Footer End-->


</article>


