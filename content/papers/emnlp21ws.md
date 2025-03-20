---
title: explanation few-shot NLP
---

## Investigating the Effect of Natural Language Explanations on Out-of-Distribution Generalization in Few-shot NLI

[Yangqiaoyu Zhou][rosa_zhou] and _Chenhao Tan_.            
In Workshop on Insights from Negative Results in NLP at EMNLP 2021.

**Abstract:**   
Although neural models have shown strong performance in datasets such as SNLI, they lack the ability to generalize out-of-distribution (OOD). In this work, we formulate a few-shot learning setup and examine the effects of natural language explanations on OOD generalization. We leverage the templates in the HANS dataset and construct templated natural language explanations for each template. Although generated explanations show competitive BLEU scores against groundtruth explanations, they fail to improve prediction performance. We further show that generated explanations often hallucinate information and miss key elements that indicate the label.

[[PDF](https://arxiv.org/pdf/2110.06223.pdf)]
[[Dataset](https://github.com/ChicagoHAI/hans-explanations)]


![generated exaplanations.](https://chenhaot.com/pubs/emnlp21ws.png)

@inproceedings{zhou+tan:21,   
&nbsp;&nbsp;&nbsp;&nbsp;
author = {Yangqiaoyu Zhou and Chenhao Tan},   
&nbsp;&nbsp;&nbsp;&nbsp;
title = {Investigating the Effect of Natural Language Explanations on Out-of-Distribution Generalization in Few-shot NLI},   
&nbsp;&nbsp;&nbsp;&nbsp;
year = {2021},   
&nbsp;&nbsp;&nbsp;&nbsp;
booktitle = {Proceedings of Workshop on Insights from Negative Results in NLP at EMNLP}   
}




[//]: <> (links for collaborators)
[rosa_zhou]: https://rosafish.github.io