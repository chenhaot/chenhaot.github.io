---
title: Wording for propagation
---

## The effect of wording on message propagation: Topic- and author-controlled natural experiments on Twitter   
Chenhao Tan, [Lillian Lee][lillian_lee], [Bo Pang][bo_pang]    
In Proceedings of the 52nd Annual Meeting of the Association for Computational Linguistics (ACL'2014)


**Abstract:**    
Consider a person trying to spread an important message on a social network. He/she can spend hours trying to craft the message.
Does it actually matter? While there has been extensive prior work looking into predicting popularity of social-media content,
the effect of wording per se has rarely been studied since it is often confounded with the popularity of the author and the topic.
To control for these confounding factors, we take advantage of the surprising fact that there are many
pairs of tweets containing the
_same_ url and written by the _same_ user but employing different
wording.
Given such pairs, we ask:
which version attracts more retweets?
This turns out to be a more difficult task than predicting popular topics.
Still, humans can answer this question better than chance (but far from
perfectly), and the computational methods we
develop
can do better than an average human as well as a strong competing method
trained on non-controlled data.

**Media coverage:**    
The New York Times: [A 25-Question Twitter Quiz to Predict Retweets][nyt_link]    
The Washington Post: [This is the perfect tweet, according to science][washingtonpost_link]     
The Physics arXiv Blog: [Data Mining Reveals How Wording Influences Tweet Propagation][physics_arxiv_link]     
engadget: [Crafting the perfect tweet is one-third talent, two-thirds science][engadget_link]     
The Daily Dot: [A data miner's guide to crafting the perfect tweet][dailydot_link]     
Yahoo! Small Business Advisor: [6 Scientific Tips to Get More Retweets][smallbusiness_link]      
associations now: [SOCIAL MEDIA ROUNDUP: THE BATTLE OF THE TWEETS][associationsnow_link]    
and [Slashdot][slashdot_link], [Brandwatch][brandwatch_link], [Daily Tech Whip][dailytechwhip_link] ...    

**Demo:**    
_We put a demo online where you can enter two tweets on the same topic and see which one our algorithm thinks will be retweeted more, or play a little quiz game to see how good you are in telling which tweet will be retweeted more._
[[Try it yourself!][demo_link]]

[[Data][data_link]([README][readme_link])]
[[PDF][paper_link]]
[[Slides][slide_link]]

@inproceedings{tan+lee+pang:14,   
&nbsp;&nbsp;&nbsp;&nbsp;
author = {Chenhao Tan and Lillian Lee and Bo Pang},   
&nbsp;&nbsp;&nbsp;&nbsp;
title = {The effect of wording on message propagation: Topic- and author-controlled natural experiments on Twitter},   
&nbsp;&nbsp;&nbsp;&nbsp;
year = {2014},   
&nbsp;&nbsp;&nbsp;&nbsp;
booktitle = {Proceedings of ACL}   
}


This work was supported in part by NSF grant IIS-0910664 and a Google Research Grant.
Any opinions, findings, and conclusions or recommendations expressed in this material are those of the author(s) and do not necessarily reflect the views of the National Science Foundation or other sponsors.

[paper_link]: /pubs/wording-effects-message-propagation.pdf
[slide_link]: /pubs/acl-wording.pdf
[readme_link]: /data/wording-effects/README.txt
[data_link]: /data/tweet_pair_data.zip
[demo_link]: /retweetedmore
[//]: <> (links for collaborators)
[claire_cardie]: http://www.cs.cornell.edu/home/cardie/
[ed_chi]: http://www-users.cs.umn.edu/~echi/
[eunsol_choi]: http://homes.cs.washington.edu/~eunsol/home.html
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
