---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<section class="page__content" itemprop="text">
<hr>

<h2 id="publications">Publications</h2>

<ul>
  <li>
    <a href="https://link.springer.com/article/10.1007/s11151-022-09876-9" style="text-decoration:none" target="_blank">
      Measuring the Effects of Bid-rigging on Prices with Binary Misclassification
    </a> (with Changsik Kim and Hyunchul Kim),
    <em>Review of Industrial Organization</em> (2022)
    <br>
    <a href="#/" style="color:black; text-decoration:underline" onclick="visib('pub1')">Abstract</a>
  </li>
</ul>

<div id="pub1" style="display: none; background-color: #F1F1F1; color: #666; padding: 10px">
  The binary indicator of collusion is the key ingredient in estimating overcharges from bid-rigging with a regression-based approach.
  We develop a method for examining the effects of misclassification error in the indicator of bid-rigging status on estimates of damages from collusion.
  We derive partial identification of the regression model of winning bids in public procurement auctions and provide informative bounds on the price effects of bid-rigging.
  We find that the bounds are tight when placing a plausible restriction on the extent of measurement errors.
  Our findings show that relaxing the nondifferential assumption about misclassification errors leads to wider bounds.
</div>


<hr>
<h2 id="working-papers">Working Papers</h2>

<ul>
  <li>
     <a href="https://www.dropbox.com/scl/fi/qb78aivj26uuweza6kgun/JMP_Seoyun_Hong.pdf?rlkey=en9drc7f1uj1r66l5bbf6wqh0&dl=0" style="text-decoration:none" target="_blank">
          Heterogeneous Treatment Effects with Endogeneity and High-Dimensional Covariates
     </a>
    <br><b>Job Market Paper</b> |
    <a href="#/" style="color:black; text-decoration:underline" onclick="visib('jmp')">Abstract</a>
  </li>
</ul>

<div id="jmp" style="display: none; background-color: #F1F1F1; color: #666; padding: 10px">
  This paper develops estimation and inference for heterogeneous treatment effects by observed covariates in settings with an endogenous treatment and high-dimensional covariates.
  The goal is to provide valid inference when effect heterogeneity is high-dimensional and discovered from the data using machine learning, rather than restricted to a few prespecified covariates.
  I estimate heterogeneous treatment effects by interacting the treatment with all covariates and select the relevant interactions with a variable selection method.
  I address endogeneity with instrumental variables and uncover new patterns in treatment effects.
  In an application to Head Start, a public early childhood education program, I examine complementarities between center characteristics and children's background, while prior work has considered center or child characteristics in isolation.
  The proposed method reveals that frequent home visits are most helpful for children who likely need additional support, such as those with teen mothers or in high-risk households.
  Transportation services deliver larger gains for children who may face access barriers.
</div>


<ul>
  <li>
    <a href="https://arxiv.org/abs/2505.10814" style="text-decoration:none" target="_blank">
      Distribution Regression with Censored Selection
    </a> (with Ivan Fernandez-Val), May 2025
    <br>
    <a href="#/" style="color:black; text-decoration:underline" onclick="visib('dr')">Abstract</a>
  </li>
</ul>

<div id="dr" style="display: none; background-color: #F1F1F1; color: #666; padding: 10px">
  We develop a distribution regression model with a censored selection rule, offering a semi-parametric generalization of the Heckman selection model.
  Our approach applies to the entire distribution, extends beyond the mean or median, accommodates non-Gaussian error structures, and allows heterogeneous effects of covariates on both selection and outcome distributions.
  By employing a censored selection rule, our model can uncover richer selection patterns according to both outcome and selection variables, compared to the binary selection case.
  We analyze identification, estimation, and inference of model functionals such as sorting parameters and distributions purged of sample selection.
  An application to labor supply using data from the UK reveals different selection patterns into full-time and overtime work across gender, marital status, and time.
  Additionally, decompositions of wage distributions by gender show that selection effects contribute to a decrease in the observed gender wage gap at low quantiles and an increase in the gap at high quantiles for full-time workers.
  The observed gender wage gap among overtime workers is smaller, which may be driven by different selection behaviors into overtime work across genders.
</div>


<ul>
  <li>
    <a href="https://arxiv.org/abs/2303.02784" style="text-decoration:none" target="_blank">
      Censored Quantile Regression with Many Controls
    </a>, March 2023
    <br>
    <a href="#/" style="color:black; text-decoration:underline" onclick="visib('cqr')">Abstract</a>
  </li>
</ul>

<div id="cqr" style="display: none; background-color: #F1F1F1; color: #666; padding: 10px">
  This paper develops estimation and inference methods for censored quantile regression models with high-dimensional controls.
  The methods are based on the application of double/debiased machine learning (DML) framework to the censored quantile regression estimator of Buchinsky and Hahn (1998).
  I provide valid inference for low-dimensional parameters of interest in the presence of high-dimensional nuisance parameters when implementing machine learning estimators.
  The proposed estimator is shown to be consistent and asymptotically normal.
  The performance of the estimator with high-dimensional controls is illustrated with numerical simulation and an empirical application that examines the effect of 401(k) eligibility on savings.
</div>


<hr>
<h2 id="work-in-progress">Work in Progress</h2>

<ul>
  <li>
    Static Games with Machine Learning: Heterogeneous Peer Effects in Analyst Recommendations
    (with Hyungjin Kim)
  </li>
</ul>

<script>
function visib(id) {
  var x = document.getElementById(id);
  if (x.style.display === "none") {
    x.style.display = "block";
  } else {
    x.style.display = "none";
  }
}
</script>

</section>
