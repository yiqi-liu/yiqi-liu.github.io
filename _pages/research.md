---
permalink: /research/
toc: false
classes: wide
---

My research interests are in theoretical and applied econometrics. I work on identification problems for more credible causal inference, as well as nonparametric estimation and statistical inference for interesting policy questions.

## Working Papers
- **Synthetic Parallel Trends** (Job Market Paper)<br>
<div class="abstract" markdown="1">
*Abstract*: Popular empirical strategies for policy evaluation in the panel data literature---including difference-in-differences (DID), synthetic control (SC) methods, and their variants---rely on key identifying assumptions that can be expressed through a specific choice of weights $\\omega$ relating pre-treatment trends to the counterfactual outcome. While each choice of $\\omega$ may be defensible in empirical contexts that motivate a particular method, it relies on fundamentally untestable and often fragile assumptions. I develop an identification framework that allows for all weights satisfying a _Synthetic Parallel Trends_ assumption: the treated unit's trend is parallel to a weighted combination of control units' trends for a general class of weights. The framework nests these existing methods as special cases and is by construction robust to violations of their respective assumptions. 
I construct a valid confidence set for the identified set of the treatment effect, which admits a linear programming representation with estimated coefficients and nuisance parameters that are profiled out. In simulations where the assumptions underlying DID or SC-based methods are violated, the proposed confidence set remains robust and attains nominal coverage, while existing methods suffer severe undercoverage.
</div>

<p class="paper-links">
[`arXiv`](https://drive.google.com/file/d/1MD1JSP1aNwMH1MtrSSLZH9HQFjY-bNlD/view?usp=sharing) | [`code`]
</p>

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

.paper-links {
  margin-left: 0em; 
  font-size: 0.85em;
  line-height: 1.3;
  margin-top: -0.6em;
}

.abstract mjx-container {
  line-height: inherit !important;
}
</style>

- **Inference for an Algorithmic Fairness-Accuracy Frontier** (2025), with [Francesca Molinari](https://molinari.economics.cornell.edu/)\
  <span style="font-size:0.8em;">Extended abstract in *Proceedings of the 25th ACM Conference on Economics and Computation (EC'24)*</span> \
  [[`arXiv`](https://arxiv.org/abs/2402.08879)] | [[`code`](https://github.com/yiqi-liu/TestAlgFair)] | [[`EC'24`](https://dl.acm.org/doi/10.1145/3670865.3673522)]
- **Using Forests in Multivariate Regression Discontinuity Designs** (2025), with [Alice Yuan Qi](https://econ.washington.edu/people/yuan-alice-qi) \
  [[`arXiv`](https://arxiv.org/abs/2303.11721)] | [[`code`](https://github.com/yqi3/RDForest)]


## Work in Progress
- **Partial Identification of Algorithmic Frontiers with Selective Labels**, with [Francesca Molinari](https://molinari.economics.cornell.edu/) and [Amilcar Velez](https://www.amilcarvelez.com/)
