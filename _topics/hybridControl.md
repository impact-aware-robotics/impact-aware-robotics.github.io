---
layout: single 
classes: wide
entries_layout: grid

author_profile: true 
title: "Handling Task-Induced Impacts with Hybrid Control Approach"
excerpt: "We enable swift robot motion without fearing impacts with the environment. For instance in a box manipulation task, the robot does not need to stop or use close-to-zero velocity to establish contacts <br/><img src='/images/box-grabbing-crop.png'>"

---

Hybrid control is a powerful modeling and control tool for non-smooth mechanical systems in general. It has already achieved successful applications in practice, e.g., efficient bipedal walking by [Sreenath et al. (2011)](http://ece.umich.edu/faculty/grizzle/papers/MABEL_CompliantHZDWalking2010.pdf), walking over uneven terrain [Manchester et al.(2011)](https://dspace.mit.edu/bitstream/handle/1721.1/62544/Tedrake_Stable%20dynamic.pdf?sequence=1&isAllowed=y), and dynamic bipedal vertical climbing in simulation by [Aghasadeghi et al. (2012)](https://ieeexplore.ieee.org/abstract/document/6225259/).


Never the less, to better exploit the hybrid control approaches for a broad task spectrum, there are practical issues to be addressed, for instance:

  * Robustness to the switching time

The reference tracking performance relies on the proper switching between different control modes. Thus sensitivity analysis are desired due to the event uncertainties, e.g., impact detection.

  * Difficult to plan trajectories for high dimensional joint space

The humanoid robot joint space dimension is typically too high to design a reference trajectory for each joint. The formal connection between the template and anchor model, e.g. full dynamics of a humanoid robot and the linear inverted pendulum model (LIPM), is not fully addressed. Thus there does not exist a mathematical proof that guarantees the tracking of the anchor model reference. 


Thus we would like to gather the latest advancements in hybrid control design and share with the community.

