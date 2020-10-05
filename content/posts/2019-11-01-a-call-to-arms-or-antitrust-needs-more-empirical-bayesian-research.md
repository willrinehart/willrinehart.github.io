---
title: 'A Call To Arms, or Antitrust Needs More Empirical Bayesian Research [Abstract]'
author: Will
type: post
date: 2019-11-01T16:09:19+00:00
url: /2019/a-call-to-arms-or-antitrust-needs-more-empirical-bayesian-research/
categories:
  - Uncategorized

---
_[Extended Abstract: November 1, 2019]_ 

The mundane world of antitrust economics has been transformed in the last decade, driven by a recorded rise in economic concentration. Across the political range from President Trump and Senator Josh Hawley to presidential hopefuls Elizabeth Warren and Bernie Sanders, attention has been directed towards the largest and most malleable source of antitrust enforcement policy, merger policy. But like the rest of antitrust, there is a dearth of empirically rooted studies on the effectiveness of antitrust policy. Even more rare are empirical analysis rooted in Bayesian analysis. This paper will reverse course by laying out a new research agenda based on empirical Bayesianism. After detailing the current state of the literature, it will combine data from Kwoka (2015) and Coate (2014) to run a new meta-study of merger price effects and explain why these methods excel at solving the problems laid out by Carlton (2009).

Retrospective mergers studies were first conducted in the early 2000s (Vita & Osinski, 2018). While there has long been demand for publicly available research, output has been limited. In 2009, Dennis W. Carlton took an appraisal and came to decry “the inadequacy of our current state of knowledge regarding the effectiveness of antitrust policy.” In a paper appropriately titled, “Why We Need to Measure the Effect of Merger Policy and How to Do It,” Carlton laid out the reasons for empirical studies, but also explained the problem of detecting the true price effects of antitrust enforcement. To be clear, the price effect of enforcement describes the change in prices in an industry due to an agency antitrust action. At a minimum, the observed price effects are inherently stochastic, which needs to be reflected in analysis. Decomposing the observed from the true price effect could be understood as,

<p style="text-align: center;">
  <img loading="lazy" src="https://www.williamrinehart.com/wp-content/ql-cache/quicklatex.com-29c52345bd1705645937e2d09b0ee3d5_l3.png" class="ql-img-inline-formula quicklatex-auto-format" alt="&#92;&#68;&#101;&#108;&#116;&#97;&#32;&#80;&#32;&#95;&#123;&#68;&#79;&#74;&#125;&#32;&#61;&#32;&#92;&#68;&#101;&#108;&#116;&#97;&#32;&#80;&#32;&#43;&#32;&#83;&#32;&#43;&#32;&#92;&#101;&#116;&#97;" title="Rendered by QuickLaTeX.com" height="16" width="175" style="vertical-align: -4px;" />
</p>

