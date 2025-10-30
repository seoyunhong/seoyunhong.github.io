---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome to my website! 

My name is Seoyun Hong, and I also go by Stella. I am a PhD candidate in economics at Boston University. 

[Click here for my CV](https://seoyunhong.github.io/assets/CV_Stella Hong.pdf) 

## Job Market Paper
<b>
  <a href="https://www.dropbox.com/scl/fi/qb78aivj26uuweza6kgun/JMP_Seoyun_Hong.pdf?rlkey=en9drc7f1uj1r66l5bbf6wqh0&dl=0" target="_blank" rel="noopener" style="text-decoration:none">
    Heterogeneous Treatment Effects with Endogeneity and High-Dimensional Covariates
  </a>
</b>
<br>
<a href="#/" style="color:black; text-decoration:underline" onclick="visib('jmp')">Abstract</a>
<div id="jmp" style="display:none; background-color:#F1F1F1; color:#666; padding:10px; margin-top:6px;">
  <small>
    This paper develops estimation and inference for heterogeneous treatment effects by observed covariates in settings with an endogenous treatment and high-dimensional covariates. The goal is to provide valid inference when effect heterogeneity is high-dimensional and discovered from the data using machine learning, rather than restricted to a few prespecified covariates. I estimate heterogeneous treatment effects by interacting the treatment with all covariates and select the relevant interactions with a variable selection method. I address endogeneity with instrumental variables and uncover new patterns in treatment effects. In an application to Head Start, a public early childhood education program, I examine complementarities between center characteristics and children's background, while prior work has considered center or child characteristics in isolation. The proposed method reveals that frequent home visits are most helpful for children who likely need additional support, such as those with teen mothers or in high-risk households. Transportation services deliver larger gains for children who may face access barriers.
  </small>
</div>

<script>
function visib(id) {
  var x = document.getElementById(id);
  x.style.display = (x.style.display === "none" || x.style.display === "") ? "block" : "none";
}
</script>



