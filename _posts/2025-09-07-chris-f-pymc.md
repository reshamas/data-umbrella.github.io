---
layout: post
title:  Contributing to the NumPy Documentation
description: A rich list of demos and resources to get started in contributing to NumPy.
date: 2025-09-07 10:01:35 +0300
image: '/images/blogs/blog-numpy.png'
tags: [opensource]
author-name: "Reshama Shaikh"
author-image: "/images/people/reshama.jpg"
author-linkedin: "https://www.linkedin.com/in/reshamas/"
author-website: "https://github.com/reshamas"
---

## Timestamps

[00:00](https://www.youtube.com/watch?v=jrU0UBr2z3k) Data Umbrella introduction  
[03:50](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=230s) Chris F begins presentation  
[05:42](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=342s) Agenda / outline  
[06:18](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=378s) What is PyMC?  
[07:37](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=457s) Why Bayesian modeling?  
[08:58](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=538s) Real world applications  
[10:08](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=608s) Installation and setup  
[12:20](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=740s) Sampling backends and libraries  
[12:40](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=760s) Q: what about uv for installation?  
[13:32](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=812s) Q: what is the recommended installation for HPC?  
[16:28](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=988s) Test your installation  
[17:00](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=1020s) Trouble shooting common issues  
[19:42](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=1182s) Performance: BLAS backends  
[20:29](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=1229s) PyMC fundamentals \- Bayes Theorem and the Computational Challenge  
[21:57](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=1317s) MCMC inference method (the model container, random variables and distributions)  
[25:22](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=1522s) Observed data  
[26:09](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=1569s) Data handling pitfalls (NumPy, pandas, polars, dataframes; missing data)  
[27:47](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=1667s) ArViz: diagnostics and visualization  
[28:58](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=1738s) Building your first model  
[31:20](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=1880s) Models dims and coords  
[32:23](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=1943s) Common modeling errors  
[33:35](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=2015s) Prior predictive check  
[34:49](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=2089s) Sampling the posterior  
[35:50](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=2150s) Trace plots: checking convergence; posterior distributions, parameter relationships, model summary table  
[40:35](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=2435s) Common pitfalls and solutions (convergence diagnostics, divergences, diagnosing sampling problems)  
[44:19](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=2659s) Performance optimization (prior specification problems)  
[47:11](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=2831s) Debugging workflow  
[48:49](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=2929s) Bambi: high-level modeling  
[49:33](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=2973s) PyMC-Extras: Cutting edge  
[50:25](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=3025s) Community & learning resources (+ PyMC example notebooks)  
[54:05](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=3245s) Future direction of PyMC  
[56:30](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=3390s) Community & Process  
[57:40](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=3460s) Q: what program did you use to create the slides? ([https://sli.dev](https://sli.dev)  
[58:50](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=3530s) Q: is PyMC using NumPy v2.0? (Answer: yes)  
[01:00:13](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=3613s) Q: why use the context manager?  
[01:01:02](https://www.youtube.com/watch?v=jrU0UBr2z3k&t=3662s) Q: How can I evaluate whether my model has too many parameters?  
