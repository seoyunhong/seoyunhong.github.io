---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome! My name is Seoyun Hong, and I also go by Stella. I am a PhD candidate in economics at Boston University. 
<p style="text-align: justify; text-justify: inter-word;">
My research is at the intersection of econometrics and applied microeconomics, including labor economics and industrial organization. In econometrics, I develop new causal inference methods that leverage machine learning and high-dimensional data. In applied microeconomics, I develop estimators tailored to each problem to study empirical questions, including the gender wage gap across work hours and the effects of collusion on prices in procurement auctions.
</p>

I am on the 2025-2026 job market. 

[Click here for my CV](https://www.dropbox.com/scl/fi/7rxmwh4d2bqkpp3i3ftgt/CV_Seoyun-Hong.pdf?rlkey=dnft6yk3sbrdy0p5hi0wl4q3j&dl=0) 

## Job Market Paper
<b>
  <a href="https://www.dropbox.com/scl/fi/qb78aivj26uuweza6kgun/JMP_Seoyun_Hong.pdf?rlkey=en9drc7f1uj1r66l5bbf6wqh0&dl=0" target="_blank" rel="noopener" style="text-decoration:none">
    Heterogeneous Treatment Effects with Endogeneity and High-Dimensional Covariates
  </a>
</b>
<br>
<a href="#/" style="color:black; text-decoration:underline" onclick="visib('jmp')">Abstract</a>
<div id="jmp" style="display:none; background-color:#F1F1F1; color:#666; padding:10px; margin-top:6px;">
This paper develops instrumental variable estimation methods for heterogeneous treatment effects in settings with an endogenous treatment and high-dimensional covariates. The goal is to provide valid inference on treatment effect heterogeneity with respect to observed covariates, when covariates are high-dimensional and heterogeneity is discovered using machine learning. I address treatment endogeneity through instrumental variables. To model heterogeneous effects, I interact the treatment with flexible transformations of all covariates and select relevant interactions with a variable selection procedure. Applying the proposed method, I study the heterogeneous treatment effects of Head Start, a public early childhood education program, on children's cognitive skills. The results reveal complementarities between center characteristics and children's background. I find that frequent home visits increase the effect of the program for children who need additional support, and transportation services deliver larger program gains for children who may face access barriers. These findings uncover that children have greater benefits from the program when center features align with their needs, highlighting the importance of considering rich heterogeneity for policy implications.
</div>

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

