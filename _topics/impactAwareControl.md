---
layout: single 
classes: wide
entries_layout: grid
author_profile: true 

title: "High dynamic motion generation"
excerpt: "
In addition to the human-like kinematic structure, humanoids are expected to execute human-level of swift motions. However referring to the failing manipulation examples in the Darpa Robotics Challenge in 2015, the state-of-the-art humanoid robot control methods still need to applied close-to-zero contact velocity to establish external contacts.
"

---

To guarantee hardware feasibility and standing stability, recent model-based control design preview the impact-induced step changes, see Wang et al. [3]. However it is still not clear how to exploit the full kinematic and dynamic potential for high dynamic tasks.

Employing impact-awareness, the invited speaker [Patrick Wensing](/speakers/wensing) will present strategies for online replanning of impacts during model predictive control using a new hybrid-systems trajectory optimization approach based on differential dynamic programming.

Hybrid control is a powerful modeling and control tool for non-smooth mechanical systems in general. It has achieved successful applications for efficient bipedal walking by Sreenath et al. [10], Manchester et al. [11]. Our invited speaker [Alessandro Saccon](/speakers/saccon/) will present the sensitivity analysis for simultaneous impacts when the switching surface is perturbed, which is common, and vital for hybrid control.

Robots with many degrees of freedom are limited to kinematic and self-collision constraints, the invited speaker [Aude Billard](/speakers/billard/) will present how to exploit the all degrees of freedom in humanoid robots for logistics applications, e.g, box-grabbing tasks, catching manipulation.


[1] Yuquan Wang, Dehio Niels, Arnaud Tanguy, and Abderrahmane Kheddar. Impact-aware task-space quadratic-programming control. 2020. URL https://arxiv.org/pdf/2006.01987.pdf.

[2] Koushil Sreenath, Hae-Won Park, Ioannis Poulakakis, and Jessy W Grizzle. A compliant hybrid zero dynamics controller for stable, efficient and fast bipedal walking on MABEL. The International Journal of Robotics Research, 30(9):1170–1193, 2011.

[3] Ian R Manchester, Uwe Mettin, Fumiya Iida, and Russ Tedrake. Stable dynamic walking over uneven terrain. The International Journal of Robotics Research, 30(3):265–279, 2011.
