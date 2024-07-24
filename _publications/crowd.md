---
title: "Navigating the Noisy Crowd: Finding Key Information for Claim Verification"
authors: "Haisong Gong, Huanhuan Ma, Qiang Liu, Shu Wu, Liang Wang"
collection: publications
permalink:  /publication/NavigatingCrowd
excerpt: "This paper introduces EACon where evidence abstraction and claim deconstruction are proposed to improve LLM's performance in claim verification."
date: 2024-07-17
venue: "arXiv"
slidesurl: 
paperurl: 'https://arxiv.org/abs/2407.12425'
codeurl:
citation:
figure: "/images/papercrowd.png"
figurewidth: "80%"
code:
---

### Authors
{{page.authors}}

### Abstract

Claim verification is a task that involves assessing the truthfulness of a given claim based on multiple evidence pieces. Using large language models (LLMs) for claim verification is a promising way. However, simply feeding all the evidence pieces to an LLM and asking if the claim is factual does not yield good results. The challenge lies in the noisy nature of both the evidence and the claim: evidence passages typically contain irrelevant information, with the key facts hidden within the context, while claims often convey multiple aspects simultaneously. To navigate this "noisy crowd" of information, we propose EACon (Evidence Abstraction and Claim Deconstruction), a framework designed to find key information within evidence and verify each aspect of a claim separately. EACon first finds keywords from the claim and employs fuzzy matching to select relevant keywords for each raw evidence piece. These keywords serve as a guide to extract and summarize critical information into abstracted evidence. Subsequently, EACon deconstructs the original claim into subclaims, which are then verified against both abstracted and raw evidence individually. We evaluate EACon using two open-source LLMs on two challenging datasets. Results demonstrate that EACon consistently and substantially improve LLMs' performance in claim verification. Code will be released once accepted.

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