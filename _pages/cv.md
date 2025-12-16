---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education
* Tsung-Dao Lee Institute, Shanghai Jiao Tong University: PhD in Astronomy/Astrophysics (2031 expected).
* School of Physics and Astronomy, Shanghai Jiao Tong University: B.S. in Physics (Basic-Strengthening Project, 强基计划) (2026 expected).

## Scientific Research Experience
* 2023 Fall—2025 Spring: Particle physics theory
  * Advisor: Wei Wang (王伟), Hong-Jian He (何红建)
  * Research topics: Loop-diagram calculation with Feynman integrals, Effective field theory for quantum chromodynamics, Non-pertubative quantum field theory methods.
* 2025 Spring—now: Theorectical astrophysics
  * Advisor: Dong Lai (赖东)
  * Research topics: Compact objects (magnetars, neutron stars, black hole binaries, TDEs, etc.), Exoplanetary dynamics (orbital dynamics, rigid-body dynamics, spin-orbit dynamics, etc.), astrophysical dynamics (non-linear, chaos, hydrodynamics, etc.) 

## Publications

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Academic Reports
------
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
