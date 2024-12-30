---
title: "Leveraging Implicit Sentiments: Enhancing Reliability and Validity in Psychological Trait Evaluation of LLMs"
authors: "Huanhuan Ma, Haisong Gong, Xiaoyuan Yi, Xing Xie, Dongkuan Xu"
collection: publications
permalink:  /publication/CSI
excerpt: "We propose the Core Sentiment Inventory (CSI), a novel tool inspired by the Implicit Association Test, to evaluate sentiment tendencies in Large Language Models."
date: 2024-09-28
venue: "openreview"
slidesurl: 
paperurl: 'https://openreview.net/forum?id=zrdkQaf48Z'
codeurl:
citation:
figure: "/images/CSI.png"
figurewidth: "80%"
code:
---

### Authors
{{page.authors}}

### Abstract

Recent advancements in Large Language Models (LLMs) have led to their increasing integration into human life. Understanding their inherent characteristics, such as personalities, temperaments, and emotions, is essential for responsible AI development. However, current psychometric evaluations of LLMs, often derived from human psychological assessments, encounter significant limitations in terms of reliability and validity. Test results reveal that models frequently refuse to provide anthropomorphic responses and exhibit inconsistent scores across various scenarios. Moreover, human-derived theories may not accurately predict model behavior in practical real-world applications. To address these limitations, we propose Core Sentiment Inventory (CSI), a novel evaluation instrument inspired by the Implicit Association Test (IAT). CSI is built from the ground up with a significantly broader range of stimuli words than traditional assessments. CSI covers both English and Chinese to implicitly evaluate models’ sentiment tendencies, which allows for a much more comprehensive assessment. Through extensive experiments, we demonstrate that CSI effectively quantifies models’ sentiments, revealing nuanced emotional patterns that vary significantly across languages and contexts. CSI significantly improves reliability, yielding more consistent results and a reduced reluctance rate, and enhances predictive power by effectively capturing models’ emotional tendencies. These findings validate CSI as a robust and insightful tool for evaluating the psychological traits of LLMs, offering a more reliable alternative to traditional methods.

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