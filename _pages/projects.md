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
<h1>Project Experiences</h1>

<ol>

<li>
  <strong><a href="LINK_TO_PROJECT_1">National Natural Science Foundation of China (41601354)</a>:</strong>
  <span class="proj-year">2018-2019</span>
  <p>Research on Multi-view Level Analysis Method of Remote Sensing Fine Change Detection</p>
  <ul>
    <li>Proposed a novel fire index-based burned area change detection approach using Landsat-8 data.</li>
    <li>Designed an automatic change detection method for large-scale remote sensing images.</li>
  </ul>
  <button class="toggle-btn" onclick="toggleImages('project1')">Show More</button>
  <div id="project1" class="image-container">
    <img src="/assets/img/projects/project11.png" alt="Project 1 Image 1">
    <img src="/assets/img/projects/project12.png" alt="Project 1 Image 2">
  </div>
</li>

<li>
  <strong><a href="LINK_TO_PROJECT_2">Key Laboratory of Cities’ Mitigation and Adaptation to Climate Change</a>:</strong>
  <span class="proj-year">2019-2020</span>
  <p>Analyzed the spatio-temporal characteristics of urban LULC and LST over Shanghai during 2009-2019.</p>
  <button class="toggle-btn" onclick="toggleImages('project2')">Show More</button>
  <div id="project2" class="image-container">
    <img src="/assets/img/projects/project21.png" alt="Project 2 Image 1">
    <img src="/assets/img/projects/project22.png" alt="Project 2 Image 2">
  </div>
</li>

<li>
  <strong><a href="LINK_TO_PROJECT_3">National Key R&D Program of China (2018YFB0505000)</a>:</strong>
  <span class="proj-year">2019-2022</span>
  <p>Research on Global Comprehensive Observation Technologies and Shared Service System</p>
  <ul>
    <li>Designed a two-stage multiple feature fusion approach for VHR image classification (based on machine learning).</li>
  </ul>
  <button class="toggle-btn" onclick="toggleImages('project3')">Show More</button>
  <div id="project3" class="image-container">
    <img src="/assets/img/projects/project31.png" alt="Project 3 Image 1">
    <img src="/assets/img/projects/project32.png" alt="Project 3 Image 2">
  </div>
</li>

<li>
  <strong><a href="LINK_TO_PROJECT_4">National Natural Science Foundation of China (42071324)</a>:</strong>
  <span class="proj-year">2021-2024</span>
  <p>Research on Automatic Change Detection Method of Hyperspectral Image with Multi-temporal Deep Features</p>
  <ul>
    <li>Designed a multitemporal deep fusion network for HR image classification (based on deep learning).</li>
  </ul>
  <button class="toggle-btn" onclick="toggleImages('project4')">Show More</button>
  <div id="project4" class="image-container">
    <img src="/assets/img/projects/project41.png" alt="Project 4 Image 1">
    <img src="/assets/img/projects/project42.png" alt="Project 4 Image 2">
  </div>
</li>

</ol>

</div>

<script>
function toggleImages(id) {
  var imgDiv = document.getElementById(id);
  var button = imgDiv.previousElementSibling;
  if (imgDiv.style.display === "none" || imgDiv.style.display === "") {
    imgDiv.style.display = "flex";
    button.innerText = "Show Less";
  } else {
    imgDiv.style.display = "none";
    button.innerText = "Show More";
  }
}
</script>
