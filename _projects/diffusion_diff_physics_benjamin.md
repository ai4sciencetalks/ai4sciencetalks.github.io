---
layout: page
title: Differentiable Physics
description: by Benjamin Holzschuh from TU Munich
img: assets/img/talks/score-match-diff-physics.png
importance: 1
category: simulations, inverse problem, pde

---



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/talks/score-match-diff-physics.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<hr>

**Topic**:  [**Score Matching via Differentiable Physics**](https://arxiv.org/abs/2301.10250)


<hr>

**Abstract:**  

Diffusion models based on stochastic differential equations (SDEs) gradually perturb a data distribution *p*(**x**) over time by adding noise to it. A neural network is trained to approximate the score ∇**x** log *pt*(**x**) at time *t*, which can be used to reverse the corruption process. In this paper, we focus on learning the score field that is associated with the time evolution according to a physics operator in the presence of natural non-deterministic physical processes like diffusion. A decisive difference to previous methods is that the SDE underlying our approach transforms the state of a physical system to another state at a later time. For that purpose, we replace the drift of the underlying SDE formulation with a differentiable simulator or a neural network approximation of the physics. We propose different training strategies based on the so-called probability flow ODE to fit a training set of simulation trajectories and discuss their relation to the score matching objective. For inference, we sample plausible trajectories that evolve towards a given end state using the reverse-time SDE and demonstrate the competitiveness of our approach for different challenging inverse problems.

<hr>


|                     |                                                              |
| ------------------- | ------------------------------------------------------------ |
| **Topic**           | [***Score Matching via Differentiable Physics***](https://arxiv.org/abs/2301.10250) |
|                     |                                                              |
| **Slides**          | **TBA**                                                      |
|                     |                                                              |
| **When**            | **20.02.2023, 15:00 - 16:30 (Central European Time)**        |
|                     |                                                              |
| **Where**           | [**https://us02web.zoom.us/j/85216309906?pwd=cVB0SjNDR2tYOGhIT0xqaGZ2TzlKUT09**](https://us02web.zoom.us/j/85216309906?pwd=cVB0SjNDR2tYOGhIT0xqaGZ2TzlKUT09) |
|                     |                                                              |
| **Video Recording** | **TBA**                                                      |


<hr>

**Speaker:**

Benjamin Holzschuh is a 2nd year PhD student at TU München and Max-Planck Institute for Astrophysics. His research focus is at the intersection of Physics and Machine Learning. Prior to starting his doctoral research, he earned both his Bachelor's and Master's from TUM.
