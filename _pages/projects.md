---
layout: page
title: Research Projects
permalink: /projects/
description: A growing collection of research projects.
nav: true
nav_order: 3
---

<!-- _pages/projects.md -->
<div class="projects">

<style>
  .project-container {
    margin-bottom: 40px;
    padding: 15px;
    border-bottom: 2px solid #ddd;
  }
  .project-title {
    font-size: 20px;
    font-weight: bold;
  }
  .project-year {
    font-size: 16px;
    color: #555;
    font-style: italic;
  }
  .project-description {
    margin-top: 10px;
    font-size: 16px;
  }
  .project-images {
    display: flex;
    gap: 15px;
    margin-top: 10px;
  }
  .project-images img {
    width: 48%;
    height: auto;
    border-radius: 10px;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
  }
</style>

{% assign projects = site.data.projects %}

{% for project in projects %}
  <div class="project-container">
    <div class="project-title">{{ project.title }}</div>
    <div class="project-year">{{ project.year }}</div>
    <div class="project-description">{{ project.description }}</div>
    <ul>
      {% for point in project.details %}
        <li>{{ point }}</li>
      {% endfor %}
    </ul>
    <div class="project-images">
      <img src="{{ project.image1 | relative_url }}" alt="Project Image 1">
      <img src="{{ project.image2 | relative_url }}" alt="Project Image 2">
    </div>
  </div>
{% endfor %}

</div>
