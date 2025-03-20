---
title: human predictions
---

## On Human Predictions with Explanations and Predictions of Machine Learning Models: A Case Study on Deception Detection

[Vivian Lai][vivian_lai] and Chenhao Tan.    
In Proceedings of ACM FAT* Conference 2019.

**Abstract:**    
Humans are the final decision makers in critical tasks that involve ethical and legal concerns, ranging from recidivism prediction, to medical diagnosis, to fighting against fake news. Although machine learning models can sometimes achieve impressive performance in these tasks, these tasks are _not_ amenable to full automation. To realize the potential of machine learning for improving human decisions, it is important to understand how assistance from machine
learning models affects human performance and human agency.

In this paper, we use deception detection as a testbed and investigate how we can harness explanations and predictions of machine learning models to improve human performance while retaining human agency. We propose a spectrum between full human agency and full automation, and develop varying levels of machine assistance along the spectrum that gradually increase the influence of machine predictions. We find that without showing predicted labels, explanations alone slightly improve human performance in the end task. In comparison, human performance is greatly improved by showing predicted labels (>20% relative improvement) and can be further improved by explicitly suggesting strong machine performance. Interestingly, when predicted labels are shown,
explanations of machine predictions induce a similar level of accuracy as an explicit statement of strong machine performance. Our results demonstrate a tradeoff between human performance and human agency and show that explanations of machine predictions can moderate this tradeoff.

[[PDF][paper_link]] [[Slides](https://vivlai.github.io/slides/fat2019_lai.pdf)] [[Data & demo](https://deception.machineintheloop.com)] (Note that the demo may differ from the paper as we continutally develop our thinking on human + machine!)

__Important update__:
If you read the paper before 01/10/19, there is a new version of the paper.
We found a bug in our code and replicated the affected experiments.
If you do not want to re-read the paper, the main change is concerned with this sentence in the abstract:
<strike>"explanations alone do not statistically significantly improve human performance in the end task"</strike>
-> "explanations alone slightly improve human performance in the end task".

![spectrum.](https://chenhaot.com/pubs/human-predictions/spectrum.png)

@inproceedings{lai+tan:19,   
&nbsp;&nbsp;&nbsp;&nbsp;
author = {Vivian Lai and Chenhao Tan},   
&nbsp;&nbsp;&nbsp;&nbsp;
title = {On Human Predictions with Explanations and Predictions of Machine Learning Models: A Case Study on Deception Detection},   
&nbsp;&nbsp;&nbsp;&nbsp;
year = {2019},   
&nbsp;&nbsp;&nbsp;&nbsp;
booktitle = {Proceedings of FAT*}   
}



[paper_link]: /pubs/human-predictions/human-predictions.pdf
[slides_link]: /pubs/debate_quotes/www_slides.pdf
[supplementary_link]: /pubs/debate_quotes/supplementary.pdf
[data_link]: /data/debate-quotes/debate_quotes.zip
[readme_link]: /data/debate-quotes/README.txt
[//]: <> (links for collaborators)
[claire_cardie]: http://www.cs.cornell.edu/home/cardie/
[ed_chi]: http://www-users.cs.umn.edu/~echi/
[eunsol_choi]: http://homes.cs.washington.edu/~eunsol/home.html
[dallas_card]: http://www.cs.cmu.edu/~dcard/
[cristian_danescu_niculescu_mizil]: http://www.mpi-sws.org/~cristian/
[evgeniy_gabrilovich]: http://www.cs.technion.ac.il/~gabr/
[david_huffaker]: http://www.davehuffaker.com
[bobby_kleinberg]: http://www.cs.cornell.edu/~rdk
[jon_kleinberg]: http://www.cs.cornell.edu/home/kleinber
[gueorgi_kossinets]: https://sites.google.com/site/gkossinets/
[lillian_lee]: http://www.cs.cornell.edu/home/llee
[tao_lei]: http://people.csail.mit.edu/taolei/
[ping_li]: http://www.stat.cornell.edu/~li/
[bin_lu]: http://sites.google.com/site/lubin2010/
[michael_macy]: http://www.soc.cornell.edu/faculty/macy.html
[bo_pang]: https://sites.google.com/site/bopang42/
[hao_peng]: https://homes.cs.washington.edu/~hapeng/
[noah_smith]: http://homes.cs.washington.edu/~nasmith/
[daniel_romero]: http://www.dromero.org/
[alex_smola]: alex.smola.org
[jimeng_sun]: http://www.sunlab.org/
[jie_tang]: http://keg.cs.tsinghua.edu.cn/persons/johan_ugander
[johan_ugander]: http://people.cam.cornell.edu/~jugander/
[fei_wang]: http://sites.google.com/site/feiwang03/
[shaomei_wu]: http://www.cs.cornell.edu/~sw475/
[ming_zhou]: http://research.microsoft.com/en-us/people/mingzhou
[gs_profile]:http://scholar.google.com/citations?user=KGMaP18AAAAJ&hl=en
[nyt_link]: http://www.nytimes.com/2014/07/03/upshot/a-25-question-twitter-quiz-to-predict-retweets.html
[physics_arxiv_link]: https://medium.com/the-physics-arxiv-blog/1cfbe4f0f2e5
[washingtonpost_link]: http://www.washingtonpost.com/news/the-intersect/wp/2014/05/14/this-is-the-perfect-tweet-according-to-science/
[slashdot_link]: http://tech.slashdot.org/story/14/05/15/144236/data-mining-reveals-how-wording-influences-tweet-propagation
[engadget_link]: http://www.engadget.com/2014/05/15/cornell-google-researchers-identify-the-perfect-tweet/
[brandwatch_link]: http://www.brandwatch.com/2014/06/6-scientific-tips-improve-retweets/
[greekgeek_link]: http://greekgeek.mythphile.com/2014/05/scientific-study-discovers-what-gets-retweeted-more-often/
[dailytechwhip_link]: http://dailytechwhip.com/crafting-the-perfect-tweet-is-one-third-talent-two-thirds-science/
[techurls_link]: http://www.techurls.com/news/192825
[smobile_link]: http://www.smobie.com/en-gb/story/1231277/Crafting_the_perfect_tweet_is_one_third_talent_two_thirds_science
[dailydot_link]: http://www.dailydot.com/technology/twitter-data-minder-big-data-perfect-tweet/
[associationsnow_link]: http://associationsnow.com/2014/07/social-media-roundup-get-twitter-retweets/
[workattheyard_link]: http://workattheyard.com/25-question-twitter-quiz-predict-retweets/
[gapundit_link]: http://gapundit.com/2014/07/02/quiz-can-you-tell-what-makes-a-good-tweet-nytimes-com/
[smallbusiness_link]: https://smallbusiness.yahoo.com/advisor/6-scientific-tips-more-retweets-005612135.html
[newsana_link]: https://www.newsana.com/social-media/story/interactive-2014-07-01-upshot-twitter-quiz
[nuzzel_link]: http://nuzzel.com/story/07012014/nytimes/quiz_can_you_tell_what_makes_a_good_tweet
[jamesswalker_link]: http://jamesswalker.com/2014/05/16/doing-social-content-training-use-this-perfect-tweet-tool/
[columusceo_link]: http://www.columbusceo.com/content/stories/apexchange/2014/07/02/why-computers-wont-replace-you-just-yet.html (duplicates of nytimes articles)
[vivian_lai]: https://vivlai.github.io/
