---
title: learning from rationales
---

## What to Learn, and How: Toward Effective Learning from Rationales

[Samuel Carton][sam_carton], [Surya Kanoria][surya_kanoria], and _Chenhao Tan_.      
Findings of ACL 2022.

**Abstract:**   
Learning from rationales seeks to augment model prediction accuracy using human-annotated rationales (i.e. subsets of input tokens) that justify their chosen labels, often in the form of intermediate or multitask supervision. While intuitive, this idea has proven elusive in practice. We make two observations about human rationales via empirical analyses: 1) maximizing rationale supervision accuracy is not necessarily the optimal objective for improving model accuracy; 2) human rationales vary in whether they provide sufficient information for the model to exploit for prediction. Building on these insights, we propose several novel loss functions and learning strategies, and evaluate their effectiveness on three datasets with human rationales. Our results demonstrate consistent improvements over baselines in both label and rationale accuracy, including a 3% accuracy improvement on MultiRC. Our work highlights the importance of understanding properties of human explanations and exploiting them accordingly in model training.

[[PDF](https://arxiv.org/pdf/2112.00071.pdf)]
[[Code](https://github.com/ChicagoHAI/learning-from-rationales)]


![recall matters more than precision.](https://chenhaot.com/pubs/acl22.png)

@inproceedings{carton+kanoria+tan:21,   
&nbsp;&nbsp;&nbsp;&nbsp;
author = {Samuel Carton and Surya Kanoria and Chenhao Tan},   
&nbsp;&nbsp;&nbsp;&nbsp;
title = {What to Learn, and How: Toward Effective Learning from Rationales},   
&nbsp;&nbsp;&nbsp;&nbsp;
year = {2022},   
&nbsp;&nbsp;&nbsp;&nbsp;
booktitle = {Findings of ACL}   
}




[//]: <> (links for collaborators)
[sam_carton]: https://shcarton.github.io/
[surya_kanoria]: https://surya-kanoria.github.io