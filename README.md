# RHUL_RGroup_BayesLMMs

<p>Tutorial on Bayesian LMMs at RHUL 27/3/23
</p>
<p>In this short tutorial, I will show one way of fitting Bayesian linear mixed effects models using <em>brms</em>. This repository contains everything you will need to replicate the code in this script. The data comes from a continuous primed lexical decision task, and we will be analysing whether the participants' ERPs in the (pre-defined) N400 spatiotemporal window were more positive when the targets were preceded by semantically related as opposed to unrelated primes (i.e., N400 priming effect). We'll do the analysis step by step:
- make sure the data is as it should be
- contrast coding 
- setting the priors
- prior predictive checks
- model fitting & diagnostics
- posterior predictive checks
- sensitivity analysis
</p>
<p>I will show how, in this particular example, model fit can be improved by using distributional regression with a random effects structure not just for the location parameter but also for the scale parameter.
</p>
<p>If there is time, I will also provide an example of how to analyse response times data with Bayesian LMMs. 
</p>
