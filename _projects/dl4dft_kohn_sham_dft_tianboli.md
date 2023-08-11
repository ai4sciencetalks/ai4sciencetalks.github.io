---
layout: page
title: DL for Density Functional Theory
description: by Dr. Tianbo Li from SEA AI Lab, Singapura.
img: assets/img/talks/dl4dft-tianbo-li.png
importance: 1
category: ml-chemistry
---



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/talks/dl4dft-tianbo-li.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


<hr>

**Topic:   [A Deep Learning Approach to Kohn-Sham Density Functional Theory](https://arxiv.org/abs/2303.00399)**

<hr>
**Abstract**:


Kohn-Sham Density Functional Theory (KS-DFT) has been traditionally solved by the Self-Consistent Field (SCF) method. Behind the SCF loop is the physics intuition of solving a system of non-interactive single-electron wave functions under an effective potential. In this work, we propose a deep learning approach to KS-DFT. First, in contrast to the conventional SCF loop, we propose to directly minimize the total energy by reparameterizing the orthogonal constraint as a feed-forward computation. We prove that such an approach has the same expressivity as the SCF method, yet reduces the computational complexity from O(N^4) to O(N^3). Second, the numerical integration which involves a summation over the quadrature grids can be amortized to the optimization steps. At each step, stochastic gradient descent (SGD) is performed with a sampled minibatch of the grids. Extensive experiments are carried out to demonstrate the advantage of our approach in terms of efficiency and stability. In addition, we show that our approach enables us to explore more complex neural-based wave functions.

**Code**: [https://github.com/sail-sg/d4ft](https://github.com/sail-sg/d4ft)

<hr>

|                     |                                                              |
| ------------------- | ------------------------------------------------------------ |
| **Topic**           | **[A Deep Learning Approach to Kohn-Sham Density Functional Theory](https://arxiv.org/abs/2303.00399)** |
|                     |                                                              |
| **Slides**          | **TBA**                                                      |
|                     |                                                              |
| **When**            | **11.09.23, 14:00-15:00 (CEST) / 20:00 - 21:00 (SGT)**       |
|                     |                                                              |
| **Zoom**            | [https://us02web.zoom.us/j/85216309906?pwd=cVB0SjNDR2tYOGhIT0xqaGZ2TzlKUT09](https://us02web.zoom.us/j/85216309906?pwd=cVB0SjNDR2tYOGhIT0xqaGZ2TzlKUT09) |
|                     |                                                              |
| **Video Recording** | **TBA**                                                      |

<hr>

**Speaker:**

Tianbo Li completed his PhD at NTU Singapore in 2021 and is now with SEA AI Lab, Singapura.
