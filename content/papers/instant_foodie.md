---
title: Instant Foodie
---

## Instant Foodie: Predicting Expert Ratings From Grassroots     
Chenhao Tan, [Ed H. Chi][ed_chi], [David Huffaker][david_huffaker], [Gueorgi Kossinets][gueorgi_kossinets], [Alexander J. Smola][alex_smola]      
In Proceedings of 22nd ACM International Conference on Information and Knowledge Management (CIKM'2013)

Consumer review sites and recommender systems typically rely on a large volume of user-contributed ratings, which makes rating acquisition an essential component in the design of such systems. User ratings are then summarized to provide an aggregate score representing a popular evaluation of an item. An inherent problem in such summarization is potential bias due to raters’ self-selection and heterogeneity in terms of experiences, tastes and rating scale interpretations. There are two major approaches to collecting ratings, which have different advantages and disadvantages. One is to allow a large number of volunteers to choose and rate items directly (a method employed by e.g. Yelp and Google Places). Alternatively, a panel of raters may be maintained and invited to rate a predefined set of items at regular intervals (such as in Zagat Survey). The latter approach arguably results in more consistent reviews and reduced selection bias, however, at the expense of much smaller coverage (fewer rated items).   
In this paper, we examine the two different approaches to collecting user ratings of restaurants and explore the question of whether it is possible to reconcile them. Specifically, we study the problem of inferring the more calibrated Zagat Survey ratings (which we dub “expert ratings”) from the user-contributed ratings (“grassroots”) in Google Places. To achieve this, we employ latent factor models and provide a probabilistic treatment of the ordinal ratings. We can predict Zagat Survey ratings accurately from ad hoc usergenerated ratings by employing joint optimization. Furthermore, the resulting model show that users become more discerning as they submit more ratings. We also describe an approach towards cross-city recommendations, answering questions such as “What is the equivalent of the Per Se1 restaurant in Chicago?”


[[Slides][cikm13_slides]][[PDF][cikm13_paper]]

@inproceedings{tan+etal:13,  
&nbsp;&nbsp;&nbsp;&nbsp;
  author = {Chenhao Tan and Ed H. Chi and David Huffaker and Gueorgi Kossinets and Alexander J. Smola},   
&nbsp;&nbsp;&nbsp;&nbsp;
  title = {Instant Foodie: Predicting Expert Ratings From Grassroots},   
&nbsp;&nbsp;&nbsp;&nbsp;
  year = {2013},   
&nbsp;&nbsp;&nbsp;&nbsp;
  booktitle = {Proceedings of CIKM}   
}

[cikm13_slides]: /pubs/cikm-instant-foodie.pdf
[cikm13_paper]: /pubs/instant-foodie.pdf
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
