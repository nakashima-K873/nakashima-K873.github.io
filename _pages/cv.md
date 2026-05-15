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
* Ph.D in Science, Nagoya University, 2026
* M.S. in Science, Nagoya University, 2023
* B.S. in Science, Nagoya University, 2021

Work experience
======
* Spring 2026: Postcoc
  * University of Tsukuba
  * Duties includes: Numerical simulation and data analysis
  * Supervisor: Professor Yajima

* Spring 2022: Research Assistant
  * Nagoya University
  * Duties included: Machine learning and data analysis
  * Supervisor: Professor Ichiki
  
Skills
======
* C/C++
* Python
  * pytorch
* Teaching license (High school) in Japan

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
