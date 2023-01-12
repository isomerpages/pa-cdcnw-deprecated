---
title: CDC Vouchers
permalink: /cohesion/January-2023/cdcv-t3/
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
  <img src="https://d33wubrfki0l68.cloudfront.net/abc6e70dc488c5f62ee571bffa3a0cb8186754b6/19768/images/cohesion-logo.gif" style="width: 100%; max-width: 200px; z-index: 99; position: relative; margin-left: -20px;">
</div>

<div>
	<img src="/images/Cohesion/Jan%202023/vouchers-kv.png" style="width: 100%; margin-top: 0px;">
</div>

<div style="padding: 30px 0px 10px;">
<p style="font-size: 16px; line-height: 26px; word-spacing: 3px;">The new tranche of CDC Vouchers has just been announced! All Singaporean households will receive another $300 worth of CDC Vouchers. To widen the choices and provide more convenience to Singaporeans, the scheme has been expanded to include supermarket chains. Singaporeans can now spend $150 at participating supermarkets, on top of the $150 CDC Vouchers that could be spent at participating heartland merchants and hawkers.</p> 

<p style="font-size: 16px; line-height: 26px; word-spacing: 3px;">CDC vouchers will come in handy as you gear up for CNY festivities. On top of shopping at supermarkets, you can continue to support your favourite local businesses!</p>

<p style="font-size: 16px; line-height: 26px; word-spacing: 3px;">From food items to fashion, here’s how you can spend your CDC vouchers to usher in the Year of the Rabbit 🐇
</p>   
</div>

<!--Box-->
<div style="padding: 20px 0px 0px;">
<div class="rounded20" style="width: 100%; background: #F2F8F6; padding: 20px 0px 0px;">
  <div style="padding: 10px 40px;">

  <div>
    <p style="color: #D5262B; font-weight: bold; font-size: x-large;">
      <img src="https://d33wubrfki0l68.cloudfront.net/b418db455e809024f12a7cff20a59dda28d0f83a/6d6b7/images/cdc_icon1.png" style="max-width: 40px; margin: -8px 10px 0px 0px; float: left;" align="left"><strong style="color: #D5262B; font-weight: bold; font-size: x-large;">Stock up on CNY goodies</strong>
    </p>
  </div>

  <p style="font-size: 16px; line-height: 26px; text-align: left; margin-top: 20px;">
    Are you looking forward to having  mouth-watering pineapple tarts during CNY? Let's not forget other popular goodies such as love letters, kueh bangkit, kueh lapis and peanut cookies too! With the CDC vouchers, you can stock up on your favourite treats and buy more for gifting. 
  </p> 

  <p style="font-size: 16px; line-height: 26px;">
    <ul style="padding: 0px 15px; line-height: 28px;">
      <li style="font-size: medium;line-height: inherit; padding-bottom: 15px;">
        <strong style="text-transform: uppercase;">Anna’s Cookies</strong><br/> 
        Blk 20 Ghim Moh Rd, #01-98/99, Singapore 270020
      </li>
      <li style="font-size: medium;line-height: inherit; padding-bottom: 15px;">
        <strong style="text-transform: uppercase;">KZ Bakery</strong><br/> 
        Sembawang Crescent, #01-09, S750365 
      </li>
      <li style="font-size: medium;line-height: inherit; padding-bottom: 15px;">
        <strong style="text-transform: uppercase;">The Baker's Brothers </strong><br/> 
        Canberra Crescent, #01-02, S750120 
      </li>
      <li style="font-size: medium;line-height: inherit; padding-bottom: 15px;">
        <strong style="text-transform: uppercase;">Snack & Cake Shop</strong><br/> 
        18 Marsiling Ln, #01-271, S730018 
      </li>
      <li style="font-size: medium;line-height: inherit; padding-bottom: 15px;">
        <strong style="text-transform: uppercase;">Swee Heng Bakery (SHB09)</strong><br/> 
        Canberra Road, #01-07, S750511
      </li>
    </ul>
  </p> 
  </div>
