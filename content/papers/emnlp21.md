---
title: decision focused summarization
---

## Decision-focused Summarization

[Chao-Chun Hsu][chaochun_hsu] and _Chenhao Tan_.         
In Proceedings of EMNLP 2021.

**Abstract:**   
Relevance in summarization is typically defined based on textual information alone, without incorporating insights about a particular decision. As a result, to support risk analysis of pancreatic cancer, summaries of medical notes may include irrelevant information such as a knee injury. We propose a novel problem, decision-focused summarization, where the goal is to summarize relevant information for a decision. We leverage a predictive model that makes the decision based on the full text to provide valuable insights on how a decision can be inferred from text. To build a summary, we then select representative sentences that lead to similar model decisions as using the full text while accounting for textual non-redundancy. To evaluate our method (DecSum), we build a testbed where the task is to summarize the first ten reviews of a restaurant in support of predicting its future rating on Yelp. DecSum substantially outperforms text-only summarization methods and model-based explanation methods in decision faithfulness and representativeness. We further demonstrate that DecSum is the only method that enables humans to outperform random chance in predicting which restaurant will be better rated in the future.

[[PDF](https://arxiv.org/pdf/2109.06896.pdf)]
[[Code](https://github.com/ChicagoHAI/decsum)]
[[Video](https://underline.io/lecture/37993-decision-focused-summarization)]


![typical summarization do not represent the decision.](https://chenhaot.com/pubs/emnlp21.png)

@inproceedings{hsu+tan:21,   
&nbsp;&nbsp;&nbsp;&nbsp;
author = {Chao-Chun Hsu and Chenhao Tan},   
&nbsp;&nbsp;&nbsp;&nbsp;
title = {Decision-focused Summarization},   
&nbsp;&nbsp;&nbsp;&nbsp;
year = {2021},   
&nbsp;&nbsp;&nbsp;&nbsp;
booktitle = {Proceedings of EMNLP}   
}




[//]: <> (links for collaborators)
[chaochun_hsu]: https://chaochunhsu.github.io
