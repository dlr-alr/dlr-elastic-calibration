---
layout: page
title: 
---

This site presents the dataset used in the paper [Calibration of an Elastic Humanoid Upper Body and Efficient Compensation for Motion Planning ](https://ieeexplore.ieee.org/abstract/document/9555793)



# Abstract
---
High absolute accuracy is an essential prerequisite for a humanoid robot to autonomously and robustly perform manipulation tasks while avoiding obstacles. We present for the first time a kinematic model for a humanoid upper body incorporating joint and transversal elasticities. These elasticities lead to significant deformations due to the robot’s own weight, and the resulting model is implicitly defined via a torque equilibrium. We successfully calibrate this model for DLR’s humanoid Agile Justin, including all Denavit–Hartenberg parameters and elasticities. The calibration is formulated as a combined least-squares problem with priors and based on measurements of the end effector positions of both arms via an external tracking system. The absolute position error is massively reduced from 21 mm to 3.1 mm on average in the whole workspace. Using this complex and implicit kinematic model in motion planning is challenging. We show that for optimization-based path planning, integrating the iterative solution of the implicit model into the optimization loop leads to an elegant and highly efficient solution. For mildly elastic robots like Agile Justin, there is no performance impact, and even for a simulated highly flexible robots with 20 times higher elasticities, the runtime increases by only 30%.
