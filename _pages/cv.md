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
* B.S. in Mechanical Engineering, Yuan Ze University, 2007
* M.S. in Applied Mechanics, National Taiwan University, 2009
* Ph.D. in Electrical and Computer Engineering, University of Maryland, 2020 (expected)

Work Experience
======
* 2015 - Present: Graduate Research Assistant

  Expression Microdissection (xMD) is an optical tissue microdissection method that isolates target cancer cells from tumor tissue samples for downstream molecular analysis. However, xMD suffers from over-heating problem that can result in contamination of the analysis. My duties include the followings:
  * Proposed a mathematica model that explains the physics behind xMD
  * Designed experimental approaches to validate the xMD model.
  * Built a laser raster system from scratch to implement xMD, and designed a control software module for the system with LabVIEW.
  * Solved the problem of measuring temperature in a micro-scaled thin tissue-mimicking phantoms.
  * Simulated transient temperature distribution in the phantoms during laser irradiation in different conditions with COMSOL
  * Demonstrated the significant correlation between the simulations and experimental results.
  * Implemented systematic approach to optimize the xMD process by deep learning so that xMD extracts only target cells and cause no damage to them due to the over-heating.
  * Commercialized a compact xMD laser raster system with model-based systems engineering. 

* 2013 - 2015: Software Engineer

  Electronic product test before launch inevitably needs many operators, thus, may cause human erros and require more cost and time. Therfore, to develop a electronic product automation and testing line, my job was the following:   
  * Designed and built control algorithms for elevators and conveyors of the line with finite state machines.
  * Implemented the machines with LabVIEW in NI single board RIO that controls and bridges the elevators and conveyors with other line subsystems, i.e., robotic arms.
  * Solved interaction problem between the line subsystems by IO handshaking and JSON protocols.
  * Validated the elevators and conveyors by field test.

* 2011 - 2013: Research Assistant

  My responsibility was to conduct experiments to validate bioinstrumentation systems and products, and processed the experimental results by machine learning classification methods and statistical analyses. Specifically, my job was the following:
  * Designed and conducted experiments to statistically validate biomedical systems. For example, factor analysis for questionnaire evaluation.
  * Developed a software testing module to record the emotion indicator and EEG of subjects simultaneously and used Support Vector Machine to classify the indicator and EEG.
  * Drafted journal articles and conference papers, and delivered presentations and posters at conferences.
  
Skills
======
* Python
* MATLAB
* LabVIEW
  * NI SoftMotion module
  * NI FPGA module
  * NI vision development module
* COMSOL
* Solidworks

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