</div>
</div>
<!--Box End-->

<!--Box-->
<div style="padding: 20px 0px 0px;">
<div class="rounded20" style="width: 100%; background: #D7E9E4; padding: 20px 0px 0px;">
  <div style="padding: 10px 40px;">

  <div>
    <p style="color: #D5262B; font-weight: bold; font-size: x-large;">
      <img src="https://d33wubrfki0l68.cloudfront.net/c328da1e881761758731e092d3447d09f99c25c6/fbb63/images/cdc_icon2.png" style="max-width: 40px; margin: -8px 10px 0px 0px; float: left;" align="left"><strong style="color: #D5262B; font-weight: bold; font-size: x-large;">Prepare for the reunion dinner</strong>
    </p>
  </div>

  <p style="font-size: 16px; line-height: 26px; text-align: left; margin-top: 20px;">
Planning the menu for your reunion dinner this year?  You can add more ingredients to your grocery list and make the most out of your budget with the CDC Vouchers!   
  </p> 

  <p style="font-size: 16px; line-height: 26px;">
    <ul style="padding: 0px 15px; line-height: 28px;">
      <li style="font-size: medium;line-height: inherit; padding-bottom: 15px;">
        <strong style="text-transform: uppercase;">AWS MARKET PTE LTD</strong><br/> 
        Yishun Street 22, #01-317, S760294
      </li>
      <li style="font-size: medium;line-height: inherit; padding-bottom: 15px;">
        <strong style="text-transform: uppercase;">LASHIKA SRI ENTERPRISES PTE LTD</strong><br/> 
        Yishun Street 22, #01-K1, S760274
      </li>
      <li style="font-size: medium;line-height: inherit; padding-bottom: 15px;">
        <strong style="text-transform: uppercase;">CHYE THIAM MARKET PRODUCE SHOP</strong><br/> 
        Gangsa Road, #01-149, S670109
      </li>
      <li style="font-size: medium;line-height: inherit; padding-bottom: 15px;">
        <strong style="text-transform: uppercase;">112 MINI MARKET</strong><br/> 
        Pending Road, #01-120, S670112
      </li>
      <li style="font-size: medium;line-height: inherit; padding-bottom: 15px;">
        <strong style="text-transform: uppercase;">SB MART (THE BROOKS II)</strong><br/> 
        Springside Green, #01-19, S786015
      </li>
    </ul>
  </p> 
  </div>
</div>
</div>
<!--Box End-->

<!--Box-->
<div style="padding: 20px 0px 0px;">
<div class="rounded20" style="width: 100%; background: #F2F8F6; padding: 20px 0px 0px;">
  <div style="padding: 10px 40px;">

  <div>
    <p style="color: #D5262B; font-weight: bold; font-size: x-large;">
      <img src="https://d33wubrfki0l68.cloudfront.net/9c1bf2a550606c41ae2076e2c4ba5d60c932216d/5e56f/images/cdc_icon3.png" style="max-width: 40px; margin: -8px 10px 0px 0px; float: left;" align="left"><strong style="color: #D5262B; font-weight: bold; font-size: x-large;">Update your wardrobe</strong>
    </p>
  </div>

  <p style="font-size: 16px; line-height: 26px; text-align: left; margin-top: 20px;">
    Wearing new clothes during CNY symbolises a fresh start to the year ahead. Take this opportunity to update your wardrobe for a fraction of the price! Spend your CDC vouchers on new outfits and accessories to look your best this festive season.
  </p> 

  <p style="font-size: 16px; line-height: 26px;">
    <ul style="padding: 0px 15px; line-height: 28px;">
      <li style="font-size: medium;line-height: inherit; padding-bottom: 15px;">
        <strong style="text-transform: uppercase;">IS ME FASHION</strong><br/> 
        2 Bukit Panjang Ring Road, #02-28, S679947
      </li>
      <li style="font-size: medium;line-height: inherit; padding-bottom: 15px;">
        <strong style="text-transform: uppercase;">Children’s Clothing</strong><br/> 
        104 Yishun Ring Road, #01-12, S7760104 
      </li>
      <li style="font-size: medium;line-height: inherit; padding-bottom: 15px;">
        <strong style="text-transform: uppercase;">Baoqiong Clothes </strong><br/> 
        21 Marsiling Lane, #01-98, S730021 
      </li>
      <li style="font-size: medium;line-height: inherit; padding-bottom: 15px;">
        <strong style="text-transform: uppercase;">Apparel Shop  </strong><br/> 
       Woodlands Street 31, #01-59, S730305 
      </li>
      <li style="font-size: medium;line-height: inherit; padding-bottom: 15px;">
        <strong style="text-transform: uppercase;">HUA LI FASHION</strong><br/> 
        Fajar Road, #01-K4, S670445
      </li>
    </ul>
  </p> 
  </div>
