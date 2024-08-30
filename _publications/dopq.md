---
title: "DopQ-ViT: Towards Distribution-Friendly and Outlier-Aware Post-Training Quantization for Vision Transformers"
authors: "Lianwei Yang, Haisong Gong, Qingyi Gu"
collection: publications
permalink:  /publication/DopQ
excerpt: "This paper introduces Distribution-Friendly and Outlier-Aware Post-training Quantization method for Vision Transformers, named DopQ-ViT. It includes Tan Quatizer (TanQ) and Median as the Optimal Scaling Factor (MOSF)."
date: 2024-07-16
venue: "arXiv"
slidesurl: 
paperurl: 'https://arxiv.org/abs/2408.03291'
codeurl:
citation:
figure: 
figurewidth: 
code:
---

### Authors
{{page.authors}}

### Abstract

Vision transformers (ViTs) have garnered significant attention for their performance in vision tasks, but the high computational cost and significant latency issues have hindered widespread adoption. Post-training quantization (PTQ), a promising method for model compression, still faces accuracy degradation challenges with ViTs. There are two reasons for this: the existing quantization paradigm does not fit the power-law distribution of post-Softmax activations well, and accuracy inevitably decreases after reparameterizing post-LayerNorm activations. We propose a Distribution-Friendly and Outlier-Aware Post-training Quantization method for Vision Transformers, named DopQ-ViT. DopQ-ViT analyzes the inefficiencies of current quantizers and introduces a distribution-friendly Tan Quantizer called TanQ. TanQ focuses more on values near 1, more accurately preserving the power-law distribution of post-Softmax activations, and achieves favorable results. Besides, during the reparameterization of post-LayerNorm activations from channel-wise to layer-wise quantization, the accuracy degradation is mainly due to the significant impact of outliers in the scaling factors. Therefore, DopQ-ViT proposes a method to select Median as the Optimal Scaling Factor, denoted as MOSF, which compensates for the influence of outliers and preserves the performance of the quantization model. DopQ-ViT has been extensively validated and significantly improves the performance of quantization models, especially in low-bit settings.

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