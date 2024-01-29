+++
author = "Tian Yi Lim"
title = "Robustness Evaluation of Localization Techniques for Autonomous Racing"
title_short = "synpf_paper"
date = "2024-01-15"
# image = "blog/synpf_paper/cover.png"
tags = [
]
categories = [
    "papers",
    "perception",
]
series = ["Papers"]
[header]
image = "synpf_paper/cover.png"
+++

# SynPF Paper

## Abstract 
This work introduces SynPF, an MCL-based algorithm tailored for high-speed racing environments. Benchmarked against Cartographer, a state-of-the-art pose-graph SLAM algorithm, SynPF leverages synergies from previous particle-filtering methods and synthesizes them for the high-performance racing domain. Our extensive in-field evaluations reveal that while Cartographer excels under nominal conditions, it struggles when subjected to wheel-slip—a common phenomenon in a racing scenario due to varying grip levels and aggressive driving behaviour. Conversely, SynPF demonstrates robustness in these challenging conditions and a low-latency computation time of 1.25 ms on on-board computers without a GPU. Using the F1TENTH platform, a 1:10
scaled autonomous racing vehicle, this work not only highlights the vulnerabilities of existing algorithms in high-speed scenarios, tested up until 7.6 m s−1, but also emphasizes the potential of SynPF as a viable  alternative, especially in deteriorating odometry conditions.