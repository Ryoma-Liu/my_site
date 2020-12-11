---
aliases: [arm]
title: Tactile Interaction of Robot Fingertip
summary: 
    <strong>Research Intern at Tongji University, Supervisor.[Prof. Peng Qi](http://orcid.org/0000-0003-0514-9464)</strong><br>
    👌 Designed a novel robot fingertip attached with tactile sensors to explore detailed properties of surfaces<br>
    👌 Presented a robust surface following algorithm based on the tactile force for the fingertip to follow irregular objects and surfaces with discontinuous curvature such as cubes<br>
    👌 Designed a feed forward neural network to classify objects with different adjectives, i.e. soft-smooth soft-rough, hard-smooth, hard-rough<br>z
    📒 Submitted a paper to 2021 IEEE International Conference on Robotics and Automation [C.2]<br> 
abstract: ""
date: "2020-11-07T16:56:12.584Z"
image:
  filename: featured.png
  focal_point: Smart
  preview_only: true
links:
- icon: door-open
  icon_pack: fas
  name: website
  url: https://arm.rbind.io/
- icon: github
  icon_pack: fab
  name: materials
  url: https://github.com/rstudio-education/rmarkdown-extensions-conf19

categories:
- Robotics
tags:
- Tactile Interaction
- Robotics
- Neural Network

---

To effectively interact with the physical world, an intelligent robot is required to have the ability to obtain the detailed features of an unknown object. Visual devices are commonly used to detect the global geometry of an object; however, detailed information such as surface properties cannot be identified using these devices. The current study proposes an adaptive haptic exploration method to recognize the physical properties of surfaces using an intelligent fingertip. Our surface-following algorithm utilizes the normal force vector and the tangential force vector at the contact point between the fingertip and the target object to predict the moving direction and to implement surface exploration. In addition, a correction index K is introduced to adjust the sliding velocity and surface following on irregular objects. The algorithm is proved to be robust and superior both in simulation and lab experiments. Finally, we propose and explore a haptic prediction neural network, which enables our robot to have an accurate feel through physical interaction. The overall accuracy of the proposed model is 90.2%.