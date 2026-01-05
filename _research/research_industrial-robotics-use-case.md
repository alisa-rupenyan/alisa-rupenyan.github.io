---
layout: single
title: "Industrial Use Case"
permalink: /research/industrial-robotics/use-case/
author_profile: false
parent: Industrial Robotics
---

# Robotic winding for additive manufacturing

## Description

We study the repetitive winding of a carbon fiber wire around a complex geometry core in order to create a wireform structure with high tensile strength. The process currently involves time-consuming stages (manually planning and teaching the robot) to achieve implementation, for each distinct core geometry.

To make it more deployable, we investigate optimization and learning-based methods (e.g., Bayesian, sampling,
gradient-based optimization, meta-learning, model predictive control) in order to:

- Optimize the joint controller gains to closely follow the task (increasing robustness)

- Identify the system-related parameter (e.g., friction, wire elastic modulus)

- Online track of the physical properties of the wire (e.g., tensile strength)

- Generalize to different core geometries

- Automate the operation planning

A digital twin that accurately represents the wire-robot interaction
allows us to get better insights into this process and perform a more rapid adaptation to new
products and tasks. For this, we are exploring several platforms, from available physics-based engines to professional solutions like Siemens Amesim.

Project partners: [ZHAW IMPE](https://www.zhaw.ch/en/engineering/institutes-centres/impe), [NCCR Automation](https://nccr-automation.ch/index.php/research/sustainability-automation), [Siemens Digital Industries](https://www.siemens.com/global/en/company/about/businesses/digital-industries.html).

- Publication: Iterative Tuning of Nonlinear Model Predictive Control for Robotic Manufacturing Tasks,
Deepak Ingole, Valentin Bhend, Shiva Ganesh Murali, Oliver Doebrich, Alisa Rupenyan (under review) https://arxiv.org/abs/2512.13170

<img src="/images/rob_winding.png" alt="robotic winding sim"/>


<video width="640" height="360" controls muted>
  <source src="/video/output.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

<img src="/images/winding1.png" alt="robotic winding on real robot" width="40%"/>




---

[Back to Industrial Robotics](/research/industrial-robotics/)