---
title: "Discretisation of Langevin diffusion in the weak log-concave case" 
date: 2024
author: "Marelys Crespo Navas" 

---

---

##### Download

+ [Paper](paper1.pdf)
+ [Online appendix](appendix1.pdf)
+ [Code and data](https://github.com/pmichaillat/feru)

---

##### Abstract

The Euler discretisation of Langevin diffusion, also known as Unadjusted Langevin Algorithm, is commonly used in machine learning for sampling from a given distribution mu e^(-U). In this paper we investigate a potential U : R^d to R which is a weakly convex function and has Lipschitz gradient. We parameterize the weak convexity with the help of the Kurdyka-Lojasiewicz (KL) inequality, that permits to handle a vanishing curvature settings, which is far less restrictive when compared to the simple strongly convex case. We prove that the final horizon of simulation to obtain an ε approximation (in terms of entropy) is of the order e^(-1) d^(1+2(1+r)^2) Poly(log(d), log(e^(-1))), where the parameter r is involved in the KL inequality and varies between 0 (strongly convex case) and 1 (limiting Laplace situation). 

---

##### Citation

Unterholzer, Detlev A., and  Moritz-Maria von Igelfeld. 2013. "Unusual Uses For Olive Oil." *Journal of Oleic Science* 34 (1): 449–489. http://www.alexandermccallsmith.com/book/unusual-uses-for-olive-oil.

```BibTeX
@article{UI13,
author = {Detlev A. Unterholzer and Moritz-Maria von Igelfeld},
year = {2013},
title ={Unusual Uses For Olive Oil},
journal = {Journal of Oleic Science},
volume = {34},
number = {1},
pages = {449--489},
url = {http://www.alexandermccallsmith.com/book/unusual-uses-for-olive-oil}}
```

---
