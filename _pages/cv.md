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
* Ph.D in Mathematical Modeling, University of Chile, 2026 (expected)
* B.S. Applied Math, University of Chile, 2022
* Mathematical Engineering, University of Chile, 2022

Work experience
======

* Prof

* Teacher Assistant
  * Universidad de Chile
  * Courses: Mixed Linear Programming, Optimization, Probabilities, Statistics, Combinatorial Algorithms, Computational Complexity, Discrete Maths, etc.
  
Skills
======
* Numerical Optimization solvers: Gurobi, CPLEX, KNITRO.
* Programming languages: Python (advanced), Julia (advanced), C++ (medium).
  

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
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* "Organizer of the PhD Seminar in Mathematical Modeling, Chile 2024
