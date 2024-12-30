---
title: "Breaking Event Rumor Detection via Stance-Separated Multi-Agent Debate"
authors: "Mingqing Zhang*, Haisong Gong*, Qiang Liu, Shu Wu, Liang Wang"
collection: publications
permalink:  /publication/S2MAD
excerpt: "This paper introduces S2MAD, which  investigate the use of multi-agent debate for rumor detection in social media within the context of breaking event scenarios."
date: 2024-12-01
venue: "arXiv"
slidesurl: 
paperurl: 'https://arxiv.org/abs/2412.04859'
codeurl:
citation:
figure: "/images/S2MAD.png"
figurewidth: "80%"
code:
---

### Authors
{{page.authors}}

### Abstract

The rapid spread of rumors on social media platforms during breaking events severely hinders the dissemination of the truth. Previous studies reveal that the lack of annotated resources hinders the direct detection of unforeseen breaking events not covered in yesterday’s news. Leveraging large language models (LLMs) for rumor detection holds significant promise. However, it is challenging for LLMs to provide comprehensive responses to complex or controversial issues due to limited diversity. In this work, we propose the Stance Separated Multi-Agent Debate (S2MAD) to address this issue. Specifically, we firstly introduce Stance Separation, categorizing comments as either supporting or opposing the original claim. Subsequently, claims are classified as subjective or objective, enabling agents to generate reasonable initial viewpoints with different prompt strategies for each type of claim. Debaters then follow specific instructions through multiple rounds of debate to reach a consensus. If a consensus is not reached, a judge agent evaluates the opinions and delivers a final verdict on the claim’s veracity. Extensive experiments conducted on two real-world datasets demonstrate that our proposed model outperforms state-of-the-art methods in terms of performance and effectively improves the performance of LLMs in breaking event rumor detection.

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