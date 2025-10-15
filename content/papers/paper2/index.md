---
title: "Stochastic Gradient Langevin Dynamics for (weakly) log-concave posterior distributions" 
date: 2024-10-23
author: ["Marelys Crespo Navas", "Sébastien Gadat", "Xavier Gendre"]
summary: "This paper studies the Stochastic Gradient Langevin Dynamics in a weak convex setting." 

---

##### Download

+ [Paper](paper2.pdf)

---

##### Abstract

In this paper, we investigate a continuous time version of the Stochastic Gradient Langevin Dynamics, introduced in [53], that incorporates a stochastic sampling step inside the traditional over-damped Langevin diffusion. This method is popular in machine learning for sampling a posterior distribution. We will pay specific attention to the computational cost in terms of n (the number of observations that produces the posterior distribution), and d (the dimension of the ambient space where the parameter of interest is living). We derive our analysis in the weakly convex framework, which is parameterized with the help of the Kurdyka-Łojasiewicz (KL) inequality, that permits to handle a vanishing curvature settings, which is far less restrictive when compared to the simple strongly convex case. We establish that the final horizon of simulation to obtain an $\epsilon$ approximation (in terms of entropy) is of the order ($d\log^2(n))^{(1+r)^2}[\log^2(\epsilon^{−1})+n^2d^{2(1+r)} \log^{4(1+r)}(n)$] with a Poissonian sub-sampling of parameter ($d \log^2(n))^{−(1+r)^2}$, where the parameter $r$ is involved in the KL inequality and varies between 0 (strongly log-concave case) and 1 (limiting Laplace situation).

---

##### Citation

Marelys Crespo Navas. Sébastien Gadat. Xavier Gendre. "Stochastic Gradient Langevin Dynamics for (weakly) log-concave posterior distributions." Electron. J. Probab. 29 1 - 40, 2024. https://doi.org/10.1214/24-EJP1235 

```BibTeX
@article{10.1214/24-EJP1235,
author = {Marelys Crespo Navas and S{\'e}bastien Gadat and Xavier Gendre},
title = {{Stochastic Gradient Langevin Dynamics for (weakly) log-concave posterior distributions}},
volume = {29},
journal = {Electronic Journal of Probability},
number = {none},
publisher = {Institute of Mathematical Statistics and Bernoulli Society},
pages = {1 -- 40},
keywords = {log-concave models, stochastic gradient Langevin dynamics, weak convexity},
year = {2024},
doi = {10.1214/24-EJP1235},
URL = {https://doi.org/10.1214/24-EJP1235}}
```

---
