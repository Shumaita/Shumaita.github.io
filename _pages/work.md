---
layout: page
title: Projects
permalink: /work/
description: Academic projects in machine learning, AI, security, and software development.
nav: true
nav_order: 2
---

{% assign projects = site.data.portfolio | sort: 'work_order' %}

<section class="project-section" aria-labelledby="ml-ai">
  <div class="project-section-heading">
    <p class="section-marker">Machine learning and AI</p>
    <h2 id="ml-ai">Learning and intelligent systems</h2>
    <p>Computer vision and AI search projects.</p>
  </div>
  <div class="project-grid">
    {% for project in projects %}
      {% if project.category == 'ml-ai' %}
        {% include portfolio/project-card.liquid project=project card_class="project-card" %}
      {% endif %}
    {% endfor %}
  </div>
</section>

<section class="project-section" aria-labelledby="systems-security">
  <div class="project-section-heading">
    <p class="section-marker">Systems and security</p>
    <h2 id="systems-security">Monitoring and security analysis</h2>
    <p>Understanding how systems and attacks behave.</p>
  </div>
  <div class="project-grid">
    {% for project in projects %}
      {% if project.category == 'systems-security' %}
        {% include portfolio/project-card.liquid project=project card_class="project-card" %}
      {% endif %}
    {% endfor %}
  </div>
</section>

<section class="project-section" aria-labelledby="software-web">
  <div class="project-section-heading">
    <p class="section-marker">Software and web</p>
    <h2 id="software-web">Applications and front-end work</h2>
    <p>Visualization tools and web development.</p>
  </div>
  <div class="project-grid">
    {% for project in projects %}
      {% if project.category == 'software-web' %}
        {% include portfolio/project-card.liquid project=project card_class="project-card" %}
      {% endif %}
    {% endfor %}
  </div>
</section>