</div>
</div>
<!--Box End-->

<!--Box-->
<div style="padding: 20px 0px 0px;">
<div class="rounded20" style="width: 100%; background: #D7E9E4; padding: 20px 0px 0px;">
  <div style="padding: 10px 40px;">

  <div>
    <p style="color: #D5262B; font-weight: bold; font-size: x-large;">
      <img src="https://d33wubrfki0l68.cloudfront.net/1ab3c0d6224b762b49a17faf1f9dd160126a1dac/1aff4/images/cdc_icon4.png" style="max-width: 40px; margin: -8px 10px 0px 0px; float: left;" align="left"><strong style="color: #D5262B; font-weight: bold; font-size: x-large;">Get a new year makeover</strong>
    </p>
  </div>

  <p style="font-size: 16px; line-height: 26px; text-align: left; margin-top: 20px;">
New year calls for new change! Thinking of getting a new hairstyle, a fresh set of manicure, or just going for a relaxing message before the festivities? You can spend your CDC vouchers at a salon for a new hairstyle or get your nails done.  Don’t forget to claim your CDC vouchers so you can spend  them at participating service providers. 
  </p> 

  <p style="font-size: 16px; line-height: 26px;">
    <ul style="padding: 0px 15px; line-height: 28px;">
      <li style="font-size: medium;line-height: inherit; padding-bottom: 15px;">
        <strong style="text-transform: uppercase;">Santorini Hair Spa </strong><br/> 
        Sembawang Crescent, #01-05, S750365 
      </li>
      <li style="font-size: medium;line-height: inherit; padding-bottom: 15px;">
        <strong style="text-transform: uppercase;">JK2 Hair Beauty Salon 768 </strong><br/> 
        Woodlands Avenue 6, #02-08, S730768 
      </li>
      <li style="font-size: medium;line-height: inherit; padding-bottom: 15px;">
        <strong style="text-transform: uppercase;">Lilian Massage Service </strong><br/> 
       235 Yishun Street 21 Yishun Singapore 760235, #01-454, S760235 
      </li>
      <li style="font-size: medium;line-height: inherit; padding-bottom: 15px;">
        <strong style="text-transform: uppercase;">Zen Nail Art </strong><br/> 
        258 Bukit Panjang Ring Road, #01-54, S670258 
      </li>
      <li style="font-size: medium;line-height: inherit; padding-bottom: 15px;">
        <strong style="text-transform: uppercase;">822 Hairdressing (Unisex) Beauty Salon  </strong><br/> 
        Sembawang Drive, #01-822, S750406
      </li>
    </ul>
  </p> 
  </div>
</div>
</div>
<!--Box End-->

