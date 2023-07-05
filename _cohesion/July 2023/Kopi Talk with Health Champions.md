---
title: Kopi Talk with Health Champions
permalink: /cohesion/july-2023/kopi-talk-healthchamps/
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
#carousel-4:checked ~ .control-4,
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
#carousel-3:checked ~ .control-3 ~ .carousel-indicators li:nth-child(3) .carousel-bullet,
#carousel-4:checked ~ .control-4 ~ .carousel-indicators li:nth-child(4) .carousel-bullet {
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

.rounded25 {
  -webkit-border-radius: 25px;
  -moz-border-radius: 25px;
  border-radius: 25px;
}
  </style>

<article style="max-width: 800px; width: 100%; margin: auto;">

<div style="width: 100%; padding-top: 15px;">
  <a href="https://northwest.cdc.gov.sg/cohesion/july-2023/july-at-a-glance">
    <img style="width: 100%; max-width: 100px; position: relative; padding-left: 10px; float:left !important; padding-bottom: 20px;" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/nw-cohesion-logo-2023%201.gif">
  </a>
</div>

<div style="width: 100%;">
  <img style="width: 100%; max-width:" alt="Promoting Health and Wellness" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/promoting-health-wellness.png">
  <img style="width: 100%; max-width:" alt="" src="/images/Cohesion/July%202023/crossfit.png">
</div>

<div class="rounded20" style="max-width: 100%; padding: 30px 0px 0px;">
	<img style="width: 100%; margin-top: 0px;" class="rounded20" src="/images/Cohesion/July%202023/healthiersg-kv.gif">
</div>

<h2 style="color: #B25694; font-weight: bold; font-size: x-large; padding: 15px 0px;">
  <strong>#KopiTalk with North West Fitness Enthusiasts</strong>
</h2>

<div style="padding: 30px 35px; background: #EBDFEC;" class="rounded25">

  <div style="padding: 5px 0px; display: inline-table;" class="w-100">
  <img style="max-width: 100%; padding: 10px 0px 15px; width: 100%;" src="/images/Cohesion/July%202023/eillron-quote.png">
  <img style="max-width: 50px; float: right; padding: 0px 0px 5px 10px; width: 100%;" src="/images/Cohesion/July%202023/kopi%20brown%20cup.png">
  <p style="font-size: 16px; line-height: 26px; padding-top: 10px;"><span style="font-weight: bold; color: #B25694;">The kind of kopi I like best is … </span> 3-in-1 coffee. However, for health purposes, I prefer to drink plain water and tea.</p>
  </div>

  <div style="padding: 5px 0px; display: inline-table;" class="w-100">
  <img style="max-width: 180px; float: left; padding: 10px 20px 5px 0px; width: 100%;" src="/images/Cohesion/July%202023/exercise.png"><p style="font-size: 16px; line-height: 26px;"><span style="font-weight: bold; color: #B25694;">When I'm not working, I like to …</span> exercise! Every weekday, I head straight to a fitness class after work. I attend various classes in the North West such as CrossFit and Fight Do.</p>
  <p style="font-size: 16px; line-height: 26px;"><span style="font-weight: bold; color: #B25694;">The last time I used my CDC Voucher, I spent it on … </span> food at my favourite hawker center,  Long Ding Seafood at Kampung Admiralty Hawker Centre in the North West. With the CDC Vouchers, I've been frequenting the stall more often for their fresh seafood dishes!</p>
  </div>

  <div style="padding: 15px 0px; display: inline-table;" class="w-100">
  <img style="max-width: 280px; float: right; padding: 10px 0px 5px 20px; width: 100%;" src="/images/Cohesion/July%202023/eillron1.png"><p style="font-size: 16px; line-height: 26px;"><span style="font-weight: bold; color: #B25694;">I first got interested in CrossFit when …</span> a friend of mine invited me to join the class with her. I had not done CrossFit then, but it seemed interesting, so I signed up immediately. I've not looked back since. I attend the class every Monday and it is my happy place!</p>
  <p style="font-size: 16px; line-height: 26px;"><span style="font-weight: bold; color: #B25694;">My favourite thing about CrossFit class is … </span> the energy you get from group exercise. You feel 
