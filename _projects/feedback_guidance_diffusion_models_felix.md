---
layout: page
title: Feedback Guidance of Diffusion Models
description: by Félix Koulischer (University of Ghent)
img: assets/img/talks/feedback-guidance-diffusion-models.jpg
importance: 1
category: neural-nets

---



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/talks/feedback-guidance-diffusion-models.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<hr>



**Topic**:  [**Feedback Guidance of Diffusion Models**](https://arxiv.org/abs/2506.06085)

**Code**: [**Feedback Guidance of Diffusion Models**](https://github.com/FelixKoulischer/Feedback-Guidance-of-Diffusion-Models)

<hr>

**Abstract:**  


While Classifier-Free Guidance (CFG) has become standard for improving sample fidelity in conditional diffusion models, it can harm diversity and induce memorization by applying constant guidance regardless of whether a particular sample needs correction. We propose FeedBack Guidance (FBG), which uses a state-dependent coefficient to self-regulate guidance amounts based on need. Our approach is derived from first principles by assuming the learned conditional distribution is linearly corrupted by the unconditional distribution, contrasting with CFG's implicit multiplicative assumption. Our scheme relies on feedback of its own predictions about the conditional signal informativeness to adapt guidance dynamically during inference, challenging the view of guidance as a fixed hyperparameter. The approach is benchmarked on ImageNet512x512, where it significantly outperforms Classifier-Free Guidance and is competitive to Limited Interval Guidance (LIG) while benefitting from a strong mathematical framework. On Text-To-Image generation, we demonstrate that, as anticipated, our approach automatically applies higher guidance scales for complex prompts than for simpler ones and that it can be easily combined with existing guidance schemes such as CFG or LIG.


<hr>


|                     |                                                              |
| ------------------- | ------------------------------------------------------------ |
| **Topic**           | [**Feedback Guidance of Diffusion Models**](https://arxiv.org/abs/2506.06085) |
|                     |                                                              |
| **Slides**          | **TBA**                                                      |
|                     |                                                              |
| **When**            | **17.03.2026, 16:00 - 17:15 (CET)**                          |
|                     |                                                              |
| **Where**           | [**https://teams.microsoft.com/meet/33271954052497?p=o3o4HgS5iczuZgHLxy**](https://teams.microsoft.com/meet/33271954052497?p=o3o4HgS5iczuZgHLxy) |
|                     |                                                              |
| **Video Recording** | **TBA**                                                      |

<hr>

**Speaker(s):**

Félix Koulischer is an engineering physicist trained at Ghent University, where he discovered a passion for both mathematics and computational methods. These led him to pursue a PhD on diffusion models, inspired by their deep connections to thermodynamics and statistical mechanics. In particular, his research centers on diffusion guidance, the conditioning mechanism vital for their outstanding generative capabilities. Beyond his work in machine learning, he loves nature and being outdoors. This appreciation for the natural world draws his interests more and more toward molecular modalities and the intersection of physical systems and AI.

