---
layout: default
title: Home
seo_title: Shumaita | Shumaita Binte Burhan - Portfolio
permalink: /
description: Shumaita Binte Burhan - portfolio of a Computer Science and Engineering graduate working in NLP, large language models, information retrieval, AI agents, and computer vision.
keywords: Shumaita, Shumaita Binte Burhan, natural language processing, large language models, information retrieval, AI agents, computer vision, machine learning
nav: false
---

<div class="portfolio-home">
  <section class="portfolio-hero" aria-labelledby="hero-title">
    <div class="hero-copy">
      <p class="hero-kicker">B.Sc. in Computer Science and Engineering · IIUC · Chattogram</p>
      <h1 id="hero-title">Shumaita Binte Burhan</h1>
      <p class="hero-lede">I am interested in natural language processing, large language models, information retrieval, AI agents, and computer vision.</p>
      <div class="hero-actions" aria-label="Contact and résumé">
        <a class="portfolio-button primary" href="{{ '/assets/pdf/resume.pdf' | relative_url }}">View CV</a>
        <a class="portfolio-button secondary" href="mailto:shumaitabinteburhan@gmail.com">Email me</a>
      </div>
      <div class="hero-links hero-professional-links" aria-label="Professional profiles">
        <a href="https://github.com/Shumaita">GitHub <span aria-hidden="true">↗</span></a>
        <a href="https://www.linkedin.com/in/shumaita-binte-burhan-617063222">LinkedIn <span aria-hidden="true">↗</span></a>
        <a href="https://openreview.net/profile?id=~Shumaita_Binte_Burhan1">OpenReview <span aria-hidden="true">↗</span></a>
        <a href="https://ieeexplore.ieee.org/author/434933835857162">IEEE Xplore <span aria-hidden="true">↗</span></a>
        <a href="https://www.researchgate.net/profile/Shumaita-Binte-Burhan">ResearchGate <span aria-hidden="true">↗</span></a>
      </div>
    </div>
    <div class="hero-portrait">
      <!-- Add your photo as assets/img/profile.webp and replace this block with:
           <img src="{{ '/assets/img/profile.webp' | relative_url }}" alt="Portrait of Shumaita Binte Burhan" width="960" height="960"> -->
      <div style="aspect-ratio:1/1;display:flex;align-items:center;justify-content:center;font-size:5rem;font-weight:700;border-radius:24px;background:rgba(127,127,127,.15)" aria-hidden="true">SB</div>
    </div>
    <article class="hero-latest" aria-labelledby="latest-work-title">
      <p class="hero-latest-label">Academic <span>Results</span></p>
      <div>
        <h2 id="latest-work-title">CGPA 3.908 / 4.0</h2>
        <p>B.Sc. in Computer Science and Engineering, International Islamic University Chittagong (2021 – 2025).</p>
      </div>
      <p class="hero-latest-stats">Supervisor: <a href="https://scholar.google.ca/citations?user=_SXy3FkAAAAJ&amp;hl=en">Md. Khaliluzzaman</a></p>
    </article>
  </section>

  <section class="portfolio-section" aria-labelledby="interests-heading">
    <div class="section-heading">
      <div>
        <p class="section-marker">Research</p>
        <h2 id="interests-heading">Research interests</h2>
      </div>
      <p>Areas I want to explore in graduate research.</p>
    </div>
    <ul class="project-tags" aria-label="Research interests">
      <li>Natural Language Processing</li>
      <li>Large Language Models</li>
      <li>Information Retrieval</li>
      <li>AI Agents</li>
      <li>Image Processing</li>
      <li>Neural Networks</li>
      <li>Computer Vision</li>
      <li>Machine Learning</li>
    </ul>
  </section>

  <section class="portfolio-section selected-work-section" aria-labelledby="featured-heading">
    <div class="section-heading">
      <div>
        <p class="section-marker">Selected work</p>
        <h2 id="featured-heading">Selected projects</h2>
      </div>
      <p>Academic projects in machine learning, AI, and security.</p>
    </div>
    {% assign selected_projects = site.data.portfolio | where: 'homepage', true | sort: 'homepage_order' %}
    <div class="work-grid">
      {% for project in selected_projects %}
        {% include portfolio/project-card.liquid project=project card_class="work-card" home=true %}
      {% endfor %}
    </div>
    <div class="section-action"><a class="text-link" href="{{ '/work/' | relative_url }}">Explore all projects <span aria-hidden="true">→</span></a></div>
  </section>

  <section class="portfolio-section" aria-labelledby="pubs-heading">
    <div class="section-heading">
      <div>
        <p class="section-marker">Research</p>
        <h2 id="pubs-heading">Publications</h2>
      </div>
      <p>Papers in computer vision and vision-language models.</p>
    </div>
    <div class="section-action"><a class="text-link" href="{{ '/publications/' | relative_url }}">View all publications <span aria-hidden="true">→</span></a></div>
  </section>

  <section class="portfolio-section career-section" aria-labelledby="career-heading">
    <div class="section-heading">
      <div>
        <p class="section-marker">Career</p>
        <h2 id="career-heading">Experience and education</h2>
      </div>
      <p>Teaching and undergraduate study.</p>
    </div>
    <div class="portfolio-timeline">
      <article class="timeline-item"><p class="timeline-date">Jul – Dec 2024</p><div><h3>Teaching Assistant</h3><p>International Islamic University Chittagong · Bangladesh</p><p class="timeline-detail">Conducted labs for Tools and Technologies for Internet Programming and supported undergraduate students.</p></div></article>
      <article class="timeline-item"><p class="timeline-date">Jun 2023 – Jun 2024</p><div><h3>Intern, Web Development</h3><p>Black Origin</p><p class="timeline-detail">Front-end development and support across various web development projects.</p></div></article>
      <article class="timeline-item"><p class="timeline-date">2021 – 2025</p><div><h3>B.Sc. in Computer Science and Engineering</h3><p>International Islamic University Chittagong · CGPA 3.908/4.0</p></div></article>
    </div>
    <div class="section-action"><a class="text-link" href="{{ '/experience/' | relative_url }}">View full experience <span aria-hidden="true">→</span></a></div>
  </section>

  <section class="portfolio-section contact-section" aria-labelledby="contact-heading">
    <div class="contact-panel">
      <div><p class="section-marker">Contact</p><h2 id="contact-heading">Let’s talk about research.</h2></div>
      <div class="hero-links">
        <a class="portfolio-button primary" href="mailto:shumaitabinteburhan@gmail.com">Email me</a>
        <a href="https://www.linkedin.com/in/shumaita-binte-burhan-617063222">LinkedIn</a>
        <a href="https://github.com/Shumaita">GitHub</a>
        <a href="https://openreview.net/profile?id=~Shumaita_Binte_Burhan1">OpenReview</a>
        <a href="https://ieeexplore.ieee.org/author/434933835857162">IEEE Xplore</a>
        <a href="https://www.researchgate.net/profile/Shumaita-Binte-Burhan">ResearchGate</a>
      </div>
    </div>
  </section>
</div>

