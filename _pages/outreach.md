---
layout: archive
title: "Outreach"
permalink: /outreach/
author_profile: false
header:
  overlay_image: headerimage1.png
  overlay_filter: rgba(140, 21, 21, 0.5)
---

<!-- <!DOCTYPE html> -->
<!-- <html> -->
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>

/* Container for image text */
.caption-container {
  text-align: center;
  <!-- background-color: #222; -->
  <!-- background-color: $primary-color -->
  padding: 2px 16px;
  <!-- background-color: rgb(0,0,0,1); -->
  <!-- color: white; -->
  display: flex;
}
</style>

In recent years, I developed a passion for science communication and became actively involved in various public outreach events.
Not only are these events enjoyable for me (and, as far as I can tell, for my audience as well), but I also see these events as crucial to strengthen trust in science and help the public understand the value of funding research. Events I have participated in include

- Long Night of Science (Dresden, 2017): Talk about the quantum mechanical concept of time. <small>(<a href="https://tu-dresden.de/mn/der-bereich/news/interdisziplinaer-und-zukunftsgewandt-physikphilosophie-an-der-tud">learn more</a>)
- Pint of Science (Cologne, 2022): Talk about my research on chaos in quantum computers. <small>(<a href = "https://ml4q.de/2022/05/11/back-in-the-pubs-again-ml4q-pint-of-science-2022/">learn more</a>)</small>
- Türen auf mit der Maus (Cologne, 2022): Introductory talk on quantum computers for children (age 8 - 13). <small>(<a href = "https://ml4q.de/2022/10/10/open-house-with-die-maus-in-the-cologne-physics-institutes/">learn more</a>)</small>
- Türen auf mit der Maus (Cologne, 2023): Computational physics workshop for children (age 8 - 13). <small>(<a href = "https://ml4q.de/2023/10/06/quantenphysik-begeistert-familien-bei-turen-auf-mit-der-maus-in-der-kolner-physik/">learn more</a>, <a href = "https://github.com/christophberke/makiephysicssimulations">download code and slides</a>)</small>
- ZDI-Schülerlabor (Cologne 2024): Computational physics workshop for female pupils (age 14 - 16).  <small>(<a href = "https://ml4q.de/2024/03/04/schnupperuni-physik-beautiful-things-one-can-do-with-theoretical-physics/">learn more</a>)</small>
- 10\. Night of Technologies (Cologne 2024): Introductory talk on quantum computers. <small>(<a href = "https://ml4q.de/2024/06/28/quantum-technology-represented-for-the-first-time-in-nacht-der-technik-cologne/">learn more</a>) </small>

Let me know if you are interested in details or the slides.

## Some impressions

<div class="SLcontainer">

  <div class="mySlides" id = "10. Night of Technologies (Cologne), Talk on quantum computers">
    <div class="numbertext" style="color:#fff">1 / 9</div>
    <img src="../images/LndT24.png" style="width:100%">
  </div>
  
  <div class="mySlides" id = "10. Night of Technologies (Cologne), Talk on quantum computers">
    <div class="numbertext">2 / 9</div>
    <img src="../images/LndT_talk.png" style="width:100%">
  </div>

  <div class="mySlides" id = "Türen auf mit der Maus (Cologne 2023), Workshop on Computational Physics">
    <div class="numbertext">3 / 9</div>
    <img src="../images/TamdM23.png" style="width:100%">
  </div>

  <div class="mySlides" id = "Computational Physics Workshop (Cologne 2023), Part I: Sea shell patterns">
    <div class="numbertext">5 / 9</div>
    <img src="../images/ca.png" style="width:100%">
  </div>

  <div class="mySlides" id = "Computational Physics Workshop (Cologne 2023) , Part II: The magnetic pendulum">
    <div class="numbertext" style="color:#fff">4 / 9</div>
    <img src="../images/mag_pend.png" style="width:100%">
  </div>
    
  <div class="mySlides" id = "Türen auf mit der Maus (Cologne 2022), Talk on quantum computers">
    <div class="numbertext">6 / 9</div>
    <img src="../images/TamdM22.png" style="width:100%">
  </div>
    
  <div class="mySlides" id="Pint of Science (Cologne 2022), Talk on chaotic transmons">
    <div class="numbertext">7 / 9</div>
    <img src="../images/PoS22.png" style="width:100%">
  </div>

  <div class="mySlides" id ="Pint of Science (Cologne 2022), Talk on chaotic transmons">
    <div class="numbertext">8 / 9</div>
    <img src="../images/pos_talk.png" style="width:100%">
  </div>

  <div class="mySlides" id = "Long Night of Science (Dresden 2017), Talk on quantum mechanics and time">
    <div class="numbertext">9 / 9</div>
    <img src="../images/LndWtitle.png" style="width:100%">
  </div>

  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>

  <div class="caption-container">
    <p id="caption"></p>
  </div>
</div>

<script>
let slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let captionText = document.getElementById("caption");
  let image1 = document.getElementById("im1");
  let image2 = document.getElementById("im2");
  if (n > slides.length) {slideIndex = 1}
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";
  }

  slides[slideIndex-1].style.display = "block";
  captionText.innerHTML = slides[slideIndex-1].id;
}

</script>

