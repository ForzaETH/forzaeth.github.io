+++
author = "Edoardo Ghignone"
title = "MAP Paper"
title_short = "map-paper"
date = "2023-05-02"
description = "Sample article showcasing basic Markdown syntax and formatting for HTML elements."
image = "blog/map-paper/cover.png"
categories = [
    "papers",
    "control",
]
series = ["Papers"]
+++

# MAP Paper

## Abstract
Autonomous racing is a research field gaining large popularity, as it pushes autonomous driving algorithms to their limits and serves as a catalyst for general autonomous driving. For scaled autonomous racing platforms, the computational constraint and complexity often limit the use of Model Predictive Control (MPC). As a consequence, geometric controllers are the most frequently deployed controllers. They prove to be performant while yielding implementation and operational simplicity. Yet, they inherently lack the incorporation of model dynamics, thus limiting the race car to a velocity domain where tire slip can be neglected. This paper presents Model- and Acceleration-based Pursuit (MAP) a high-performance model-based trajectory tracking algorithm that preserves the simplicity of geometric approaches while leveraging tire dynamics. The proposed algorithm allows accurate tracking of a trajectory at unprecedented velocities compared to State-of-the-Art (SotA) geometric controllers. The MAP controller is experimentally validated and outperforms the reference geometric controller four-fold in terms of lateral tracking error, yielding a tracking error of 0.055m at tested speeds up to 11m/s.

## Video

{{< youtube lE_Dk1iJHHg >}}
