---

layout: single 
classes: wide
entries_layout: grid
author_profile: true 

title: "Hardware design with high impact affordance"

excerpt: "
High dynamic motion between rigid bodies can lead to severe hardware failures due to abrupt changes in the velocities and torques. Without dedicated hardware or controllers, robots typically operate at a near-zero velocity in the vicinity of contacts.
"

---

High dynamic motion between rigid bodies, i.e., robots and the surrounding environment, can lead to severe hardware failures due to abrupt changes in the velocities and torques. In addition to software improvement, i.e., control or planning, hardware resilience to impact shall inform on how much impact a robot can perform without breaking links, joint mechanisms and embedded electronics.

Designing robust hardware specifically for high dynamic tasks is appealing, and notable progress has been made, see the cheetah robot actuator design by the invited speaker [Wensing](/speakers/wensing) et al. [1] and more recent novel leg design by the invited speaker [Zeyu](/speakers/zeyu) [2]. Once we know the hardware capabilities in terms of impact resilience, we can consider impact-aware motion planning and control.

[1] Patrick M Wensing, Albert Wang, Sangok Seok, David Otten, Jeffrey Lang, and Sangbae Kim. Proprioceptive actuator design in the mit cheetah: Impact mitigation and high-bandwidth physical interaction for dynamic legged robots. IEEE Transactions on Robotics, 33(3):509–522, 2017.

[2] Wesley Roozing, Zeyu Ren, and Nikos G Tsagarakis. An efficient leg with series–parallel and biarticular compliant actuation: design optimization, modeling, and control of the eleg. The International Journal of Robotics Research, page 0278364919893762, 2019.


