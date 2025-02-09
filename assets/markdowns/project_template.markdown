---
title: "Gourmet of Fire"
image: "/assets/images/gourmet_of_fire.png"
layout: project
---

## <Project-Name>

Link to the game

<div class="slideshow-container">
  <div class="slides-wrapper">
    <div class="slide"><img src="/assets/images/gourmet_of_fire.png" alt="Gourmet of Fire"></div>
    <div class="slide"><img src="/assets/images/gourmet_of_fire_cooking_ui.jpg" alt="Cooking UI"></div>
    <div class="slide"><img src="/assets/images/gourmet_of_fire_cooking_animation.jpg" alt="Cooking Animation"></div>
    <div class="slide"><img src="/assets/images/gourmet_of_fire_princess_concept.png" alt="Princess Concept"></div>
    <div class="slide"><img src="/assets/images/gourmet_of_fire_dialog.jpg" alt="Dialog"></div>
    <div class="slide"><img src="/assets/images/gourmet_of_fire_field_level.jpg" alt="Field Level"></div>
    <div class="slide"><img src="/assets/images/gourmet_of_fire_village_level.jpg" alt="Village Level"></div>
    <div class="slide"><img src="/assets/images/gourmet_of_fire_in_house_level.jpg" alt="In-House Level"></div>
  </div>
</div>

<style>
  .slideshow-container {
    max-width: 600px;
    position: relative;
    margin: auto;
    overflow: hidden;
    border-radius: 10px;
    aspect-ratio: 16 / 9; /* Maintain a proper aspect ratio */
  }

  .slides-wrapper {
    display: flex;
    transition: transform 1s ease-in-out;
  }

  .slide {
    min-width: 100%;
    flex-shrink: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .slide img {
    max-width: 100%;
    max-height: 100%;
    object-fit: contain; /* Ensures the image fits properly */
  }
</style>

<script>
  let slideIndex = 0;
  function showSlides() {
    let slidesWrapper = document.querySelector(".slides-wrapper");
    let totalSlides = document.querySelectorAll(".slide").length;

    slideIndex++;
    if (slideIndex >= totalSlides) {
      slideIndex = 0;
    }

    slidesWrapper.style.transform = `translateX(${-slideIndex * 100}%)`;
    setTimeout(showSlides, 3000); // Change image every 3 seconds
  }

  document.addEventListener("DOMContentLoaded", showSlides);
</script>


Explaination of the game

* Genre:
* Type of project:
* Engine: 
* Supported platforms:
* Schedule:
* Team/solo:
* Status:
* Role:

## Contributions / Responsibilities

### Design Goal

### Highlights / Major Contributions

### Minor Contributions

### Major Challenges

Add images / codes to explain

### Possible Improvements

## Reviews / Feedbacks

## Gameplay Videos
