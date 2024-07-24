---
title: "Heterogeneous Graph Reasoning for Fact Checking over Texts and Tables"
authors: "Haisong Gong, Weizhi Xu, Shu Wu, Qiang Liu,Liang Wang"
collection: publications
permalink:  /publication/HeterFC
excerpt: "This paper presents HeterFC, where word-level heterogenous is build for graph reasoning. An attention-based method is utilized to integrate information. Multitask loss function is proposed to account for potential inaccuracies in evidence retrieval."
date: 2024-03-25
venue: "AAAI2024"
slidesurl: 
paperurl: 'https://ojs.aaai.org/index.php/AAAI/article/view/27760'
codeurl: 'https://github.com/Deno-V/HeterFC'
citation: "Gong, H., Xu, W., Wu, S., Liu, Q., & Wang, L. (2024). Heterogeneous Graph Reasoning for Fact Checking over Texts and Tables. Proceedings of the AAAI Conference on Artificial Intelligence, 38(1), 100-108. "
figure: "/images/paperheterfc.png"
figurewidth: "80%"
---

### Authors
{{page.authors}}

### Abstract

Fact checking aims to predict claim veracity by reasoning over multiple evidence pieces. It usually involves evidence retrieval and veracity reasoning. In this paper, we focus on the latter, reasoning over unstructured text and structured table information. Previous works have primarily relied on fine-tuning pretrained language models or training homogeneous-graph-based models. Despite their effectiveness, we argue that they fail to explore the rich semantic information underlying the evidence with different structures. To address this, we propose a novel word-level Heterogeneous-graph-based model for Fact Checking over unstructured and structured information, namely HeterFC. Our approach leverages a heterogeneous evidence graph, with words as nodes and thoughtfully designed edges representing different evidence properties. We perform information propagation via a relational graph neural network, facilitating interactions between claims and evidence. An attention-based method is utilized to integrate information, combined with a language model for generating predictions. We introduce a multitask loss function to account for potential inaccuracies in evidence retrieval. Comprehensive experiments on the large fact checking dataset FEVEROUS demonstrate the effectiveness of HeterFC. Code is released at: https://github.com/Deno-V/HeterFC.

![MainFig]({{page.figure}})



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