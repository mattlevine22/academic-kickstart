---
title: "Offline and online data assimilation for real-time blood glucose forecasting in type 2 diabetes"
date: 2017-09-01
publishDate: 2020-04-22T07:23:28.587662Z
authors: ["Matthew E. Levine", "George Hripcsak", "Lena Mamykina", "Andrew Stuart", "David J. Albers"]
publication_types: ["2"]
abstract: "We evaluate the benefits of combining different offline and online data assimilation methodologies to improve personalized blood glucose prediction with type 2 diabetes self-monitoring data. We collect self-monitoring data (nutritional reports and pre- and post-prandial glucose measurements) from 4 individuals with diabetes and 2 individuals without diabetes. We write online to refer to methods that update state and parameters sequentially as nutrition and glucose data are received, and offline to refer to methods that estimate parameters over a fixed data set, distributed over a time window containing multiple nutrition and glucose measurements. We fit a model of ultradian glucose dynamics to the first half of each data set using offline (MCMC and nonlinear optimization) and online (unscented Kalman filter and an unfiltered model---a dynamical model driven by nutrition data that does not update states) data assimilation methods. Model parameters estimated over the first half of the data are used within online forecasting methods to issue forecasts over the second half of each data set. Offline data assimilation methods provided consistent advantages in predictive performance and practical usability in 4 of 6 patient data sets compared to online data assimilation methods alone; yet 2 of 6 patients were best predicted with a strictly online approach. Interestingly, parameter estimates generated offline led to worse predictions when fed to a stochastic filter than when used in a simple, unfiltered model that incorporates new nutritional information, but does not update model states based on glucose measurements. The relative improvements seen from the unfiltered model, when carefully trained offline, exposes challenges in model sensitivity and filtering applications, but also opens possibilities for improved glucose forecasting and relaxed patient self-monitoring requirements."
featured: false
publication: "*arXiv:1709.00163 [math, q-bio]*"
tags: ["Mathematics - Dynamical Systems", "Quantitative Biology - Quantitative Methods"]
url_pdf: "http://arxiv.org/abs/1709.00163"
---

