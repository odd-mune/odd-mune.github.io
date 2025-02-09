---
title: "Gourmet of Fire"
image: "/assets/images/gourmet_of_fire.png"
layout: project
---

<p><iframe width="560" height="315" src="https://www.youtube.com/embed/W7AT3YjdtvY" title="Gourmet of Fire" frameBorder="0"   allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"  allowFullScreen><br>Powered by <a href="https://youtubeembedcode.com">youtube embed code</a> and <a href="https://snabblan.io/">snabblån utan uc</a></iframe></p>

* [Link to the game](https://odd-mune.itch.io/gourmet-of-fire)
* [Instagram](https://www.instagram.com/gourmet_of_fire)
* [Devlogs](https://savory-postage-c8f.notion.site/Gourmet-of-Fire-09430cb0422e4ee8bebb1ec8d10c4811?pvs=24)

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
    width: 100%;
    position: relative;
    margin: auto;
    overflow: hidden;
    border-radius: 10px;
    aspect-ratio: 16 / 9; /* Maintain a proper aspect ratio */
    background-color: black; /* Prevents white flashes */
  }

  .slides-wrapper {
    display: flex;
    transition: transform 1s ease-in-out;
    width: 100%;
  }

  .slide {
    min-width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .slide img {
    max-width: 100%;
    height: auto; /* Keeps aspect ratio */
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

## Overview

"Embark on an adventure to find your own 美味(taste)."

In the land of gourmet, the Kingdom of Cuisine, under the protection of the fire spirit, the ancient flames are passed down, continuing their legacy. The spark that split from the first flame has safeguarded the kingdom's people and contributed to the development of its culinary culture. However, as time passed, the flame began to lose its vigor, and despite the kingdom's efforts to restore it, the flame continues to weaken day by day. In the midst of this decline, the princess, born with the strongest protection of fire and the ability to hear the song of fire, feels a deep sense of responsibility. Determined to solve the crisis, she embarks on an adventure beyond the palace to find a solution.

* Genre: 2D top-down cooking adventure
* Type of project: Graduation project
* Engine: Unity
* Supported platforms: Windows / HTML
* Schedule: January 1, 2024 &rarr; November 15, 2024 (320 days)
* Team/solo: Team of two
* Status: Finished prototype
* Role: Game designer, game programmer

![Synopsis](/assets/images/gourmet_of_fire_creative_submission_01.jpg)

## Contributions / Responsibilities

* Unity
* C#

### Design Goal

### Highlights / Major Contributions

### Minor Contributions

### Major Challenges

Add images / codes to explain

### Possible Improvements

## Reviews / Feedbacks

## Gameplay Videos

