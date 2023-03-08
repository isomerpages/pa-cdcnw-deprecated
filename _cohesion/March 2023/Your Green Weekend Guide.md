---
title: Your Green Weekend Guide
permalink: /cohesion/March-2023/green-weekend-guide/
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
  <img src="images/cohesion_logo.gif" style="width: 100%; max-width: 200px; z-index: 99; position: relative; margin-left: -20px;">
</div>

<div>
  <img src="images/advocating-green-living.jpg" style="width: 100%; margin-top: 0px;">
</div>

<div>
	<img src="images/green-living_kv.jpg" style="width: 100%; margin-top: 0px;">
</div>

<div style="padding: 0px 0px;">
<p style="font-size: 16px; line-height: 26px;">Did you know that the North West District has various initiatives to encourage sustainable living in the community? From community farming to recycling, discover new ways to live a more eco-conscious life while connecting with fellow residents. Through these weekend activities, we hope you will be inspired to be kinder to the planet!  </p>   
</div>


<div style="padding: 3px 0px 0px;">
<h2 style="color: #D5262B; font-weight: bold; font-size: x-large; margin-bottom: 0px;">
  <strong>1. Get ready to enjoy community farming  </strong>
</h2>
</div>

<div style="padding: 0px 0px;">
<p style="font-size: 16px; line-height: 26px;">Get into the kampung spirit by growing your own crops with fellow residents! One of Singapore's largest community farms will be coming to Nee Soon East by year-end. Soon, you'll have the chance to enjoy this unique farm-to-table experience. </p>

<p style="font-size: 16px; line-height: 26px;">A project by the Nee Soon East cause-based group, the Community Farm will be designed and built using recycled materials. Located at an open field opposite Block 320 Yishun Central, the farm will have 12 planter beds that can be used to grow a variety of different vegetables.</p>  

<p style="font-size: 16px; line-height: 26px;">Feel a sense of pride from cultivating and harvesting your own fresh produce! At the same time, make new friends and connect with nature in a fun and meaningful way.</p>

<p style="font-size: 16px; line-height: 26px;">Join us on every 2<sup>nd</sup> Sunday morning of the month to plant and harvest fresh produce at the farm. Foster community bonding, meet like minded individuals and learn about farming.</p>   
</div>

<div>
  <img src="images/recycle5.png" class="rounded20" style="width: 100%; margin-top: 0px;">
</div>


<div style="padding: 30px 0px 0px;">
<h2 style="color: #D5262B; font-weight: bold; font-size: x-large; margin-top: 0px;">
  <strong>2. Turn trash to treasure: Join us in building a nature playground together  </strong>
</h2>
</div>

<div style="padding: 0px 0px;">
<p style="font-size: 16px; line-height: 26px;">Calling all outdoor enthusiasts, nature lovers and families! We're inviting you to join us in building an eco-friendly nature playground together. Get down and dirty with Mother Nature to create fun memories while unleashing your inner creativity. </p>  

<p style="font-size: 16px; line-height: 26px;">Designed and built by the community for the community, this project by Nee Soon East cause-based group will see discarded waste and materials such as wooden pallets, cut down tree trunks and old tires being upcycled to create interesting structures in the playground. </p>   

<p style="font-size: 16px; line-height: 26px;">So, let's come together as a community to bond, learn cool woodworking skills and have a whole lot of fun – all while making a positive impact on our environment. Join us on every 4<sup>th</sup> Saturday afternoon of the month to build the community Nature Playground located opposite Block 320 Yishun Central for families to enjoy the nature elements together in future.</p>   
</div>

<div>
  <img src="images/recycle1.png" class="rounded20" style="width: 100%; margin-top: 0px;">
</div>

<div>
  <img src="images/recycle2.png" class="rounded20" style="width: 100%; margin-top: 30px;">
</div>


<div style="padding: 15px 0px 0px;">
<h2 style="color: #D5262B; font-weight: bold; font-size: x-large; margin-bottom: 0px;">
  <strong>Join Us!</strong>
</h2>
</div>

<div style="padding: 0px 0px;">
<p style="font-size: 16px; line-height: 26px;">Attend our woodworking workshops on the first Saturday of the month. Learn how to transform waste into something that's not only useful, but totally awesome! Through this, we'll be more mindful of what we throw away and find inspiration in giving things a new lease of life!</p>   
</div>


<div style="padding: 5px 0px 0px;">
<h2 style="color: #D5262B; font-weight: bold; font-size: x-large; margin-bottom: 0px;">
  <strong>3. Explore and protect: Clean up our waterways with Kayak N Klean  </strong>
