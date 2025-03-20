---
title: neural topic model metadata
---

## Neural Models for Documents with Metadata

[Dallas Card][dallas_card], Chenhao Tan, and [Noah A. Smith][noah_smith].      
In Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics (ACL'2018).


**Abstract:**    
Most real-world document collections involve various types of metadata, such as author, source, and date, and yet the most commonly-used approaches to modeling text corpora ignore this information. While specialized models have been developed for particular applications, few are widely used in practice, as customization typically requires derivation of a custom inference algorithm. In this paper, we build on recent advances in variational inference methods and propose a general neural framework, based on topic models, to enable flexible incorporation of metadata and allow for rapid exploration of alternative models. Our approach achieves strong performance, with a manageable tradeoff between perplexity, coherence, and sparsity. Finally, we demonstrate the potential of our framework through an exploration of a corpus of articles about US immigration.

[[PDF][paper_link]][[Code][code_link]][[Supplementary material][supplement_link]]

![Immigration temporal dynamics.](https://chenhaot.com/pubs/neuraltm/example.png)

@inproceedings{card+etal:18,   
&nbsp;&nbsp;&nbsp;&nbsp;
author = {Dallas Card and Chenhao Tan and Noah A. Smith},   
&nbsp;&nbsp;&nbsp;&nbsp;
title = {Neural Models for Documents with Metadata},   
&nbsp;&nbsp;&nbsp;&nbsp;
year = {2018},   
&nbsp;&nbsp;&nbsp;&nbsp;
booktitle = {Proceedings of ACL}   
}


[paper_link]: /pubs/neuraltm/neural_metadata.pdf
[supplement_link]: /pubs/neuraltm/supplementary.pdf
[code_link]: https://github.com/dallascard/scholar
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
