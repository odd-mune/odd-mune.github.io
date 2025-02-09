---
layout: page
title: "Portfolio"
permalink: /portfolio/
---

<h1>Projects</h1>

<div class="portfolio-grid">
  {% for project in site.projects %}
  <div class="portfolio-item">
    <a href="{{ project.url }}">
      <img src="{{ project.image }}" alt="{{ project.title }}">
      <div class="overlay">{{ project.title }}</div>
    </a>
  </div>
  {% endfor %}
</div>

<style>
  .portfolio-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    padding: 20px;
  }

  .portfolio-item {
    position: relative;
    overflow: hidden;
    border-radius: 10px;
  }

  .portfolio-item img {
    width: 100%;
    height: auto;
    display: block;
    transition: transform 0.3s ease-in-out;
  }

  .portfolio-item:hover img {
    transform: scale(1.05);
  }

  .overlay {
    position: absolute;
    bottom: 0;
    width: 100%;
    background: rgba(0, 0, 0, 0.7);
    color: white;
    text-align: center;
    padding: 10px;
    font-size: 1.2em;
  }
</style>
