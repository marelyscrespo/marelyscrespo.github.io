---
title: "Discretisation of Langevin diffusion in the weak log-concave case" 
date: 2024
author: "Marelys Crespo Navas" 

---

---

##### Download

+ [Paper](paper1.pdf)

---

##### Abstract

The Euler discretisation of Langevin diffusion, also known as Unadjusted Langevin Algorithm, is commonly used in machine learning for sampling from a given distribution mu e^(-U). In this paper we investigate a potential U : R^d to R which is a weakly convex function and has Lipschitz gradient. We parameterize the weak convexity with the help of the Kurdyka-Lojasiewicz (KL) inequality, that permits to handle a vanishing curvature settings, which is far less restrictive when compared to the simple strongly convex case. We prove that the final horizon of simulation to obtain an ε approximation (in terms of entropy) is of the order e^(-1) d^(1+2(1+r)^2) Poly(log(d), log(e^(-1))), where the parameter r is involved in the KL inequality and varies between 0 (strongly convex case) and 1 (limiting Laplace situation). 

---

##### Citation

Crespo Navas, Marelys. 2024. "Discretisation of Langevin diffusion in the weak log-concave case." preprint 

```BibTeX
@unpublished{crespo:hal-04427207,
  TITLE = {{Discretisation of Langevin diffusion in the weak log-concave case}},
  AUTHOR = {Crespo, Marelys},
  URL = {https://hal.science/hal-04427207},
  NOTE = {working paper or preprint},
  YEAR = {2024},
  MONTH = Jan,
  KEYWORDS = {Unadjusted Langevin Algorithm ; Entropy ; Weak convexity ; Rate of convergence},
  PDF = {https://hal.science/hal-04427207v1/file/ULA.pdf},
  HAL_ID = {hal-04427207},
  HAL_VERSION = {v1},
}
```

---


