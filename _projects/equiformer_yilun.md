---
layout: page
title: Equiformer
description: by Yi-Lun Liao (MIT)
img: assets/img/talks/equiformer-yi-lun.png
importance: 1
category: md-simulations

---



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/talks/equiformer-yi-lun.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<hr>



**Topic**:  [**Equiformer: Equivariant Graph Attention Transformer for 3D Atomistic Graphs**](https://arxiv.org/abs/2206.11990)



<hr>

**Abstract:**  

Despite their widespread success in various domains, Transformer networks have yet to perform well across datasets in the domain of 3D atomistic graphs such as molecules even when 3D-related inductive biases like translational invariance and rotational equivariance are considered. In this paper, we demonstrate that Transformers can generalize well to 3D atomistic graphs and present Equiformer, a graph neural network leveraging the strength of Transformer architectures and incorporating SE(3)/E(3)-equivariant features based on irreducible representations (irreps). First, we propose a simple and effective architecture by only replacing original operations in Transformers with their equivariant counterparts and including tensor products. Using equivariant operations enables encoding equivariant information in channels of irreps features without complicating graph structures. With minimal modifications to Transformers, this architecture has already achieved strong empirical results. Second, we propose a novel attention mechanism called equivariant graph attention, which improves upon typical attention in Transformers through replacing dot product attention with multi-layer perceptron attention and including non-linear message passing. With these two innovations, Equiformer achieves competitive results to previous models on QM9, MD17 and OC20 datasets.

**Code**: [https://github.com/atomicarchitects/equiformer](https://github.com/atomicarchitects/equiformer)

<hr>


|                     |                                                              |
| ------------------- | ------------------------------------------------------------ |
| **Topic**           | [**Equiformer: Equivariant Graph Attention Transformer for 3D Atomistic Graphs**](https://arxiv.org/abs/2206.11990) |
|                     |                                                              |
| **Slides**          | **TBA**                                                      |
|                     |                                                              |
| **When**            | **23.10.23, 15:00 - 16:15 (CET) / 09:00 - 10:15 (EDT)**      |
|                     |                                                              |
| **Where**           | [**https://us02web.zoom.us/j/85216309906?pwd=cVB0SjNDR2tYOGhIT0xqaGZ2TzlKUT09**](https://us02web.zoom.us/j/85216309906?pwd=cVB0SjNDR2tYOGhIT0xqaGZ2TzlKUT09) |
|                     |                                                              |
| **Video Recording** | **TBA**                                                      |

<hr>

**Speaker(s):**

Yi-Lun Liao is a PhD student at MIT where he is working on Equivariant Neural Nets for Natural Science applications under the supervision of [Tess Smidt](https://blondegeek.github.io).

Previously, he was an intern at Meta AI where he worked on developing EquiformerV2. Before starting his PhD, he obtained his Bachelor's degree in Electrical Engineering from the National Taiwan University in Taipei, Taiwan.