more motivated when you're exercising together with other people who are bursting with 
energy. I also like working with the different types of equipment in the class, such as the dumbbells and ropes. This lets you build up the muscles from different parts of your body. </p>
  </div>

  <div style="padding: 20px 0px 0px; display: inline-table;" class="w-100">
  <img style="max-width: 280px; float: left; padding: 0px 20px 5px 0px; width: 100%;" src="/images/Cohesion/July%202023/eillron2.png">
  <p style="font-size: 16px; line-height: 26px; padding-top: 20px;"><span style="font-weight: bold; color: #B25694;">As an avid CrossFitter, my top tips are …  </span> to take things step by step and more importantly, to never give up. Although it can be tough and tiring in the beginning, you'll gradually be able to build up your endurance and enjoy the health benefits!</p>
  </div>

</div>

<div style="padding: 15px 0px;">
</div>

<div style="padding: 30px 35px; background: #EBDFEC;" class="rounded25">

  <img style="max-width: 100%; padding: 10px 0px 15px; width: 100%;" src="/images/Cohesion/July%202023/wendy-quote.png">

  <div style="padding: 5px 0px; display: inline-table;" class="w-100">

  <img style="max-width: 320px; float: right; padding: 0px 0px 5px 20px; width: 100%;" src="/images/Cohesion/July%202023/wendy1.png">

  <div style="padding-top: 20px;" class="w-100">
  <img style="max-width: 92px; float: left; padding: 20px 20px 5px 0px; width: 100%;" src="/images/Cohesion/July%202023/kopi2%20white%20cup.png">
  <p style="font-size: 16px; line-height: 26px; padding-top: 0px;"><span style="font-weight: bold; color: #B25694;">我最喜欢的咖啡种类是… </span> 我不喝咖啡，只喝茶或白开水。基于我是癌症病患者的缘故，我都会选择比较健康的饮料。 </p>
  </div>

  <p style="font-size: 16px; line-height: 26px; padding-top: 10px;"><span style="font-weight: bold; color: #B25694;">我在西北部最喜欢的地方是… </span> 三巴旺公园! 我喜欢去那看看风景和走走，因为那里的景色和环境让我很放松。 </p>
  <p style="font-size: 16px; line-height: 26px;"><span style="font-weight: bold; color: #B25694;">我的超能力是...  </span> 非常独立和拥有敏捷的动作！能够快速地把家务做好，虽然我的丈夫在外地工作，但我也可以非常独立和勇敢地面对自己的病况。 </p>
  </div>


  <div style="padding: 5px 0px; display: inline-table;" class="w-100">
  <img style="max-width: 150px; float: left; padding: 0px 20px 5px 0px; width: 100%;" src="/images/Cohesion/July%202023/wendy2.png">
  <p style="font-size: 16px; line-height: 26px; padding-top: 20px; margin: auto;"><span style="font-weight: bold; color: #B25694;">课程中，最难忘的一次经历是…</span> 课程中看到一些成员因为不太会运用运动器材而做出的一些可爱动作，非常的搞笑又可爱，这些画面对我来说特别的难忘。</p>
  </div>


  <div style="padding: 25px 0px 0px; display: inline-table;" class="w-100">
  <img style="max-width: 320px; float: left; padding: 0px 20px 5px 0px; width: 100%;" src="/images/Cohesion/July%202023/wendy3.png">
  <p style="font-size: 16px; line-height: 26px; padding-top: 20px;"><span style="font-weight: bold; color: #B25694;">会让我继续参与西北部混合健身课的动力是来自于…  </span> 专业教练的培训和教导，还有学员也非常的友善，而且还可以锻炼身体和维持建康，我会鼓励身边更多的朋友一起参与这些健康和免费的运动课程。</p>
  </div>

</div>

<div style="padding: 30px 0px 0px;">
<h2 style="color: #B25694; font-weight: bold; font-size: x-large; padding: 15px 0px;">
  <strong>Eillron and Wendy at the HealthierSG Fest</strong>
</h2>

