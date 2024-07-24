---
title: "MGRQ: Post-Training Quantization For Vision Transformer With Mixed Granularity Reconstruction"
authors: "Lianwei Yang, Zhikai Li, Junrui Xiao, Haisong Gong, Qingyi Gu"
collection: publications
permalink:  /publication/MGRQ
excerpt: "This paper presents MGRA (Mixed Granularity Reconstruction Quantization) to improve post-training quantization for vision transformer."
date: 2024-06-13
venue: "ICIP2024"
slidesurl: 
paperurl: 'https://arxiv.org/abs/2406.09229'
codeurl: 
citation: 
figure:
figurewidth: 
---

### Authors
{{page.authors}}

### Abstract

Post-training quantization (PTQ) efficiently compresses vision models, but unfortunately, it accompanies a certain degree of accuracy degradation. Reconstruction methods aim to enhance model performance by narrowing the gap between the quantized model and the full-precision model, often yielding promising results. However, efforts to significantly improve the performance of PTQ through reconstruction in the Vision Transformer (ViT) have shown limited efficacy. In this paper, we conduct a thorough analysis of the reasons for this limited effectiveness and propose MGRQ (Mixed Granularity Reconstruction Quantization) as a solution to address this issue. Unlike previous reconstruction schemes, MGRQ introduces a mixed granularity reconstruction approach. Specifically, MGRQ enhances the performance of PTQ by introducing Extra-Block Global Supervision and Intra-Block Local Supervision, building upon Optimized Block-wise Reconstruction. Extra-Block Global Supervision considers the relationship between block outputs and the model's output, aiding block-wise reconstruction through global supervision. Meanwhile, Intra-Block Local Supervision reduces generalization errors by aligning the distribution of outputs at each layer within a block. Subsequently, MGRQ is further optimized for reconstruction through Mixed Granularity Loss Fusion. Extensive experiments conducted on various ViT models illustrate the effectiveness of MGRQ. Notably, MGRQ demonstrates robust performance in low-bit quantization, thereby enhancing the practicality of the quantized model.



---
{% if page.paperurl %}
- **Link to our paper**: [{{page.paperurl}}]({{page.paperurl}})
{% endif %}
{% if page.slidesurl %}
- **Link to our slides**: [{{page.slidesurl}}]({{page.slidesurl}})
{% endif %}
{% if page.codeurl %}
- **Link to our code**: [{{page.codeurl}}]({{page.codeurl}})
{% endif %}