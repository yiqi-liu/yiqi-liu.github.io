---
permalink: /research/
toc: false
classes: wide
---

My research interests are in theoretical and applied econometrics. I work on identification problems for more credible causal inference, as well as nonparametric estimation and statistical inference for interesting policy questions.

## Working Papers
- **Inference for an Algorithmic Fairness-Accuracy Frontier** (2025), with [Francesca Molinari](https://molinari.economics.cornell.edu/)\
  <span style="font-size:0.8em;">Extended abstract in *Proceedings of the 25th ACM Conference on Economics and Computation (EC'24)*</span> \
  [[`arXiv`](https://arxiv.org/abs/2402.08879)] | [[`code`](https://github.com/yiqi-liu/TestAlgFair)] | [[`EC'24`](https://dl.acm.org/doi/10.1145/3670865.3673522)]
- **Using Forests in Multivariate Regression Discontinuity Designs** (2025), with [Alice Yuan Qi](https://econ.washington.edu/people/yuan-alice-qi) \
  [[`arXiv`](https://arxiv.org/abs/2303.11721)] | [[`code`](https://github.com/yqi3/RDForest)]


## Work in Progress
- **Synthetic Parallel Trends** (Job Market Paper)<br>
<div class="abstract" markdown="1">
*Abstract*: Popular empirical strategies for policy evaluation in the panel data literature---including difference-in-differences, synthetic control methods, and their variants---rely on key identifying assumptions that can be expressed through a specific choice of weights $\\omega$ relating pre-treatment trends to the counterfactual outcome. While each choice of $\\omega$ may be defensible in empirical contexts that motivate a particular method, it relies on fundamentally untestable and often fragile assumptions. I develop an identification framework that allows for all weights satisfying a _Synthetic Parallel Trends_ assumption: the treated unit's trend is parallel to a weighted combination of control units' trends for a general class of weights. The framework nests these existing methods as special cases and is by construction robust to violations of their respective assumptions. 
I characterize the identified set for the treatment effect of the treated unit, which admits a linear programming representation that yields moment equalities. I provide a consistent estimator and a valid confidence set for this identified set, and illustrate their finite-sample performance in a simulation and empirical value in an application.
</div>

<script>
  MathJax = {
    tex: { inlineMath: [['$', '$'], ['\\(', '\\)']] },
    svg: { fontCache: 'global' }
  };
</script>
<script id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-svg.js">
</script>

<style>
.abstract {
  font-size: 0.8em;
  line-height: 1.2 !important;
  margin-left: 2.3em; 
  margin-top: -0.8em;
}

.abstract mjx-container {
  line-height: inherit !important;
}
</style>
