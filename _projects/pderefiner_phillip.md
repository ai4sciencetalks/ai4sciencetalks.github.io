---
layout: page
title: PDE-Refiner
description: by Phillip Lippe (MSR AI4Science/UvA)
img: assets/img/talks/pderefiner-msr-phillip.png
importance: 1
category: pde

---



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/talks/pderefiner-msr-phillip.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<hr>


**Topic**:  [**PDE-Refiner: Achieving Accurate Long Rollouts with Neural PDE Solvers**](https://arxiv.org/abs/2308.05732)



<hr>

**Abstract:**  

Time-dependent Partial Differential Equations (PDEs) are ubiquitous in science and engineering. Recently, mostly due to the high computational cost of traditional solution techniques, deep neural network based surrogates have gained increased interest. The practical utility of such neural PDE solvers relies on their ability to provide accurate, stable predictions over long time horizons, which is a notoriously hard problem. In this work, we present a large-scale analysis of common temporal rollout strategies, identifying the neglect of non-dominant spatial frequency information, often associated with high frequencies in PDE solutions, as the primary pitfall limiting stable, accurate rollout performance. Based on these insights, we draw inspiration from recent advances in diffusion models to introduce PDE-Refiner, a novel model class that enables more accurate modeling of all frequency components via a multi-step refinement process. We validate PDE-Refiner on challenging benchmarks of complex fluid dynamics, demonstrating stable and accurate rollouts that consistently outperform state-of-the-art models, including neural, numerical, and hybrid (neural-numerical) architectures. We further demonstrate that PDE-Refiner greatly enhances data efficiency, since the denoising objective implicitly induces a novel form of spectral data augmentation. Finally, PDE-Refiner's connection to diffusion models enables an accurate and efficient assessment of the model's predictive uncertainty, allowing us to estimate when the surrogate becomes inaccurate.

**Project Page**: [https://phlippe.github.io/PDERefiner](https://phlippe.github.io/PDERefiner)

<hr>


|                     |                                                              |
| ------------------- | ------------------------------------------------------------ |
| **Topic**           | [**PDE-Refiner: Achieving Accurate Long Rollouts with Neural PDE Solvers**](https://arxiv.org/abs/2308.05732) |
|                     |                                                              |
| **Slides**          | **TBA**                                                      |
|                     |                                                              |
| **When**            | **28.08.23, 15:00 - 16:15 (CET) / 09:00 - 10:15 (EDT)**      |
|                     |                                                              |
| **Where**           | [**https://us02web.zoom.us/j/85216309906?pwd=cVB0SjNDR2tYOGhIT0xqaGZ2TzlKUT09**](https://us02web.zoom.us/j/85216309906?pwd=cVB0SjNDR2tYOGhIT0xqaGZ2TzlKUT09) |
|                     |                                                              |
| **Video Recording** | **TBA**                                                      |

<hr>

**Speaker(s):**

[Phillip Lippe](https://phlippe.github.io) is a PhD student in the QUVA lab at the University of Amsterdam supervised by [Efstratios Gavves](https://www.egavves.com/) and [Taco Cohen](https://tacocohen.wordpress.com/). He is also part of the ELLIS PhD program in cooperation with Qualcomm. His research mostly focuses on the intersection of causality and machine learning, particularly on causal representation learning and temporal data. Besides that, he is a Machine Learning Google Developer Expert for JAX and Flax.

Previously, he was an intern at Microsoft Research. Before starting his PhD, he completed his Master degree in Artificial Intelligence at the University of Amsterdam, with his thesis on Categorical Normalizing Flows.

Google Scholar: [https://scholar.google.de/citations?user=69hFZp4AAAAJ](https://scholar.google.de/citations?user=69hFZp4AAAAJ)

