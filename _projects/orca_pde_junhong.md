---
layout: page
title: Cross-Modal Fine-Tuning
description: by Junhong Shen from Carnegie Mellon University
img: assets/img/talks/orca-pipeline.png
importance: 1
category: transfer-learning

---



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/talks/orca-pipeline.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<hr>

**Topic**:  [**Cross-Modal Fine-Tuning: Align then Refine**](https://arxiv.org/abs/2302.05738)


<hr>

**Abstract:**  

Fine-tuning large-scale pretrained models has led to tremendous progress in well-studied modalities such as Vision and NLP. However, similar gains have not been observed in many other modalities due to a lack of relevant pretrained models. In this work, we propose ORCA, a general cross-modal fine-tuning framework that extends the applicability of a single large-scale pretrained model to diverse modalities. ORCA adapts to a target task via an align-then-refine workflow: given the target input, ORCA first learns an embedding network that aligns the embedded feature distribution with the pretraining modality. The pretrained model is then fine-tuned on the embedded data to exploit the knowledge shared across modalities. Through extensive experiments, we show that ORCA obtains state-of-the-art results on 3 benchmarks containing over 60 datasets from 12 modalities, outperforming a wide range of hand-designed, AutoML, general-purpose, and task-specific methods. We highlight the importance of data alignment via a series of ablation studies and demonstrate ORCA's utility in data-limited regimes.

<hr>


|                     |                                                              |
| ------------------- | ------------------------------------------------------------ |
| **Topic**           | [**Cross-Modal Fine-Tuning: Align then Refine**](https://arxiv.org/abs/2302.05738) |
|                     |                                                              |
| **Slides**          | **TBA**                                                      |
|                     |                                                              |
| **When**            | **20.03.2023, 15:00 - 16:00 (CET) / 10:00 - 11:00 (EDT)**    |
|                     |                                                              |
| **Where**           | [**https://us02web.zoom.us/j/85216309906?pwd=cVB0SjNDR2tYOGhIT0xqaGZ2TzlKUT09**](https://us02web.zoom.us/j/85216309906?pwd=cVB0SjNDR2tYOGhIT0xqaGZ2TzlKUT09) |
|                     |                                                              |
| **Video Recording** | **TBA**                                                      |


<hr>

**Speaker:**

[**Junhong Shen**](https://sjunhongshen.github.io) is a second-year Ph.D. student in the [Machine Learning Department](https://www.ml.cmu.edu/) at CMU, advised by [Ameet Talwalkar](http://www.cs.cmu.edu/~atalwalk/). Her current research focuses on automated machine learning (AutoML), in particular building practical and easily accessible model development tools for diverse applications in real life.

She obtained her B.S. in Mathematics of Computation at UCLA, where she was fortunate to work with [Lin Yang](http://drlinyang.net/) on sample-efficient reinforcement learning. She also studied multi-agent RL and Theory of Mind, advised by [Song-Chun Zhu](http://www.stat.ucla.edu/~sczhu/) and [Ying Nian Wu](http://www.stat.ucla.edu/~ywu/).