<!--Slider-->
<div style="text-align: center; padding: 0px 0px;">
<div class="carousel">
    <div style="-webkit-border-radius: 20px; -moz-border-radius: 20px; border-radius: 20px;" class="carousel-inner">
        <input checked="checked" hidden="" aria-hidden="true" name="carousel" id="carousel-1" type="radio" class="carousel-open">
        <div class="carousel-item">
            <img style="width: 100%;" src="/images/Cohesion/July%202023/cf-slide1.jpg">
        </div>
        <input hidden="" aria-hidden="true" name="carousel" id="carousel-2" type="radio" class="carousel-open">
        <div class="carousel-item">
            <img style="width: 100%;" src="/images/Cohesion/July%202023/cf-slide2.jpg">
        </div>
        <input hidden="" aria-hidden="true" name="carousel" id="carousel-3" type="radio" class="carousel-open">
        <div class="carousel-item">
            <img style="width: 100%;" src="/images/Cohesion/July%202023/cf-slide3.jpg">
        </div>
        <input hidden="" aria-hidden="true" name="carousel" id="carousel-4" type="radio" class="carousel-open">
        <div class="carousel-item">
            <img style="width: 100%;" src="/images/Cohesion/July%202023/cf-slide4.jpg">
        </div>
        <label class="carousel-control prev control-1" for="carousel-4">‹</label>
        <label class="carousel-control next control-1" for="carousel-2">›</label>
        <label class="carousel-control prev control-2" for="carousel-1">‹</label>
        <label class="carousel-control next control-2" for="carousel-3">›</label>
        <label class="carousel-control prev control-3" for="carousel-2">‹</label>
        <label class="carousel-control next control-3" for="carousel-4">›</label>
        <label class="carousel-control prev control-4" for="carousel-3">‹</label>
        <label class="carousel-control next control-4" for="carousel-1">›</label>
        <ol class="carousel-indicators">
            <li>
                <label class="carousel-bullet" for="carousel-1">•</label>
            </li>
            <li>
                <label class="carousel-bullet" for="carousel-2">•</label>
            </li>
            <li>
                <label class="carousel-bullet" for="carousel-3">•</label>
            </li>
            <li>
                <label class="carousel-bullet" for="carousel-4">•</label>
            </li>
        </ol>
    </div>
</div>
</div>
<!--Slider End-->

<p style="font-size: 16px; line-height: 26px;">From sports tasters and kampung games to water activities and brisk walking, it was plenty of fun for residents at our inaugural HealthierSG Fest @ North West, held on 17 and 18 June 2023 at the Choa Chu Kang Sports Centre. </p>
</div>

<div style="padding: 30px 0px">
<h2 style="color: #B25694; font-weight: bold; font-size: x-large; padding: 15px 0px;">
  <strong>HealthierSG Fest in a nutshell!</strong>
</h2>
<div style="text-align: center; margin: auto;">

<iframe allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share" allowfullscreen="true" frameborder="0" scrolling="no" style="border:none;overflow:hidden" height="710" width="500px" src="https://www.facebook.com/plugins/post.php?href=https%3A%2F%2Fwww.facebook.com%2Fnwcdc%2Fposts%2Fpfbid0WMyrwdt56C2Qq6tUKYsnPYC7owXpLBWaBZcRCtQ4jYeZvPUNoymmpRF5WgwaKxfal&amp;show_text=true&amp;width=500"></iframe>

</div>
</div>


<!--CTA-->
<div style="padding: 20px 0px;">
<div style="width: 100%; background: #EBDFEC; padding: 0px 8px 0px;" class="rounded20">
  <div style="padding: 30px 40px;">
    <div style="padding: 0px 10px;">
      <div style="background-image: url('/images/Cohesion/July%202023/nwfitness-logo.png'); background-color: #EBDFEC; background-blend-mode: darken; min-height: 100px; background-repeat: no-repeat;     background-size: contain;
    margin-left: -15px;">
        <!--<img src="/images/Cohesion/July%202023/nwfitness-logo.png" style="max-width: 150px;" />-->
      </div>
        <p style="font-size: 16px; text-align: left; line-height: 24px; color: #000; margin: 10px 0px;">If you're keen to start your fitness journey, Eillron and Wendy have the same piece of advice: GO&nbsp;FOR IT!</p>
        <p style="font-size: 16px; text-align: left; line-height: 24px; color: #000; margin: 10px 0px;">North West FitnessX Club offers high-intensity classes including CrossFit, Fight Do, K-pop Fitness and Zumba for residents in the North West District to encourage them to lead a healthier lifestyle. If you're keen to start your fitness journey, why not sign up for our classes! Take that first step and <a style="font-weight: bold; color: #B25694;" target="_new" href="https://northwest.cdc.gov.sg/programmes/promoting-health-and-wellness/nw-fitnessx/">find out more here</a>.</p>  
  </div>
</div>
</div>
</div>
<!--CTA End-->


<div style="text-align: center; margin: auto; padding: 20px 0px;">
<img style="width: 100%; margin: auto;" class="rounded20" src="/images/Cohesion/July%202023/collage.jpeg">
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
