---
layout: page
title: "SineNet: Learning Temporal Dynamics in Time-Dependent Partial Differential Equations"  
description: by Xuan Zhang and Jacob Helwig (TAMU, USA)
img: assets/img/talks/sinenet-neural-pde-solver-xzhang.png
importance: 1
category: pde

---



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/talks/sinenet-neural-pde-solver-xzhang.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<hr>



**Topic**:  [**SineNet: Learning Temporal Dynamics in Time-Dependent Partial Differential Equations**](https://arxiv.org/abs/2403.19507)



<hr>

**Abstract:**  

We consider using deep neural networks to solve time-dependent partial differential equations (PDEs), where multi-scale processing is crucial for modeling complex, time-evolving dynamics. While the U-Net architecture with skip connections is commonly used by prior studies to enable multi-scale processing, our analysis shows that the need for features to evolve across layers results in temporally misaligned features in skip connections, which limits the model's performance. To address this limitation, we propose SineNet, consisting of multiple sequentially connected U-shaped network blocks, referred to as waves. In SineNet, high-resolution features are evolved progressively through multiple stages, thereby reducing the amount of misalignment within each stage. We furthermore analyze the role of skip connections in enabling both parallel and sequential processing of multi-scale information. Our method is rigorously tested on multiple PDE datasets, including the Navier-Stokes equations and shallow water equations, showcasing the advantages of our proposed approach over conventional U-Nets with a comparable parameter budget. We further demonstrate that increasing the number of waves in SineNet while maintaining the same number of parameters leads to a monotonically improved performance. The results highlight the effectiveness of SineNet and the potential of our approach in advancing the state-of-the-art in neural PDE solver design. Our code is available as part of AIRS.


<hr>


|                     |                                                              |
| ------------------- | ------------------------------------------------------------ |
| **Topic**           | [**SineNet: Learning Temporal Dynamics in Time-Dependent Partial Differential Equations**](https://arxiv.org/abs/2403.19507) |
|                     |                                                              |
| **Slides**          | **TBA**                                                      |
|                     |                                                              |
| **When**            | **13.05.2024, 15:00 - 16:15 (CEST) / 09:00 - 10:15 (EDT) / 08:00 - 09:15 (CDT)** |
|                     |                                                              |
| **Where**           | [**https://us02web.zoom.us/j/85216309906?pwd=cVB0SjNDR2tYOGhIT0xqaGZ2TzlKUT09**](https://us02web.zoom.us/j/85216309906?pwd=cVB0SjNDR2tYOGhIT0xqaGZ2TzlKUT09) |
|                     |                                                              |
| **Video Recording** | **TBA**                                                      |

<hr>
**Speaker(s):**

Xuan Zhang is a fourth-year PhD student advised by Prof. Shuiwang Ji. Prior to that he received his master's degree in engineering from Shanghai Jiao Tong University, his engineering degree from ENSTA Paris (equivalent to master's degree). His current research focus is on developing deep learning methods for scientific problems, including deep-learning-based physics simulation and computational chemistry.

Jacob Helwig is a 2nd year Ph.D. student in the Department of Computer Science & Engineering at Texas A&M University advised by Prof. Shuiwang Ji. Prior to that he obtained his bachelor’s degree in mathematics from the University of Texas at Austin in 2020, as well as several certificates in computing and statistical modeling through the UT Computer Science Department and the UT Statistics and Data Science Department. He is currently working on data-driven methods for accelerating the numerical solution of partial differential equations.