</h2>
</div>

<div>
  <img src="images/kayak.gif" class="rounded20" style="width: 100%; margin-top: 30px;">
</div>

<div style="padding: 0px 0px;">
<p style="font-size: 16px; line-height: 26px;">If you don't like seeing trash floating in our waterways and ruining the beauty of our coastlines, join Kayak N Klean! This community volunteering programme at Sembawang Central is all about cutting down pollution in our waterways and keeping our environment litter-free.</p>  

<p style="font-size: 16px; line-height: 26px;">Hop into a kayak and paddle through the canals, rivers and coastal areas to collect trash and debris that will then be properly disposed of and recycled where possible.</p>  

<p style="font-size: 16px; line-height: 26px;">Through this win-win weekend activity, you'll get to keep fit, enjoy amazing views, and save the environment! What's more, it's a great way to have fun and bond with family, friends or neighbours. </p>   
</div>

<div style="padding: 20px 0px;">
<div class="rounded20" style="width: 100%; background: #F9FFFE; padding: 0px 0px 0px; border: 3px dashed #006544;">
  <div style="padding: 30px 40px;">
    <div style="padding: 0px 0px;">
      <p style="font-size: larger; text-align: left; color: #0C6C37; margin: 0px 0px;"><strong>Did you know?</strong>
      </p> 
        <p style="font-size: 16px; text-align: left; color: #000; margin: 10px 0px;">Kayak N Klean is more than just cleaning up our waterways. It's a whole movement to raise awareness about the impact of litter and pollution on our environment. Whether you're an individual or organisation, you can make more conscious choices to reduce your environmental footprint. So join us and be part of something great – to protect our coastlines for future generations!</p> 
    </div>
  </div>
</div>
</div>

<div style="padding: 0px 0px 0px;">
<h2 style="color: #D5262B; font-weight: bold; font-size: x-large; margin-bottom: 0px;">
  <strong>4. Recycle right at PAssionWave @ Sembawang  </strong>
</h2>
</div>

<div>
  <img src="images/IMG_2368_Original.jpg" class="rounded20" style="width: 100%; margin-top: 30px;">
</div>

<div style="padding: 0px 0px;">
<p style="font-size: 16px; line-height: 26px;">One of the simplest ways to start your sustainable journey is to recycle your items. At the North West District, we're making it easy and convenient for you to go green!</p>  

<p style="font-size: 16px; line-height: 26px;">PAssionWave @ Sembawang is a new recycling point where you can drop off your recyclables every third Saturday of the month. A high-five to Mother Nature, this cool initiative unites residents and builds a greener community.</p> 

<p style="font-size: 16px; line-height: 26px;">What's more, you're in for a treat – each time you drop off your recyclables, you can enjoy a super discounted price of $10 on kayak rentals (usual price $27 for PAssion members and $30 for non-PAssion members). By doing your bit for the environment, you can have fun in the sun and take in stunning views of the coastline.</p>  

<p style="font-size: 16px; line-height: 26px;">Ready to recycle and claim your kayak rental offer? <a href="https://go.gov.sg/recyclerightpwsb" style="font-weight: bold; text-decoration: underline; color: #000;">Register now!</a></p>

<p style="font-size: 16px; line-height: 26px;">Residents are encouraged to bring their own recyclables to further sort into 13 categories and to understand more about how recycling encourages a sustainable lifestyle and to be aware of marine litter as well.
This session is facilitated by our environmental interest group, Blue Tribe.</p>   
</div>

<div>
  <img src="images/recycle3.png" class="rounded20" style="width: 100%; margin-top: 30px;">
</div>


<div>
  <img src="images/recycle4.png" class="rounded20" style="width: 100%; margin-top: 30px;">
</div>


<div style="padding: 20px 0px;">
<div class="rounded20" style="width: 100%; background: #E5F1ED; padding: 0px 0px 0px;">
  <div style="padding: 30px 40px;">
    <div style="padding: 0px 0px;">
      <p style="font-size: larger; text-align: left; color: #0C6C37; margin: 0px 0px;"><strong>Start your eco journey today!  </strong>
      </p> 
        <p style="font-size: 16px; text-align: left; color: #000; margin: 10px 0px;">These initiatives are funded by North West GIRAFFE Fund. Find out how you can make use of the  <a href="https://northwest.cdc.gov.sg/programmes/bonding-the-people/northwest-giraffe-fund/" target="_new" style="color: #0C6C37; text-decoration: underline; font-weight: bold;">GIRAFFE Fund</a> to create green initiatives and contribute back to the community.</p> 
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

