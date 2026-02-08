---
title: "Iterative learning control with mismatch compensation for residual vibration suppression in delta robots"
collection: publications
category: manuscripts
permalink: /publication/2025-NonlinDyn_ILC_Delta_Robots
excerpt: 'We propose an adaptive mismatch compensated iterative learning controller based on input shaping techniques for precise reference tracking in Delta robots.'
date: 2025-05-22
venue: 'Nonlinear Dynamics, Volume 113'
paperurl: 'https://link.springer.com/article/10.1007/s11071-025-11299-6'
citation: 'Mingkun Wu, Alisa Rupenyan, Burkhard Corves, Nonlinear Dynamics, Volume 113, Pages 21631-21651, 2025'
---

Unwanted vibrations stemming from the energy-optimized design of Delta robots pose a challenge in their operation, especially with respect to precise reference tracking. To improve tracking accuracy, this paper proposes an adaptive mismatch compensated iterative learning controller based on input shaping techniques. More precisely, we establish a comprehensive dynamic model of the Delta robot, capturing the rigid-flexible coupling relationship of the Delta robot and incorporating the dynamics of the permanent magnet synchronous motor. Using this model, we design an optimization-based input shaper, considering the robot's configuration-dependent natural frequency to effectively mitigate unwanted residual vibrations. Furthermore, we propose an iterative learning controller for the delta robot to improve tracking accuracy, which addresses model mismatch by a fuzzy logic structure and designs adaptive parameter update laws to ensure convergence. The convergence property of the proposed controller is rigorously proved using a barrier composite energy function, providing a guarantee that the tracking errors along the iteration axis converge to zero. Finally, we perform a series of high-fidelity simulations of the Delta robot using Simscape to demonstrate the effectiveness of the proposed control strategy.
