---
title: diverse counterfactual explanations
---

## Explaining Machine Learning Classifiers through Diverse Counterfactual Explanations

Ramaravind Kommiya Mothilal, [Amit Sharma][amit_sharma] and Chenhao Tan.    
In Proceedings of ACM FAT* Conference 2020.

**Abstract:**    
Post-hoc explanations of machine learning models are crucial for people to understand and act on algorithmic predictions. An intriguing class of explanations is through counterfactuals, hypothetical examples that show people how to obtain a different prediction. We posit that effective counterfactual explanations should satisfy two properties: feasibility of the counterfactual actions given user context and constraints, and diversity among the counterfactuals presented. To this end, we propose a framework for generating and evaluating a diverse set of counterfactual explanations based on determinantal point processes. To evaluate the actionability of counterfactuals, we provide metrics that enable comparison of counterfactual-based methods to other local explanation methods. We further address necessary tradeoffs and point to causal implications in optimizing for counterfactuals. Our experiments on four real-world datasets show that our framework can generate a set of counterfactuals that are diverse and well approximate local decision boundaries, outperforming prior approaches to generating diverse counterfactuals. We provide an implementation of the framework at [https://github.com/microsoft/DiCE](https://github.com/microsoft/DiCE).

[[PDF][paper_link]] [[Slides][slides_link]] [[Code](https://github.com/microsoft/DiCE)]

![tuotrial.](https://chenhaot.com/pubs/counterfactuals/example.png)

@inproceedings{mothilal+sharma+tan:20,   
&nbsp;&nbsp;&nbsp;&nbsp;
author = {Ramaravind K. Mothilal and Amit Sharma and Chenhao Tan},   
&nbsp;&nbsp;&nbsp;&nbsp;
title = {Explaining Machine Learning Classifiers through Diverse Counterfactual Explanations},   
&nbsp;&nbsp;&nbsp;&nbsp;
year = {2020},   
&nbsp;&nbsp;&nbsp;&nbsp;
booktitle = {Proceedings of FAT*}   
}



[paper_link]: https://arxiv.org/pdf/1905.07697.pdf
[slides_link]: /pubs/counterfactuals/slides_conf.pdf
[//]: <> (links for collaborators)
[amit_sharma]: http://www.amitsharma.in/
