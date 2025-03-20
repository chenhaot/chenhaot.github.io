---
title: migrant churn
---

## To Stay or to Leave: Churn Prediction for Urban Migrants in the Initial Period

[Yang Yang](http://yangy.org/), Zongtao Liu, Chenhao Tan, Fei Wu, Yueting Zhuang, and Yafeng Li.    
In Proceedings of The Web Conference (WWW'2018).


**Abstract:**    
In China, 260 million people migrate to cities to realize their urban dreams. Despite that these migrants play an important role in the rapid urbanization process, many of them fail to settle down and eventually leave the city. The integration process of migrants thus raises an important issue for scholars and policymakers.

In this paper, we use Shanghai as an example to investigate migrants’ behavior in their first weeks and in particular, how their behavior relates to early departure. Our dataset consists of a one-month complete dataset of 698 telecommunication logs between 54 million users, plus a novel and publicly available housing price data for 18K real estates in Shanghai. We find that migrants who end up leaving early tend to neither develop diverse connections in their  rst weeks nor move around the city. Their active areas also have higher housing prices than that of staying migrants. We formulate a churn prediction problem to determine whether a migrant is going to leave based on her behavior in the  rst few days. The prediction performance improves as we include data from more days. Interestingly, when using the same features, the classifier trained from only the  rst few days is already as good as the classifier trained using full data, suggesting that the performance difference mainly lies in the di erence between features.

[[PDF][paper_link]][[Slides][slides_link]]

![Housing price distributions.](https://chenhaot.com/pubs/migrants/housing.png)

@inproceedings{yang+etal:18b,   
&nbsp;&nbsp;&nbsp;&nbsp;
author = {Yang Yang and Zongtao Liu and Chenhao Tan and Fei Wu and Yueting Zhuang and Yafeng Li},   
&nbsp;&nbsp;&nbsp;&nbsp;
title = {To Stay or to Leave: Churn Prediction for Urban Migrants in the Initial Period},   
&nbsp;&nbsp;&nbsp;&nbsp;
year = {2018},   
&nbsp;&nbsp;&nbsp;&nbsp;
booktitle = {Proceedings of WWW}   
}


[paper_link]: /pubs/migrants/migrant_churn.pdf
[slides_link]: /pubs/migrants/www_slides.pdf
[supplementary_link]: /pubs/idea_relations/supplementary.pdf
[acl_readme_link]: /data/idea-relations/acl_README.txt
[nips_readme_link]: /data/idea-relations/nips_README.txt
[nips_link]: /data/idea-relations/nips_release.zip
[acl_link]: /data/idea-relations/acl_release.zip
[demo_link]: /retweetedmore
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
