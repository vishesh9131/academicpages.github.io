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
* M.C.A. (Hons) Artificial Intelligence
* Research work at Indian Institute of Science (IISc) Bangalore

Work experience
======
* Research Assistant — IISc Bangalore, CDS / AIREX Lab
  * Advisor: Prof. Sashikumaar Ganesan
  * Computational modeling, language modeling, ML; defense-oriented applications (DRDO)

* NVIDIA — TEGRA team
  * Data / ML work tied to autonomous driving (DriveNet pipeline)

* Open source / product
  * CoreRec, BHASA, oioi, SLYRIC; Apple AxLearn contributions

Skills
======
* Python, ML systems, recommender stacks
* State-space / Mamba-style language modeling
* Edge / realtime ML (sign language, lightweight utilities)
* Research engineering and open-source packaging (PyPI)

Publications / projects
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Portfolio
======
  <ul>{% for post in site.portfolio %}
    {% include archive-single.html %}
  {% endfor %}</ul>
