---
permalink: /
# title: "Biomineralization, gravity sensing and regeneration"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<style>
.home-title {
  text-align: center;
  font-size: 1.6em;
  font-weight: bold;
  margin-bottom: 0.5em;
}

.home-text {
  max-width: 800px;
  margin: 1em auto 0 auto;
  text-align: center;
}
</style>

<div class="home-title">
  Biomineralization, gravity sensing and regeneration Group
</div>

<div class="lab-fade-slider">
  <img src="{{ site.baseurl }}/images/axolotl_1.png">
  <img src="{{ site.baseurl }}/images/axolotl_2.png">
  <img src="{{ site.baseurl }}/images/axolotl_3.png">
  <img src="{{ site.baseurl }}/images/axolotl_4.png">
</div>

<style>
.lab-fade-slider {
  position: relative;
  max-width: 1000px;
  margin: 0.5rem auto;
  height: 600px; /* adjust if needed */
}

.lab-fade-slider img {
  position: absolute;
  width: 100%;
  height: 100%;
  object-fit: contain;
  border-radius: 10px;
  opacity: 0;
  animation: fadeSlider 16s infinite;
}

/* Each image gets a delayed animation */
.lab-fade-slider img:nth-child(1) { animation-delay: 0s; }
.lab-fade-slider img:nth-child(2) { animation-delay: 4s; }
.lab-fade-slider img:nth-child(3) { animation-delay: 8s; }
.lab-fade-slider img:nth-child(4) { animation-delay: 12s; }

@keyframes fadeSlider {
  0%   { opacity: 0; }
  5%   { opacity: 1; }
  25%  { opacity: 1; }
  30%  { opacity: 0; }
  100% { opacity: 0; }
}
</style>


<div class="home-text">
  <p>
    We are located at the Center for Regenerative Therapies Dresden (CRTD) at the Dresden University of Technology (TUD), Germany
  </p>
</div>

<p style="text-align:center; display:flex; justify-content:center; gap:2em;">
  <img src="{{ site.url }}{{ site.baseurl }}/images/crtd_logo.png"
       alt="crtd logo"
       style="height:60px; width:auto;">

  <img src="{{ site.url }}{{ site.baseurl }}/images/tud_logo_trim.png"
       alt="second logo"
       style="height:60px; width:auto;">
</p>


<p style="text-align:center;">
  <img src="{{ site.url }}{{ site.baseurl }}/images/homepage/banner.png"
       alt="fluorescent images of axolotls and brittle stars"
       style="max-width: 1200px; width: 80%; height: auto;">
</p>

<!-- <div style="height:200px;"></div> -->



<div class="home-text">
  <p>
    Our funding
  </p>
</div>

<div style="text-align:center; margin-top:2em;">

  <!-- Top single logo -->
  <div style="margin-bottom:1.5em;">
    <img src="{{ site.url }}{{ site.baseurl }}/images/logo_erc_flag_EU.png"
         alt="erc logo"
         style="height:100px; width:auto;">
  </div>

  <!-- Bottom row with three logos -->
  <div style="display:flex; justify-content:center; align-items:center; gap:3em; flex-wrap:wrap;">
    <img src="{{ site.url }}{{ site.baseurl }}/images/mv_logo.jpg"
         alt="mv logo"
         style="height:60px; width:auto;">

    <img src="{{ site.url }}{{ site.baseurl }}/images/crtd_logo.png"
         alt="crtd logo"
         style="height:60px; width:auto;">

    <img src="{{ site.url }}{{ site.baseurl }}/images/tud_logo_trim.png"
         alt="tud logo"
         style="height:60px; width:auto;">
  </div>

</div>




<!-- <div class="home-text">
  <p>
    Our funding
  </p>
</div>

<p style="text-align:center;">
  <img src="{{ site.url }}{{ site.baseurl }}/images/homepage/banner.png"
       alt="fluorescent images of axolotls and brittle stars"
       style="max-width: 1200px; width: 80%; height: auto;">
</p> -->