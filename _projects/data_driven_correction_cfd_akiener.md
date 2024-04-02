---
layout: page
title: Data-driven Correction of Coarse Grid CFD Simulations
description: by Anna Kiener (German Aerospace Center (DLR))
img: assets/img/talks/data-driven-correction-cgrid-cfd-anna.jpg
importance: 1
category: pde

---



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/talks/data-driven-correction-cgrid-cfd-anna.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<hr>



**Topic**:  [**Data-driven Correction of Coarse Grid CFD Simulations**](https://www.sciencedirect.com/science/article/pii/S0045793023001962)



<hr>

**Abstract:**  

Computational fluid dynamics is a cornerstone of the modern aerospace industry, providing important insights through aerodynamic analysis while reducing the need for expensive experiments and tests. A consistent spatial discretization on so-called grids approximates the analytical solution of the partial differential equation with increasing number of discrete points. But computing a rigorous amount of CFD simulations on fine grids can be a daunting task due to the high computational cost involved. Thus, it is of interest to find methods which generate accurate results while keeping computational costs low. This work proofs that machine learning as a post-processing tool is capable of improving the accuracy of coarse grid simulations. The results show that three machine learning models with varying complexity, namely random forest, neural network, and graph neural network, are capable of finding patterns in coarse grid simulations. These patterns are used for a vertex-wise prediction of the discretization error to approximate the field variables of interest of the corresponding fine grid simulation mapped onto the coarse grid. Initial training and testing is performed on the two dimensional RAE2822 airfoil leading to corrected flow fields, improved surface integrals and coefficients, even when shocks are present. Additional tests are performed on the RAE5212 airfoil, showing the generalization limits of the trained models. Finally, the training and prediction is showcased on a three dimensional geometry. The proposed method promises to reduce computational expenses while increasing the accuracy of the coarse grid results which works locally, e.g. it corrects the error for each vertex individually and is therefore not restricted by the number of grid points. The presented results obtained by the machine learning models during post-processing are a promising baseline for more integrated developments, where the models will interact in a dynamic fashion with the flow solver to further improve coarse grid simulations.


<hr>


|                     |                                                              |
| ------------------- | ------------------------------------------------------------ |
| **Topic**           | [**Data-driven Correction of Coarse Grid CFD Simulations**](https://www.sciencedirect.com/science/article/pii/S0045793023001962) |
|                     |                                                              |
| **Slides**          | **TBA**                                                      |
|                     |                                                              |
| **When**            | **22.04.2024, 15:00 - 16:15 (CEST) / 10:00 - 11:15 (EST) / 08:00 - 09:15 (MST)** |
|                     |                                                              |
| **Where**           | [**https://us02web.zoom.us/j/85216309906?pwd=cVB0SjNDR2tYOGhIT0xqaGZ2TzlKUT09**](https://us02web.zoom.us/j/85216309906?pwd=cVB0SjNDR2tYOGhIT0xqaGZ2TzlKUT09) |
|                     |                                                              |
| **Video Recording** | **TBA**                                                      |

<hr>
**Speaker(s):**

Anna Kiener is a PhD candidate at the Aerodynamics and Flow Technology Institute of the German Aerospace Center (DLR). Prior to that she completed her Master's in Mechanical Engineering from Hochschule Luzern. Her research interests include machine learning, turbulence modeling, and applying ML for solving partial differential equations.