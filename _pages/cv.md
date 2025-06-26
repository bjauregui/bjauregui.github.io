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
* Mathematical Engineering, University of Chile, 2022
* B.S. Applied Math,University of Chile, 2021

Work experience
======

* Teacher Assistant
  * Universidad de Chile
  * Courses: Calculus Integer Linear Programming, Optimization, Probabilities, Statistics, Combinatorial Algorithms, Computational Complexity, Discrete Maths, etc.
  
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
