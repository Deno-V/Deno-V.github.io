---
title: "Text-Guided Molecule Generation with Diffusion Language Model"
authors: "Haisong Gong, Qiang Liu, Shu Wu, Liang Wang"
collection: publications
permalink:  /publication/TGM
excerpt: "This paper presents TGM-DLM, the first diffusion language model designed for SMILE-based molecule generation, replacing traditional auto-regressive models. It highlights improved data efficiency, achieving superior results with a reduced amount of training data."
date: 2024-03-28
venue: "AAAI2024"
slidesurl: 
paperurl: 'https://ojs.aaai.org/index.php/AAAI/article/view/27761'
codeurl: 'https://github.com/Deno-V/tgm-dlm'
citation: "Gong, H., Liu, Q., Wu, S., & Wang, L. (2024). Text-Guided Molecule Generation with Diffusion Language Model. Proceedings of the AAAI Conference on Artificial Intelligence, 38(1), 109-117. "
figure: "/images/papertgm.png"
figurewidth: "80%"
---

### Authors
{{page.authors}}

### Abstract

Text-guided molecule generation is a task where molecules are generated to match specific textual descriptions. Recently, most existing SMILES-based molecule generation methods rely on an autoregressive architecture. In this work, we propose the Text-Guided Molecule Generation with Diffusion Language Model (TGM-DLM), a novel approach that leverages diffusion models to address the limitations of autoregressive methods. TGM-DLM updates token embeddings within the SMILES string collectively and iteratively, using a two-phase diffusion generation process. The first phase optimizes embeddings from random noise, guided by the text description, while the second phase corrects invalid SMILES strings to form valid molecular representations. We demonstrate that TGM-DLM outperforms MolT5-Base, an autoregressive model, without the need for additional data resources. Our findings underscore the remarkable effectiveness of TGM-DLM in generating coherent and precise molecules with specific properties, opening new avenues in drug discovery and related scientific domains. Code is at https://github.com/Deno-V/tgm-dlm.

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