<!--Box-->
<div style="padding: 20px 0px 0px;">
<div class="rounded20" style="width: 100%; background: #F2F8F6; padding: 20px 0px 0px;">
  <div style="padding: 10px 40px;">

  <div>
    <p style="color: #D5262B; font-weight: bold; font-size: x-large;">
      <img src="https://d33wubrfki0l68.cloudfront.net/12160d66576acc0784257dcabf20a7118bcd0320/cb377/images/cdc_icon5.png" style="max-width: 40px; margin: -8px 10px 0px 0px; float: left;" align="left"><strong style="color: #D5262B; font-weight: bold; font-size: x-large;">Spruce up your home</strong>
    </p>
  </div>

  <p style="font-size: 16px; line-height: 26px; text-align: left; margin-top: 20px;">
    It's time to spring clean and dress up your home for the celebrations. To give your home a fresh look, here are some ideas on what you can spend your CDC vouchers on: bedsheets, cushion covers, plants, "huat" decorations or table linen. You can also take the opportunity to buy new electric hotpot and appliance to spruce up your kitchen. Happy decorating!
  </p> 

  <p style="font-size: 16px; line-height: 26px;">
    <ul style="padding: 0px 15px; line-height: 28px;">
      <li style="font-size: medium;line-height: inherit; padding-bottom: 15px;">
        <strong style="text-transform: uppercase;">Sherlin Florist </strong><br/> 
        20 Marsiling Ln, #20/21, Singapore 730020
      </li>
      <li style="font-size: medium;line-height: inherit; padding-bottom: 15px;">
        <strong style="text-transform: uppercase;">Furniture Cubes Pte Ltd </strong><br/> 
        Block 291 Yishun Street 22 #01-361 Singapore (760291) 
      </li>
      <li style="font-size: medium;line-height: inherit; padding-bottom: 15px;">
        <strong style="text-transform: uppercase;">Home Curtains & Blinds  </strong><br/> 
        Woodlands Street 12, #02-37, S738623 
      </li>
      <li style="font-size: medium;line-height: inherit; padding-bottom: 15px;">
        <strong style="text-transform: uppercase;">Ajits Household & Sundry Trading  
</strong><br/> 
       Canberra Road, #01-08, S750511 
      </li>
      <li style="font-size: medium;line-height: inherit; padding-bottom: 15px;">
        <strong style="text-transform: uppercase;">Kah Ho Household & Hardware </strong><br/> 
        Woodlands Drive 44, #02-31, S730548
      </li>
    </ul>
  </p> 
  </div>
</div>
</div>
<!--Box End-->

<div style="padding: 0px 0px 10px;">
<p style="font-size: 16px; line-height: 26px; word-spacing: 3px;">On top of these businesses, there are many others where you can spend your CDC vouchers. Choose from over 20,000 heartland merchants, hawkers and supermarket outlets!</p> 

<p style="font-size: 16px; line-height: 26px; word-spacing: 3px;">Hear what some excited merchants and residents have to say for the new CDC Vouchers scheme 2023! </p>

<div style="text-align: center; padding: 0px 0px 20px;">
<div class="video-container">
  <iframe src="https://www.youtube.com/embed/UyvUvKO3j0g" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
</div>


<div style="padding: 20px 0px;">
<div class="rounded20" style="width: 100%; background: #E5F1ED; padding: 0px 0px 0px;">
  <div style="padding: 30px 40px;">
    <div style="padding: 0px 0px;">
      <p style="font-size: 18px; text-align: left; color: #0C6C37; margin: 0px 0px;"><strong>Ready to start CNY shopping with your CDC vouchers? </strong>
      </p> 
        <p style="font-size: 16px; text-align: left; line-height: initial; color: #000; margin: 10px 0px;">To claim your CDC vouchers, visit <a href="https://go.gov.sg/cdcv" target="_new" style="color: #0C6C37; text-decoration: underline; font-weight: bold;">go.gov.sg/cdcv</a><br/>
To find out where you can spend your CDC vouchers, visit <a href="https://gowhere.gov.sg/cdcvouchersmerchants" target="_new" style="color: #0C6C37; text-decoration: underline; font-weight: bold;">gowhere.gov.sg/cdcvouchersmerchants</a> </p>  
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


</body>
</html>

