---
title: "Gourmet of Fire"
image: "/assets/images/gourmet_of_fire.png"
layout: project
---

## Gourmet of Fire

[Link to the game](https://odd-mune.itch.io/gourmet-of-fire)

<div class="slideshow-container">
  <div class="slide fade">
    <img src="/assets/images/gourmet_of_fire.png" alt="Gourmet of Fire">
  </div>
  <div class="slide fade">
    <img src="/assets/images/gourmet_of_fire_cooking_ui.jpg" alt="Cooking UI">
  </div>
  <div class="slide fade">
    <img src="/assets/images/gourmet_of_fire_cooking_animation.jpg" alt="Cooking Animation">
  </div>
  <div class="slide fade">
    <img src="/assets/images/gourmet_of_fire_princess_concept.png" alt="Princess Concept">
  </div>
  <div class="slide fade">
    <img src="/assets/images/gourmet_of_fire_dialog.jpg" alt="Dialog">
  </div>
  <div class="slide fade">
    <img src="/assets/images/gourmet_of_fire_field_level.jpg" alt="Field Level">
  </div>
  <div class="slide fade">
    <img src="/assets/images/gourmet_of_fire_village_level.jpg" alt="Village Level">
  </div>
  <div class="slide fade">
    <img src="/assets/images/gourmet_of_fire_in_house_level.jpg" alt="In-House Level">
  </div>
</div>

<style>
  .slideshow-container {
    max-width: 600px; /* Adjust as needed */
    position: relative;
    margin: auto;
    overflow: hidden;
    border-radius: 10px;
  }

  .slide {
    display: none;
    width: 100%;
  }

  .slide img {
    width: 100%;
    height: auto;
    border-radius: 10px;
  }

  /* Smooth fade transition */
  .fade {
    animation: fadeEffect 1.5s ease-in-out;
  }

  @keyframes fadeEffect {
    from { opacity: 0.4; }
    to { opacity: 1; }
  }
</style>

<script>
  let slideIndex = 0;

  function showSlides() {
    let slides = document.getElementsByClassName("slide");
    for (let i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";  
    }
    slideIndex++;
    if (slideIndex > slides.length) { slideIndex = 1; }  
    slides[slideIndex - 1].style.display = "block";  
    setTimeout(showSlides, 3000); // Change image every 3 seconds
  }

  document.addEventListener("DOMContentLoaded", showSlides);
</script>


Explaination of the game

* Genre: 2D top-down cooking adventure
* Type of project: Graduation project
* Engine: Unity
* Supported platforms: Windows / HTML
* Schedule: 2024.01 ~ 2024.12
* Team/solo: Team of two
* Status: Finished prototype
* Role: Game designer, game programmer

## Contributions / Responsibilities

### Design Goal

### Highlights / Major Contributions

### Minor Contributions

### Major Challenges

Add images / codes to explain

### Possible Improvements

## Reviews / Feedbacks

## Gameplay Videos

