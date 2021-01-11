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
* Ph.D in Neuroscience, Sorbonne University, 2021 (expected)
* M.S. in Biomedical Engineering, Sorbonne University, 2017
* B.S. in Physics, Yildiz Technical University, 2010

Work experience
======
* 2018 - now: Researcher
  * Sorbonne University, Paris Brain Institute
  * Anatomo-functional organisation of subthalamic nucleus (STN) in human via
  diffusion Magnetic Resonance Imaging (dMRI)
    * Duties included: diffusion MRI processing, machine learning
  * Supervisor: Carine Karachi & Eric Bardinet

* 2017 - 2018: Research Engineer
  * Sorbonne University, Paris Brain Institute
  * Phantom based evaluation of geometric distortions in clinical Magnetic
  Resonance Imaging (MRI)
  * Supervisor: Eric Bardinet

Skills
======
* Matlab, R, Python
* Data analysis: Machine learning algorithms
* Neuroimaging tools: MRTrix, FSL, Freesurfer, ANTs, 3D Slicer

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
