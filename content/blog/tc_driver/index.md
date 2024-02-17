---
title: "TC-Driver: A Trajectory Conditioned Reinforcement Learning Approach to Zero-Shot Autonomous Racing"
date: "2023-04-01"
image: "/blog/tc_driver/cover.png"
draft: false
author: "Edoardo Ghignone"
description: ""
catecories: ["paper"]
tags: []
series: [Papers]
---￼
# TC-Driver

## Abstract 
Autonomous racing is becoming popular for academic and industry researchers as a test
for general autonomous driving by pushing perception, planning, and control algorithms to their
limits. While traditional control methods such as model predictive control are capable of generating
an optimal control sequence at the edge of the vehicles’ physical controllability, these methods are
sensitive to the accuracy of the modeling parameters, such as tire modeling coefficients. As model
mismatch is inevitable in reality, the heuristic nature of Reinforcement Learning (RL) offers a viable
approach to modeling robustness. This paper presents TC-Driver, an RL approach for robust control
in autonomous racing. In particular, the TC-Driver agent is conditioned by a trajectory generated
by any arbitrary traditional high-level trajectory planner. The proposed TC-Driver architecture
addresses the tire parameter modeling inaccuracies by exploiting the learning capabilities of RL while
utilizing the reliability of traditional planning methods in a hybrid fashion. We train the agent under
varying tire conditions, allowing it to generalize to different model parameters, aiming to increase
the racing capabilities of the system in practice. Experimental results demonstrate that the proposed
hybrid RL architecture of the TC-Driver improves the generalization robustness of autonomous
racing agents when compared to a previous state-of-the-art end-to-end-based architecture. Namely,
the proposed controller yields a 29-fold improvement in crash ratio when facing model mismatch
and can zero-shot transfer its behavior on unseen tracks which present completely new features,
while the end-to-end baseline fails. When deployed on a physical system, the proposed architecture
demonstrates zero-shot Sim2Real capabilities that outperform end-to-end agents 10-fold in terms
of crash ratio while exhibiting similar driving characteristics in reality as in simulation.

[Full Article]((https://www.research-collection.ethz.ch/bitstream/handle/20.500.11850/620280/Vol3_20.pdf?sequence=3))

## Authors
Ghignone Edoardo, Baumann Nicolas, Magno Michele