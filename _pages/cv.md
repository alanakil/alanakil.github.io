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
* Lead AI/ML Engineer, Project Management Institute; February 2025 – Present

* AI/ML Engineer II, Project Management Institute; April 2024 – January 2025
  
  _Bridging research and application in customer-facing AI systems_

* Data Scientist I, Project Management Institute; July 2021 – March 2024
  
  _Development of AI systems for customer insights_

* Graduate Research and Teaching Assistant, University of Houston (Houston, TX);  2016 – 2021

    _Theoretical foundations of learning in neural networks_

  * **Neural Network Learning Theory:** Developed mathematical framework connecting synaptic plasticity rules to emergent network dynamics. Proved conditions under which learning preserves network balance in recurrent architectures. Theory validated through large-scale simulations.

  * **Computational Neuroscience:** Applied theoretical models to explain experimental observations of rapid plasticity in primate visual cortex. Demonstrated how inhibitory learning mechanisms maintain homeostasis during network perturbations.

  * **Open Source Research Tools:** Created [Python package]{https://github.com/alanakil/PlasticBalancedNetsPackage} implementing theoretical predictions, enabling reproducible research in plastic neural networks. 
  

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
* Secretary of [UH American Mathematical Society Graduate Chapter](https://www.math.uh.edu/ams/); 2020 - 2021
* President of [UH American Mathematical Society Graduate Chapter](https://www.math.uh.edu/ams/); 2019 - 2020
* Treasurer of [UH American Mathematical Society Graduate Chapter](https://www.math.uh.edu/ams/); 2017 - 2019
* Member of American Mathematical Society (AMS) and Society for Industrial and Applied Mathematics (SIAM)
* Graduate Tuition Fellowship; 2016 – 2021