Where

  *<img loading="lazy" src="https://www.williamrinehart.com/wp-content/ql-cache/quicklatex.com-f4c8b06e44d265862c1a27c3f708835f_l3.png" class="ql-img-inline-formula quicklatex-auto-format" alt="&#92;&#68;&#101;&#108;&#116;&#97;&#32;&#80;&#32;&#95;&#123;&#68;&#79;&#74;&#125;" title="Rendered by QuickLaTeX.com" height="15" width="58" style="vertical-align: -3px;" /> = Observed price effect of the DOJ’s enforcement
  *<img loading="lazy" src="https://www.williamrinehart.com/wp-content/ql-cache/quicklatex.com-03417f507cc4317aced756e201aa2ec1_l3.png" class="ql-img-inline-formula quicklatex-auto-format" alt="&#8710;&#80;" title="Rendered by QuickLaTeX.com" height="12" width="14" style="vertical-align: 0px;" /> = Real price effect
  *<img loading="lazy" src="https://www.williamrinehart.com/wp-content/ql-cache/quicklatex.com-520cb534cd5b6bed768a61515b57cb7e_l3.png" class="ql-img-inline-formula quicklatex-auto-format" alt="&#83;" title="Rendered by QuickLaTeX.com" height="12" width="12" style="vertical-align: 0px;" /> = Systemic bias
  *<img loading="lazy" src="https://www.williamrinehart.com/wp-content/ql-cache/quicklatex.com-353d8843a56869470cc39f8575e0c785_l3.png" class="ql-img-inline-formula quicklatex-auto-format" alt="&#92;&#101;&#116;&#97;" title="Rendered by QuickLaTeX.com" height="12" width="9" style="vertical-align: -4px;" /> = random error independent of<img loading="lazy" src="https://www.williamrinehart.com/wp-content/ql-cache/quicklatex.com-03417f507cc4317aced756e201aa2ec1_l3.png" class="ql-img-inline-formula quicklatex-auto-format" alt="&#8710;&#80;" title="Rendered by QuickLaTeX.com" height="12" width="14" style="vertical-align: 0px;" /> and<img loading="lazy" src="https://www.williamrinehart.com/wp-content/ql-cache/quicklatex.com-520cb534cd5b6bed768a61515b57cb7e_l3.png" class="ql-img-inline-formula quicklatex-auto-format" alt="&#83;" title="Rendered by QuickLaTeX.com" height="12" width="12" style="vertical-align: 0px;" /> with<img loading="lazy" src="https://www.williamrinehart.com/wp-content/ql-cache/quicklatex.com-955b6eccdbbe133eb9d4942351b04e6e_l3.png" class="ql-img-inline-formula quicklatex-auto-format" alt="&#69;&#91;&#48;&#93;" title="Rendered by QuickLaTeX.com" height="18" width="31" style="vertical-align: -5px;" /> .

In response to this call, Coate (2014) and Kwoka (2015) compiled and then analyzed the available studies. While both are important additions to the scholarship, there are two primary drawbacks with their approach.

The first concern lies in the interpretation of the estimated parameter. In the classical framework, confidence intervals are measures of frequency that the interval will contain the true parameter, which is the true price effect. Empirical Bayesianism has the benefit of calculating the whole posterior distribution of the parameter. A reproduction of the same meta-study through these methods will yield probability statements of the true parameter given fixed bounds. If properly constructed then, the Bayesian credible interval will more closely approximate the true range of the price effect, the goal of Carlton. As the FTC’s Christopher Adams (2018) explained in one of the few papers in this literature, “The empirical Bayesian estimator appropriately accounts for sampling variation, shrinking the magnitude of the treatment effect relative the standard approach.”

Second, Bayesian methods offer flexibility in their model design, which is needed for the problem at hand. As noted above, the enforcement price effect is stochastic, but there is more to the story because each possible outcome in the process of securing a deal leads to a unique dataset and thus sampling issues. Those mergers that are abandoned after a challenge are of a different nature than those that go to trial. Using hierarchical methods within a Bayesian framework will allow for the proper implementation of Carlton’s extended analysis.

The limits of antitrust are constrained by the costs of action and information. This paper aims to better understand both by explaining the importance of empirical Bayesianism to antitrust, completing a meta-study in this methodology, and then setting a path for further exploration.

* * *

_References_

Adams, C. P. (2018). Empirical Bayesian Estimation of Merger Effects. Retrieved October 28, 2019, from <https://www.econ.pitt.edu/sites/default/files/Adams.Christopher.pdf>.

Carlton, D. W. (2009, February 13). Why We Need to Measure the Effect of Merger Policy and How to Do It. Retrieved October 28, 2019, from <http://economics.mit.edu/files/4149>.

Coate, M. B. (2014, April 7). A Meta-Study of Merger Retrospectives in the United States. Retrieved October 28, 2019, from <https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2333815>.

Kwoka, J. (2018). _Mergers, Merger Control, and Remedies: A Retrospective analysis of U.S. Policy_. Hong Kong: MIT Press.

Vita, M., & Osinski, D. (2016, December 22). John Kwoka&#8217;s Mergers, Merger Control, and Remedies: A Critical Review. Retrieved October 28, 2019, from <https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2888485>.