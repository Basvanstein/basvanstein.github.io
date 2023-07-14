---
title: "BIAS: A Toolbox for Benchmarking Structural Bias in the Continuous Domain"
collection: talks
type: "talk"
permalink: /talks/2023-07-15-talk-gecco-bias
venue: "GECCO 2023"
date: 2023-07-15
location: "Lisbon, Portugal"
header:
  teaser: "teasers/biastoolbox.png"
  image: "teasers/biastoolbox.png"
---

## Hot off the Press presentation @Gecco.

Watch the [Video](https://youtu.be/tVBM56y-lU0){:target="_blank"}

[Code](https://github.com/Dvermetten/BIAS){:target="_blank"} | [Full paper](https://ieeexplore.ieee.org/abstract/document/9828803){:target="_blank"}

Benchmarking heuristic algorithms is vital to understand under which conditions and on what kind of problems certain algorithms perform well. Most benchmarks are performance based, to test algorithm performance under a wide set of conditions. There is also resource- and behavior-based benchmarks to test the resource consumption and the behavior of algorithms. In this article, we propose a novel behavior-based benchmark toolbox: BIAS (Bias in algorithms, structural). This toolbox can detect structural bias (SB) per dimension and across dimension-based on 39 statistical tests. Moreover, it predicts the type of SB using a random forest model. BIAS can be used to better understand and improve existing algorithms (removing bias) as well as to test novel algorithms for SB in an early phase of development. Experiments with a large set of generated SB scenarios show that BIAS was successful in identifying bias. In addition, we also provide the results of BIAS on 432 existing state-of-the-art optimization algorithms showing that different kinds of SB are present in these algorithms, mostly toward the center of the objective space or showing discretization behavior. The proposed toolbox is made available open-source and recommendations are provided for the sample size and hyper-parameters to be used when applying the toolbox on other algorithms.

