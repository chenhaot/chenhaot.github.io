---
title: unifying explanations
---

## Towards Unifying Feature Attribution and Counterfactual Explanations: Different Means to the Same End

[Ramaravind Kommiya Mothilal][ram_mothilal], [Divyat Mahajan][divyat_mahajan], _Chenhao Tan_ and [Amit Sharma](amit_sharma).           
In Proceedings of the Fourth AAAI/ACM conference on Artificial Intelligence, Ethics, and Society (AIES'2021); also presented at the [Reponsible AI workshop](https://sites.google.com/view/rai-workshop/home?authuser=0) at ICLR.

**Abstract:**   
Feature attributions and counterfactual explanations are popular approaches to explain a ML model. The former assigns an impor- tance score to each input feature, while the latter provides input examples with minimal changes to alter the model’s predictions. To unify these approaches, we provide an interpretation based on the actual causality framework and present two key results in terms of their use. First, we present a method to generate feature attribution explanations from a set of counterfactual examples. These feature attributions convey how important a feature is to changing the classification outcome of a model, especially on whether a subset of features is necessary and/or sufficient for that change, which attribution-based methods are unable to provide. Second, we show how counterfactual examples can be used to evaluate the goodness of an attribution-based explanation in terms of its necessity and sufficiency. As a result, we highlight the complementarity of these two approaches. Our evaluation on three benchmark datasets — Adult-Income, LendingClub, and German-Credit — confirms the complementarity. Feature attribution methods like LIME and SHAP and counterfactual explanation methods like Wachter et al. and DiCE often do not agree on feature importance rankings. In addi- tion, by restricting the features that can be modified for generating counterfactual examples, we find that the top-k features from LIME or SHAP are often neither necessary nor sufficient explanations of a model’s prediction. Finally, we present a case study of different explanation methods on a real-world hospital triage problem.

[[PDF](https://arxiv.org/pdf/2011.04917.pdf)]

![complementarity.](https://chenhaot.com/pubs/explanations/complementarity.png)

@inproceedings{mothilal+etal:21,   
&nbsp;&nbsp;&nbsp;&nbsp;
author = {Ramaravind Kommiya Mothilal and Divyat Mahajan and Chenhao Tan and Amit Sharma},   
&nbsp;&nbsp;&nbsp;&nbsp;
title = {Towards Unifying Feature Attribution and Counterfactual Explanations: Different Means to the Same End},   
&nbsp;&nbsp;&nbsp;&nbsp;
year = {2021},   
&nbsp;&nbsp;&nbsp;&nbsp;
booktitle = {Proceedings of AIES}   
}




[slides_link]: /pubs/debate_quotes/www_slides.pdf
[//]: <> (links for collaborators)
[amit_sharma]: http://www.amitsharma.in/
[divyat_mahajan]: http://divy.at/
[ram_mothilal]: https://raam93.github.io/