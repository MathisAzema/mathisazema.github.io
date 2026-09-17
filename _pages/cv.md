---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Download my detailed [research CV (PDF)](/files/cv_en.pdf).

Education
======
* Master's degree, Operations Research (MPRO), Conservatoire National des Arts et Métiers, 2024
* Master's degree, Optimization and Data Science, ENSTA Paris, 2024
* Engineering degree, École Polytechnique, 2020–2024 (ranked 10th out of 425 students)
* Engineering school preparatory classes, Lycée Aux Lazaristes, 2018–2020

Work experience
======
* Apr 2024–present: PhD candidate at École des Ponts (CERMICS), Champs-sur-Marne, France
  * Decomposition methods for stochastic, robust and distributionally robust optimization, with applications to power systems.

* Apr–Aug 2023: Research intern at Polytechnique Montréal (GERAD), Montréal, Canada
  * Developed MILP and constraint programming models to solve an electric bus
assignment planning problem.
  * Literature review and writing of two research papers.

* Jun–Sep 2022 and Nov–Dec 2022: Research and development intern at the French Ministry of Ecological and Solidarity Transition, Paris La Défense, France
  * Optimization model on long-term trajectories towards a low-carbon French economy.

Teaching experience
======
* Teaching assistant at École des Ponts
  * Introduction to Optimization, first-year engineering students.
  * Convex Optimization, second-year engineering students.

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
