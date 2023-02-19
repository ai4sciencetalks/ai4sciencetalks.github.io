---
layout: page
title: Neural Fields for PDEs
description: by Dr. Peter Yichen Chen (MIT), Honglin Chen and Rundi Wu (Columbia).
img: assets/img/talks/crom-pde-yichen.png
importance: 1
category: pde

---



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/talks/crom-pde-yichen.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<hr>

**Topic**:  [**Implicit Neural Representations for Solving Partial Differential Equations (PDEs)**](https://arxiv.org/abs/2210.00124)



<hr>

**Abstract:**  

 The long runtime of high-fidelity partial differential equation (PDE) solvers makes them unsuitable for time-critical applications. We propose to accelerate PDE solvers using reduced-order modeling (ROM). Whereas prior ROM approaches reduce the dimensionality of discretized vector fields, our continuous reduced-order modeling (CROM) approach builds a smooth, low-dimensional manifold of the continuous vector fields themselves, not their discretization. We represent this reduced manifold using continuously differentiable neural fields, which may train on any and all available numerical solutions of the continuous system, even when they are obtained using diverse methods or discretizations. We validate our approach on an extensive range of PDEs with training data from voxel grids, meshes, and point clouds. Compared to prior discretization-dependent ROM methods, such as linear subspace proper orthogonal decomposition (POD) and nonlinear manifold neural-network-based autoencoders, CROM features higher accuracy, lower memory consumption, dynamically adaptive resolutions, and applicability to any discretization. For equal latent space dimension, CROM exhibits 79× and 49× better accuracy, and 39× and 132× smaller memory footprint, than POD and autoencoder methods, respectively. Experiments demonstrate 109× and 89× wall-clock speedups over unreduced models on CPUs and GPUs, respectively.

<hr>


|                     |                                                              |
| ------------------- | ------------------------------------------------------------ |
| **Topic**           | [***Implicit Neural Representations for Solving Partial Differential Equations (PDEs)***](https://arxiv.org/abs/2210.00124) |
|                     |                                                              |
| **Slides**          | **TBA**                                                      |
|                     |                                                              |
| **When**            | **13.03.2023, 15:00 - 16:30 (Central European Time) / 09:00 (EST)** |
|                     |                                                              |
| **Where**           | [**https://us02web.zoom.us/j/85216309906?pwd=cVB0SjNDR2tYOGhIT0xqaGZ2TzlKUT09**](https://us02web.zoom.us/j/85216309906?pwd=cVB0SjNDR2tYOGhIT0xqaGZ2TzlKUT09) |
|                     |                                                              |
| **Video Recording** | **TBA**                                                      |


<hr>

**Speaker(s):**

[Dr. Peter Yichen Chen](https://peterchencyc.com) is a postdoc at [MIT CSAIL](https://www.csail.mit.edu/), working with [Wojciech Matusik](https://cdfg.mit.edu/wojciech). Previously, he completed his CS PhD from [Columbia](https://www.columbia.edu/), advised by [Eitan Grinspun](https://www.dgp.toronto.edu/~eitan/). Before that, he was a Sherwood-Prize-winning math undergrad from [UCLA (#GoBruins)](https://www.ucla.edu/), working with [Joey Teran](http://www.math.ucla.edu/~jteran/). He enjoys blending the depth of math with the pragmatism of CS. Throughout his academic career, he has squeezed in three industry research internships at [Tencent Game AI Research Center](https://careers.tencent.com/en-us/home.html), [Meta Reality Labs](https://research.fb.com/category/augmented-reality-virtual-reality/), and [Weta Digital](https://www.wetafx.co.nz/), all of which he appreciated a lot.

[Honglin Chen](https://www.cs.columbia.edu/~honglinchen) is a second-year Computer Science PhD student at [Columbia University](https://www.columbia.edu/), advised by Prof. [Changxi Zheng](http://www.cs.columbia.edu/~cxz/). Her research interests mainly focus on computer graphics, e.g., physics-based animation and geometry processing. Before coming to Columbia, she received her MSc in Computer Science from [University of Toronto](https://www.utoronto.ca/) in 2021, advised by Prof. [David I.W. Levin](https://www.cs.toronto.edu/~diwlevin/), and her B.Eng. in Computer Science and Technology from [Zhejiang University](http://www.zju.edu.cn/english/) in 2019.

[Rundi Wu](https://chriswu1997.github.io) is a third-year PhD student at Columbia University, advised by Prof. [Changxi Zheng](http://www.cs.columbia.edu/~cxz/index.htm). Before joining Columbia, he obtained his B.S. degree in 2020 from Turing Class, Peking University. He was fortunate to work with Prof. [Baoquan Chen](http://cfcs.pku.edu.cn/baoquan/) during his undergraduate research. His current areas of interests include deep learning, computer graphics and computer vision, with special interest in data-driven 3D shape modeling. He enjoys learning and exploring, especially in the middle ground of deep learning and graphics. He's a recipient of the [Columbia Engineering School Dean Fellowship](https://www.cs.columbia.edu/2020/students-with-fellowships-2020/).
