---
layout: page
title: How Temporal Unrolling Supports Neural Physics Simulators
description: by Björn List (Technical University Munich)
img: assets/img/talks/temp-unroll-neural-physics-simulator-blist.png
importance: 1
category: pde

---



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/talks/temp-unroll-neural-physics-simulator-blist.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<hr>



**Topic**:  [**How Temporal Unrolling Supports Neural Physics Simulators**](https://arxiv.org/abs/2402.12971)



<hr>

**Abstract:**  

Unrolling training trajectories over time strongly influences the inference accuracy of neural network-augmented physics simulators. We analyze these effects by studying three variants of training neural networks on discrete ground truth trajectories. In addition to commonly used one-step setups and fully differentiable unrolling, we include a third, less widely used variant: unrolling without temporal gradients. Comparing networks trained with these three modalities makes it possible to disentangle the two dominant effects of unrolling, training distribution shift and long-term gradients. We present a detailed study across physical systems, network sizes, network architectures, training setups, and test scenarios. It provides an empirical basis for our main findings: A non-differentiable but unrolled training setup supported by a numerical solver can yield 4.5-fold improvements over a fully differentiable prediction setup that does not utilize this solver. We also quantify a difference in the accuracy of models trained in a fully differentiable setup compared to their non-differentiable counterparts. While differentiable setups perform best, the accuracy of unrolling without temporal gradients comes comparatively close. Furthermore, we empirically show that these behaviors are invariant to changes in the underlying physical system, the network architecture and size, and the numerical scheme. These results motivate integrating non-differentiable numerical simulators into training setups even if full differentiability is unavailable. We also observe that the convergence rate of common neural architectures is low compared to numerical algorithms. This encourages the use of hybrid approaches combining neural and numerical algorithms to utilize the benefits of both.



<hr>


|                     |                                                              |
| ------------------- | ------------------------------------------------------------ |
| **Topic**           | [**How Temporal Unrolling Supports Neural Physics Simulators**](https://arxiv.org/abs/2402.12971) |
|                     |                                                              |
| **Slides**          | **TBA**                                                      |
|                     |                                                              |
| **When**            | **08.04.2024, 15:00 - 16:15 (CEST) / 10:00 - 11:15 (EST) / 08:00 - 09:15 (MST)** |
|                     |                                                              |
| **Where**           | [**https://us02web.zoom.us/j/85216309906?pwd=cVB0SjNDR2tYOGhIT0xqaGZ2TzlKUT09**](https://us02web.zoom.us/j/85216309906?pwd=cVB0SjNDR2tYOGhIT0xqaGZ2TzlKUT09) |
|                     |                                                              |
| **Video Recording** | **TBA**                                                      |

<hr>
**Speaker(s):**

Björn List is a PhD candidate at the Technical University Munich. Previously he completed his M.Sc. from Imperial College London. His current research interests focus on the intersection of computational fluid dynamics and machine learning, specifically the learning-based methods for turbulence modelling with the aim of leveraging such methods to improve simulation accuracy and efficiency.

