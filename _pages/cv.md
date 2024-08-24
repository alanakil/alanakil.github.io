---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Mathematics, University of Houston, 2021
  * Advisor: [Krešimir Josić](https://www.math.uh.edu/~josic/)
  * Dissertation: ["The Dynamics of Balanced Neural Networks Under Spike-Timing Dependent Plasticity"](https://uh-ir.tdl.org/handle/10657/8131)
* B.S. in Mathematics, University of Nebraska-Lincoln, 2016
* B.S. in Chemical Engineering, University of Nebraska-Lincoln, 2016

Work experience
======

* AI/ML Engineer II, Project Management Institute; April 2024 – Present
  * Technical leadership for PMI's [Infinity](https://infinity.pmi.org/) portfolio of AI-powered products.

* Data Scientist I, Project Management Institute; July 2021 – March 2024
  * Upgraded cohort Customer Lifetime Value (CLV) model to a probabilistic model that predicts individual CLV using survival functions and historic transaction data. Uncovered similar lifetime patterns across segments.
  * Led a cross-functional team of data scientists, engineers, and business stakeholders to equip [Career Navigator](https://navigator.pmi.org) with three recommendation systems to guide users in their careers.
  * Predicted users' visit intent and likelihood to convert using web activity. Uncovered insightful behaviors and interests that supported Customer Segmentation.

* Graduate Research and Teaching Assistant, University of Houston (Houston, TX); August 2016 – May 2021
  * Developed theory of plasticity in balanced neural networks backed by large-scale simulations of networks of 10,000+ neurons in MATLAB and Python. All code is publicly accessible. Python–packaged customizable, sample network as a pip–installable library for public use (Link to [package](https://github.com/alanakil/PlasticBalancedNetsPackage)).
  * Simulated balanced networks under inhibitory plasticity to explain optogenetically–evoked changes in correla-
tions of local networks in visual cortex of monkeys.
  * Taught recitation sections of various math undergraduate-level courses of 50+ students each. Led and supervised team of 7 undergraduate students to grade udnergraduate-level math homework and exams.
  

<!-- Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3 -->

Publications
======
  <ul>{% assign sorted_publications = site.publications | sort: 'date' | reverse %}
    {% for post in sorted_publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% assign sorted_talks = site.talks | sort: 'date' | reverse %}
    {% for post in sorted_talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
<!-- Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
  
Service and leadership
======
* Secretary of [UH American Mathematical Society Graduate Chapter](https://www.math.uh.edu/ams/); August 2020 - May 2021
* President of [UH American Mathematical Society Graduate Chapter](https://www.math.uh.edu/ams/); August 2019 - August 2020
* Treasurer of [UH American Mathematical Society Graduate Chapter](https://www.math.uh.edu/ams/); August 2017 - August 2019
* Member of American Mathematical Society (AMS) and Society for Industrial and Applied Mathematics (SIAM)
* Graduate Tuition Fellowship; August 2016 – May 2021
