---
title: "Jia Yan-Bin"
excerpt: "Targeted Batting of In-flight Objects by a Robotic Arm"
layout: single 
classes: wide

sidebar:
  - title: "Professor"
    image: /docs/assets/images/speakers/yan-bin.jpg 
    image_alt: "logo"
    text: "Department of Computer Science
    Iowa State University"

toc: false 
collection: speakers
---

<center style="font-size:30px">
Targeted Batting of In-flight Objects by a Robotic Arm
</center>

##### Abstract

Striking a flying object such as a ball to some target location is a highly skillful maneuver that a human being has to learn  through a great deal of practice. In robotic manipulation, precision batting remains one of the most challenging tasks in which computer vision, modeling, planning, control, and action must be tightly coordinated in a split second. This paper investigates the problem of a 2-DOF robotic arm intercepting an object in free flight and redirecting it to some target with a single strike, assuming all the movements take place in one vertical plane. Two-dimensional impact is solved under Coulomb friction and energy-based restitution with a proof of termination. Planning combines impact dynamics and projectile flight mechanics with manipulator kinematics and image-based motion estimation. As the object is on the incoming flight, the post-impact task constraint of reaching the target is propagated backward in time, while the arm’s kinematic constraints are propagated forward (via joint trajectory interpolation), all to the pre-impact instant when they will meet constraints that allow batting to happen. All the constraints (sixteen in total) are then exerted on the arm’s pre-impact joint angles and velocities, which are repeatedly planned based on updated estimates of the object’s motion captured by a high speed camera. The arm keeps adjusting its motion in sync with planning until batting takes place. Experiments have demonstrated a better batting performance by a Barrett Technology WAM Arm than by a human being without training.


 
| Experiment Setup |  Experiment Video|
:-------------------------:|:-------------------------:
![](/docs/assets/images/objectBatting.jpg)  |  [![Batting-flying-object](/docs/assets/images/objectBattingThree.jpg)](https://www.youtube.com/watch?v=dGBevZ54E3s)


