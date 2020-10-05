---
title: The Kids Are Going To Be Alright
author: Will
type: post
date: 2019-01-17T19:24:02+00:00
url: /2019/the-kids-are-going-to-be-alright/
classic-editor-remember:
  - classic-editor
thesis_thumb_width:
  - 66
thesis_thumb_height:
  - 66
categories:
  - Miscellaneous
  - Moral Panics
tags:
  - COPPA
  - immersive tech
  - user empowerment

---
Catchy headlines like “[Heavy Social Media Use Linked With Mental Health Issues In Teens][1]” and “[Have Smartphones Destroyed a Generation?][2]” advance a common trope of generational decline. But a [new paper in Nature][3] uses a new and rigorous analytical method to understand the relationship between adolescent well-being and digital technology, finding a “negative but small [link], explaining at most 0.4% of the variation in well-being.”

What really sets apart the new paper from Amy Orben and Andy Przybylski is that it aims to capture a more complete picture of how variables interact. The problem that Orden and Przybylski tackle is endemic one in social science. Sussing out the causal relationship between two variables will always be confounded by other related variables in the dataset. So how do you choose the right combination of variables to test?

[An analytical approach][4] first developed by Simonsohn, Simmons and Nelson outlines a method for solving this problem. As Orben and Przybylski [wrote][5], “Instead of reporting a handful of analyses in their paper, [researchers] report all results of all theoretically defensible analyses.” The result is a range of possible coefficients, which can then be plotted along a curve, a specification curve. Below is the specification curve from one of the datasets that Orben and Przybylski analyzed.<figure class="wp-block-image">

![][6] </figure> 

Amy Orben and Andrew Przybylski [explain][7] why this method is important to policy makers who are interested in the tech use question:

<p style="padding-left: 40px;">
  Although statistical significance is often used as an indicator that findings are practically significant, the paper moves beyond this surrogate to put its findings in a real-world context.  In one dataset, for example, the negative effect of wearing glasses on adolescent well-being is significantly higher than that of social media use. Yet policymakers are currently not contemplating pumping billions into interventions that aim to decrease the use of glasses.
</p>

Truthfully this is the first time I have encountered specification curve analysis and am quite impressed with its power. For more details, check out the [OSF page][8], [the writeup in Nature][7], and [the full paper][5]. Also, Michael Scharkow [details how to apply SCA to variance][9] and includes some R code.

 [1]: https://www.huffingtonpost.com/entry/social-media-mental-health_us_55b129d9e4b08f57d5d3eedf
 [2]: https://www.theatlantic.com/magazine/archive/2017/09/has-the-smartphone-destroyed-a-generation/534198/
 [3]: https://www.nature.com/articles/s41562-018-0506-1
 [4]: https://repository.upenn.edu/cgi/viewcontent.cgi?article=1314&context=marketing_papers
 [5]: https://www.amyorben.com/pdf/2019_orbenprzybylski_nhb.pdf
 [6]: https://lh5.googleusercontent.com/1fyqKDYKYVDufAqyzOJ-KbvY_37mcUNMOLxdhC8aTizV9K1c1Yzbw-sILC2adJdNuuQ36YBvB9BjRrA1BxgKE8q5pN54MGLocy7g0PSwTYAYuMbyBDlobDmJa9am70Ra5P_-MpEN
 [7]: https://socialsciences.nature.com/users/200472-amy-orben/posts/42763-beyond-cherry-picking
 [8]: https://osf.io/phf8v/
 [9]: https://underused.org/2019-01-spec-curve