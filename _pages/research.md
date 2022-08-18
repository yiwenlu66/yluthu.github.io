---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

## Safe and Efficient Design for LQ Adaptive Control

LQR/LQG have been a fundamental problem in optimal control, and LQR/LQG with unknown model parameters has drawn renewed attention as a benchmark for continuous control by reinforcement learning. Progress has been made in understanding the statistical properties of "learning to control" algorithms, but practical safety concerns like closed-loop stability have been less discussed. We formalize and analyze a safeguard mechanism commonly used in engineering: normally using the learned controller $K_1$, while switching to a stabilizing fallback controller $K_0$ when potential instability is detected.

![Switching controller design](/images/switch.png)

Our results include:

- Stability of closed-loop system and maximum performance loss caused by switching: [CDC22 paper](https://arxiv.org/pdf/2205.08817)
- Regret with controller learned online: in progress

## Autonomous Car Drifting

Driving an autonomous car beyond the tire saturation limit is an exciting control problem, with challenges including high nonlinearity, inaccuracy in modeling and strict requirement on real-time computation. We apply online system identification and data-driven control techniques to achieve complex drift maneuvers.

<iframe src="//player.bilibili.com/player.html?aid=506333261&bvid=BV14u411o7TS&cid=432151143&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>

<iframe src="//player.bilibili.com/player.html?aid=899609546&bvid=BV1LN4y1V7Nt&cid=805243803&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>

[ICRA22 paper](https://arxiv.org/pdf/2109.06730)
