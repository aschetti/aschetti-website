---
title: Participating in the OSF Preregistration Challenge
authors:
- admin
date: "2019-07-23"
lastmod: "2019-07-23"
tags: ["OSF", "preregistration"]
categories: ["open science"]
summary: "My colleagues and I pre-registered a study via the OSF and participated in the Preregistration Challenge. Here are my thoughts."
featured: no
image:
  caption: ""
  focal_point: ""
  preview_only: yes
projects: []
---



## Table of Contents

- [Background](#background)
- [A Lucky Match](#a-lucky-match)
- [The Project](#the-project)
- [The Preregistration Challenge ](#the-preregistration-challenge)
    - [Preparation](#preparation)
    - [Process](#process)
    - [Prize](#prize)
- [Final thoughts](#final-thoughts)

# Background

During my academic career I have been following with great interest the development of open and transparent research practices. The first spark was the preprint of an article by [Wagenmakers et al.](http://www.ejwagenmakers.com/2011/Bem6.pdf) examining a paper on extra-sensory perception authored by [Daryl Bem](https://pdfs.semanticscholar.org/79ec/e4f787af713d82924e41d8c17ab130f4b22d.pdf). What I distilled from that criticism was that, in many fields of social sciences, questionable research practices -- combined with a mechanical, [ritualistic](https://library.mpib-berlin.mpg.de/ft/gg/GG_Mindless_2004.pdf) way of analyzing data -- can easily lead to the support of highly unlikely theories (in this case, humans can see the future[^1]).

More generally, this and other events kickstarted a series of initiatives aimed at mitigating the influence of such practices, including (but not limited to):

* [Open Science Badges](https://cos.io/our-services/open-science-badges/), encouraging **researchers** to share data, materials, and analysis protocols on public repositories;
* [TOP guidelines](https://cos.io/our-services/top-guidelines/), stimulating **journals** to flexibly adopt increased standards of transparency;
* dedicated [funding](https://www.nature.com/news/dutch-agency-launches-first-grants-programme-dedicated-to-replication-1.20287) and [article formats](https://www.psychologicalscience.org/observer/preregistered-direct-replications-a-new-article-type-in-psychological-science) supporting [direct replications](https://www.cambridge.org/core/services/aop-cambridge-core/content/view/2E3D8805BF34927A76B963C7BBE36AC7/S0140525X17001972a.pdf/making_replication_mainstream.pdf) of published studies;
* [preregistrations](https://osf.io/2dxu5/) and [registered reports](https://www.theguardian.com/science/head-quarters/2014/may/20/psychology-registration-revolution) of experiment plans before data collection.

Regarding the latter, one of the boldest initiatives aimed at stimulating researchers to preregister their experiments was the [Preregistration Challenge](https://cos.io/prereg/). In 2016, the Center for Open Science ([COS](https://cos.io/)) received a generous [$7.5-million gift](https://www.philanthropy.com/factfile/gifts/1?DonorDisplayName_cu=&Category=any&GiftRecipients_RecipOrgDateline_c=center+for+open+science&GiftRecipients_RecipStateFull=any&GiftDonors_SourceWealth_cu=&GiftDonors_aStateFull=any&GiftYear=2016) from the [Laura and John Arnold Foundation](https://www.arnoldfoundation.org/). One million was split it into one thousand \$1,000 prizes. To be eligible for this prize, researchers had to preregister a study on the Open Science Framework ([OSF](https://osf.io/)) following a specific [template](https://osf.io/prereg/?utm_source=cos_site&utm_medium=get_started_button&utm_campaign=PreReg_Challenge). If the resulting article was published in one of the partenered journals by Dec. 31st, 2018, the prize could be claimed. More details on the procedures can be found [here](https://cos.io/our-services/prereg-more-information/).

I simply could not pass on such a sweet opportunity[^2]. So I started looking around to see who, among my colleagues in the [CapLab](https://www.cap-lab.be/), would be interested in such an adventure.

# A Lucky Match

In November 2016 the CapLab welcomed [Sebastian Schindler](https://www.researchgate.net/profile/Sebastian_Schindler), a visiting post-doc from Universität Bielefeld[^3]. His contagious energy and enthusiasm, combined with his hard-working attitude, immediately made him a protagonist in our lab. He got involved in a series of projects with the very talented [Sam Verschooren](https://twitter.com/SamVerschooren)[^4] and pitched several original ideas, one of which became the project we preregistered[^5].

# The Project

Emotional information is particularly salient for the human brain. Many researchers have reported that processing emotional stimuli, like pictures of babies or curse words, is associated with stronger electrical activity recorded on the scalp (electroencephalography, _EEG_). In particular, several event-related potential (_ERP_) components -- e.g., [_P1_](https://www.ncbi.nlm.nih.gov/pubmed/12459215), [_N1_](https://www.ncbi.nlm.nih.gov/pubmed/21058848), [_EPN_](https://www.ncbi.nlm.nih.gov/pubmed/16407776), and [_LPP_](https://www.ncbi.nlm.nih.gov/pubmed/10731776) --, are larger in amplitude for emotional stimuli compared to neutral controls. This amplitude increase is typically explained as enhanced attention for emotion-laden material. However, similar amplitude modulations can be observed when non-emotional stimuli are changed in [_size_](https://www.ncbi.nlm.nih.gov/pubmed/15261860) (bigger size associated with larger amplitude) or [_contrast_](https://www.ncbi.nlm.nih.gov/pubmed/7580401) relative to background (higher contrast associated with larger amplitude).

So, we thought it would be interesting to investigate whether emotion-dependent ERP amplitude amplification during visual word processing is **independently** or **interactively** related to the processing of low-level features (in our case, font size and contrast).

Discussing the results is not the aim of this post. If you are curious to know more, you can find the paper [here](https://www.nature.com/articles/s41598-018-30701-5). Feel free to leave your post-publication peer-review in the comment section below!

# The Preregistration Challenge 

## Preparation

We piloted a few versions of the paradigm, to make sure that our experimental manipulations were clear to participants and elicited reliable ERP components. We fought the temptation to interpret any differences associated with our factors of interest, because pilot work typically overestimates the observed effect size (Uri Simonhson discusses the issue in [this talk](https://www.youtube.com/watch?v=HzE9HtOX_sE&list=PLVsU5p9lr8QF6Ut-wujw2gYIfZlP0du3z&index=6)). Meanwhile, we wrote down a text containing a review of relevant literature and the aims of the study, similarly to the _Introduction_ section of an academic manuscript. As soon as the pilot testing was done, we added a very detailed _Methods_ section with a description of the stimulation protocol. Since we also collected some data, we could develop [preprocessing and analysis scripts](https://osf.io/aev6j/) (in _Matlab_ and _R_) to verify whether our pipeline could be computationally feasible (and catch possible bugs). Having prepared such a detailed document made it very easy to fill out the preregistration form on the OSF: all the requested information was, in some form, already present. 

## Process

We sent the final protocol for approval on April 23rd, 2017. The next day, Alex DeHaven from COS sent us an email requesting some minor clarifications related to the planned statistical analysis, i.e., [Bayes factors](https://richarddmorey.github.io/BayesFactor/): we were asked to specify whether the priors used for paired comparisons were the same as used in the ANOVAs. While COS was not responsible for the **content** of any preregistration, it was nice to see that a knowledgeable reviewer could spot this missing information. 

We then had a series of technical issues related to a corrupted file that was solved at the very last minute, the day before we were scheduled to test our first official participant. Luckily everything went well, thanks to Alex's relentlessness and Sebastian's commitment (I was at a [conference](https://osf.io/wdaj4/) and could only send good vibes and imaginary pretzels 🥨 ): we registered our protocol on April 25th and started data collection on April 26th at 8:30. The completed preregistration protocol can be found [here](https://osf.io/uf9gh).

After collecting the data, the EEG preprocessing, ERP amplitude extraction, and statistical analyses were performed quite quickly: we already had a good pipeline based on our pilots and only refined the code to make it more readable. However, we noticed something we did not anticipate while crafting the preregistration protocol: not only the amplitude, but also the latency of some ERP components was modulated by our experimental factors. So, we decided to run the same analyses planned for the mean amplitude also for the amplitude and latency of component _peaks_. These results were added in the _Supplementary Materials_ and briefly described in an additional _Exploratory Analyses_ section in the main text.

We uploaded the [preprint](https://psyarxiv.com/2sv3t/) of the manuscript on _PsyArXiv_ on May 1st, 2018 -- approximately one year after uploading the preregistration protocol -- and, a few days later, submitted it to **Scientific Reports**, one of the many [eligible journals](https://cos.io/our-services/prereg-more-information/). After a thorough round of review, the paper was accepted and published online on August 15th, 2018.

## Prize

On August 21st, Alex DeHaven contacted us asking if we wanted our article to be eligible for the \$1,000 prize. After the COS reviewing team ensured that the published paper followed the preregistered plan, we filled out some tax documents and received the funds by the end of the year. Yes, it was that smooth and simple.

# Final thoughts

Undoubtedly, this has been one of the most rewarding experiences of my academic career. 

Having to craft the preregistration document forced us to think very carefully about the main theoretical predictions and how to tackle them with appropriate methodology, instead of having (relatively) vague research questions to be tested with omnibus statistical tests. We could also note unforeseen events and report additional exploratory analyses, contrary to the [opinion](https://www.timeshighereducation.com/comment/opinion/pre-registration-would-put-science-in-chains/2005954.article) that preregistration may limit data exploration and the reporting of unexpected results. It was also interesting to consciously appreciate how many choices we typically make when preprocessing EEG data, e.g., by selecting specific filtering parameters or artifact detection/correction/rejection algorithms. Collecting pilot data greatly helped make such choices early on in the process. Finally, from a pragmatic perspective, this has been the fastest project I have ever worked on: only one year from data collection to publication. Sebastian's commitment surely propelled this project, and he deserves all the credit. However, having a well-thought plan definitely increased our efficiency because our degrees of freedom were necessarily limited: we could not try out different ways to extract amplitude values of the ERP components, or various statistical models to chase significance. 

My positive experience leads me to strongly encourage researchers working with human electrophysiological data to preregister their studies. I would recommend starting with one simple study, with relatively straightforward predictions and simple analyses, in order to better appreciate how many degrees of freedom could already be exploited in such an easy scenario. With time, preregistration can become another procedure in the research workflow, a tool to increase the reliability of the scientific process... just like learning a new programming language or statistical technique[^6].

It is a humbling experience that turned me into a better researcher, and I hope you will try as well.

[^1]: Well, not necessarily all humans... mainly university students. And they can "sense" whether one image behind a curtain shows an erotic scene. With an accuracy of ~53% (50% being chance level). ... *crickets in the background* ... I guess they won't be able to use their superhuman abilities at the casino, after all.

[^2]: ![Scrooge](https://media.giphy.com/media/13yNFN1TlNCjC0/giphy.gif)

[^3]: Sebastian is now working at [Westfälische Wilhelms-Universität Münster](https://www.medizin.uni-muenster.de/medpsych/institut/team/sebastian-schindler/). He is a wonderful human being and I am honored to be able to call him a friend 💓

[^4]: His most recent paper is great! Preprint can be found [here](https://psyarxiv.com/swc3q/).

[^5]: Also, I want to acknowledge the constant patience and support of [Gilles Pourtois](https://www.researchgate.net/profile/Gilles_Pourtois), with whom I have collaborated for more than 7 years.

[^6]: Echoing [Brian Nosek](https://twitter.com/BrianNosek/status/1132239169772761089), "preregistration is a skill and not a bureaucratic process".
