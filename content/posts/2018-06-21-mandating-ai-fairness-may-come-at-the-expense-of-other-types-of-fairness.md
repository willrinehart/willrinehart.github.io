---
title: Mandating AI Fairness May Come At The Expense Of Other Types of Fairness
author: Will
type: post
date: 2018-06-21T18:12:25+00:00
url: /2018/mandating-ai-fairness-may-come-at-the-expense-of-other-types-of-fairness/
categories:
  - 'Antitrust &amp; Competition Policy'
tags:
  - AI
  - algorithm
  - algorithmic
  - artificial intelligence
  - risk

---
Two years ago, ProPublica [initiated a conversation][1] over the use of risk assessment algorithms when they concluded that a widely used “score proved remarkably unreliable in forecasting violent crime” in Florida. Their examination of the racial disparities in scoring has been cited countless times, often as a proxy for the power of automation and algorithms in daily life. Indeed, as the authors concluded, these scores are “part of a part of a larger examination of the powerful, largely hidden effect of algorithms in American life.”  
As this examination continues, two precepts are worth keeping in mind. First, the social significance of algorithms needs to be considered, not just their internal model significance. While the accuracy of algorithms are important, more emphasis should be placed on how they are used within institutional settings. And second, fairness is not a single idea. Mandates for certain kinds of fairness could come at the expense of others forms of fairness. As always, policymakers need to be cognizant of the trade offs.  <!--more-->

  
_Statistical significance versus social significance_  
The ProPublica study arrived at a critical junction in the conversation over algorithms. In the tech space, [TensorFlow][2], Google’s artificial intelligence (AI) engine, had been released in 2015, sparking interest in algorithms and the application of AI for commercial applications. At the same time, in the political arena, sentencing reform was gaining steam. Senators Rand Paul and Cory Booker helped bring wider attention to the need for reforms to the criminal justice system through their efforts in passing [the REDEEM Act][3]. Indeed, when the Koch Brothers’ political network announced more than $5 million in spending for criminal justice reform, the [Washington Post noted][4] that it underscored “prison and sentencing reform&#8217;s unique position as one of the nation&#8217;s most widely discussed policy proposals as well as one with some of the most broad political backing.”  
Model selection is a critical component of any study, so it is no wonder that criticism of risk assessment algorithms have focused on this aspect of the process. Error bars might reflect precision, but they tell us little about a model’s applicability. More importantly however, the implementation isn’t frictionless. People have to use them to make decisions. Algorithms must be integrated within a set of processes that involve the messiness of human relations. Because of the variety of institutional settings, there is sure to be significant variability in how they come to be used. The impact of real decision-making processes isn’t constrained only by the accuracy of the models, but also the purposes to which they are applied.  
In other words, the social significance of these models, how they come to be used in practice, is a pertinent question for policy makers just the same as their statistical significance is.  
Angèle Christin, a professor at Stanford who studies these topics, made the issue abundantly clear when she [noted][5],

<p style="padding-left: 30px;">
  Yet it is unclear whether these risk scores always have the meaningful effect on criminal proceedings that their designers intended. During my observations, I realized that risk scores were often ignored. The scores were printed out and added to the heavy paper files about defendants, but prosecutors, attorneys, and judges never discussed them. The scores were not part of the plea bargaining and negotiation process. In fact, <b>most of judges and prosecutors told me that they did not trust the risk scores at all</b>. Why should they follow the recommendations of a model built by a for-profit company that they knew nothing about, using data they didn’t control? They didn’t see the point. <b>For better or worse, they trusted their own expertise and experience instead</b>. (emphasis added)
</p>

Christin’s on the ground experience urges scholars to consider how these algorithms have come to be implemented in practice. As she points out, institutions engage in various kinds rituals to appear modern, chief among them being [the acquisition of new technological tools][6]. Changing practices within workplaces is a much more difficult task than reformers would like to imagine. Instead, a typical reaction by those who have long worked within a system is to  manipulate the tool to look compliant.  
The implementation of pretrial risk assessment instruments highlights the potential variability when algorithms are deployed. These instruments can help guide judges when decisions are made about what is going to happen to a defendant before a trial. Will the defendant be put on bail and what will be the cost? The most popular of these instruments is known as the Public Safety Assessment or simply the PSA, which was developed by the Laura and John Arnold Foundation and has been adopted in over 30 jurisdictions in the last five years.  
The adoption of the PSA across regions helps to demonstrate just how disparate implementation can be. In New Jersey, the adoption of the PSA seems to have correlated with a [dramatic decline][7] in the pretrial detention rate. In Lucas County, Ohio [the pretrial detention][8] rate increased after the PSA was put into place. In Chicago, judges seem to be [simply ignoring][9] the PSA. Indeed, there appears to be [little agreement][10] on how well the PSA’s high-risk classification corresponds to reality, as re-arrest can be as low as 10 percent or as high as 42 percent, depending on how the PSA is integrated in a region.  
And in the most [comprehensive study of its kind][11], George Mason University law professor Megan Stevenson looked at Kentucky after it implemented the PSA and found significant changes in bail-setting practices, but only a small increase in pretrial release. Over time these changes eroded as judges returned to their previous habits. If this tendency to revert back to the mean is widespread, then why even implement these pre-trial risk instruments?  
Although it was focused on pretrial risk assessments, Stevenson’s call for a broader understanding of these tools applies to the entirety of algorithm research:

