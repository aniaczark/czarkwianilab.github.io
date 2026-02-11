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
  margin-bottom: 1em;
}

.home-text {
  max-width: 800px;
  margin: 2em auto 0 auto;
  text-align: center;
}
</style>

<div class="home-title">
  Biomineralization, gravity sensing and regeneration Group
</div>

<p style="text-align:center;">
  <img src="{{ site.url }}{{ site.baseurl }}/images/homepage/banner.png"
       alt="fluorescent images of axolotls and brittle stars"
       style="max-width: 1200px; width: 80%; height: auto;">
</p>

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

<div class="lab-slideshow">
  <div class="slides fade">
    <img src="{{ site.baseurl }}/images/axolotl_1.png" alt="Axolotl 1">
  </div>

  <div class="slides fade">
    <img src="{{ site.baseurl }}/images/axolotl_2.png" alt="Axolotl 2">
  </div>

  <div class="slides fade">
    <img src="{{ site.baseurl }}/images/axolotl_3.png" alt="Axolotl 3">
  </div>

  <div class="slides fade">
    <img src="{{ site.baseurl }}/images/axolotl_4.png" alt="Axolotl 4">
  </div>
</div>

<style>
.lab-slideshow {
  max-width: 1000px;
  margin: 2rem auto;
  position: relative;
}

.slides {
  display: none;
}

.slides img {
  width: 100%;
  border-radius: 10px;
}

.fade {
  animation: fadeEffect 1.5s;
}

@keyframes fadeEffect {
  from {opacity: .4}
  to {opacity: 1}
}
</style>

<script>
let slideIndex = 0;
showSlides();

function showSlides() {
  let slides = document.getElementsByClassName("slides");
  for (let i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";
  }
  slideIndex++;
  if (slideIndex > slides.length) { slideIndex = 1 }
  slides[slideIndex-1].style.display = "block";
  setTimeout(showSlides, 4000); // Change image every 4 seconds
}
</script>

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