<p style="padding-left: 30px;">
  Risk assessment in practice is different from risk assessment in the abstract, and its impacts depend on context and details of implementation. If indeed risk assessment is capable of producing large benefits, it will take research and experimentation to learn how to achieve them. Such a process would be evidence-based criminal justice at its best: not a flocking towards methods that bear the glossy veneer of science, but a careful and iterative evaluation of what works and what does not.
</p>

Algorithms are tools. While it is important to understand how well calibrated the tool is, researchers needs to be focused on how that tool impacts real people working with and within institutions with embedded cultural and historic practices.  
_Trade offs in fairness determinations_  
Julia Angwin and her team at ProPublica helped to spark a new interest in algorithmic decision-making when [they dove deeper][1] into a commonly used post trial sentencing tool known as COMPAS. Instead of predicting behavior before a trial takes place, COMPAS purports to predict a defendant’s risk of committing another crime in the sentencing phase after a defendant has been found guilty. As they discovered, the risk system was biased against African-American defendants, who were more likely to be incorrectly labeled as higher-risk than they actually were. At the same time, white defendants were labeled as lower-risk than they was actually the case.  
Superficially, that seems like  a simple problem to solve. Just add features to the algorithm that consider race and rerun the tool. If only the algorithm payed attention to this bias, the outcome could be corrected. Or so goes the thinking.  
But let’s take a step back and consider really what these tools represent. The task of the COMPAS tool is to estimate the degree to which people possess a likeliness for future risk. In this sense, the algorithm aims for _calibration_, one of at least three distinct ways we might understand fairness. Aiming for fairness through calibration means that people were correctly identified as having some probability of committing an act. Indeed, as subsequent research has found, the number of people who committed crimes were correctly distributed within each group. In other words, the algorithm did correctly identify a set of people as having a probability of committing a crime.  
Angwin’s criticism is of another kind, as Jon Kleinberg, Sendhil Mullainathan, and Manish Raghavan [explain][12] in “Inherent Trade-Offs in the Fair Determination of Risk Scores.” The kind of fairness that Angwin aligns with might be understand as a _balance for the positive class_. To violate this kind of fairness notion, people would be later identified as being part of the class, yet they were predicted initially as having a lower probability by the algorithm. For example, as the ProPublica study found, white defendants that did commit crimes in the future were assigned lower risk scores. This would be a violation of balance for the positive class.  
Similarly, _balance for a negative class_ is the negative correlate. To violate this kind of fairness notion, people that would be later identified as not being part of the class would be predicted initially as having a higher probability of being part of it by the algorithm. Both of these conditions try to capture the idea that groups should have equal false negative and false positive rates.  
After formalizing these three conditions for fairness, Kleinberg, Mullainathan, and Raghavan proved that it isn’t possible to satisfy all constraints simultaneously except in highly constrained special cases. These results hold regardless of how the risk assignment is computed, since “it is simply a fact about risk estimates when the base rates differ between two groups.”  
What this means is that some views of fairness might simply be incompatible with each other. Balancing for one kind of notion of fairness is likely to come at the expense of another.  
This trade off is really a subclass of a larger problem that is of central focus in data science, econometrics, and statistics. [As Pedro Domingos noted][13]:

<p style="padding-left: 30px;">
  You should be skeptical of claims that a particular technique “solves” the overfitting problem. It’s easy to avoid overfitting (variance) by falling into the opposite error of underfitting (bias). Simultaneously avoiding both requires learning a perfect classifier, and short of knowing it in advance there is no single technique that will always do best (no free lunch).
</p>

Internalizing these lessons about fairness requires a shift in framing. For those working in the AI field, actively deploying algorithms, and especially for policy makers, fairness mandates will likely create trade offs. If most algorithms cannot achieve multiple notions of fairness simultaneously, then every decision to balance for class attributes is likely to take away from efficiency elsewhere. This isn’t to say that we shouldn’t strive to optimize fairness. Rather, it is simply important to recognize that mandating of one type of fairness may necessarily come at the expense of a different type of fairness.  
Understanding the internal logic of risk assessment tools is not the end of the conversation. Without data of how they are used, it could be that these algorithm entrench bias, uproot it, or have ambiguous effects. To have an honest conversation, we need to understand how they nudge decisions in the real world.

 [1]: https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing
 [2]: https://www.tensorflow.org/about/
 [3]: http://thehill.com/blogs/pundits-blog/crime/346474-glimmer-of-hope-in-bipartisan-criminal-justice-reform-effort
 [4]: https://www.washingtonpost.com/news/post-politics/wp/2015/02/19/the-bipartisan-push-for-criminal-justice-gets-a-koch-funded-boost/?utm_term=.216ff51e7609
 [5]: https://points.datasociety.net/models-in-practice-19e68b18c340
 [6]: http://www.jstor.org/stable/2778293?seq=1#page_scan_tab_contents
 [7]: https://www.nbcnews.com/specials/bail-reform
 [8]: https://thecrimereport.org/wp-content/uploads/2017/08/Lucas-County-court-filing.pdf
 [9]: https://chicago.suntimes.com/news/cook-county-judges-not-following-bail-recommendations-study-find/
 [10]: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2826600
 [11]: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3016088
 [12]: https://arxiv.org/pdf/1609.05807.pdf
 [13]: https://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf