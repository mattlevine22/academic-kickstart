---
title: "The Parameter Houlihan: a solution to high-throughput identifiability indeterminacy for brutally ill-posed problems"
date: 2019-02-01
publishDate: 2020-04-22T07:23:28.591559Z
authors: ["D. J. Albers", "M. Levine", "L. Mamykina", "G. Hripcsak"]
publication_types: ["2"]
abstract: "One way to interject knowledge into clinically impactful forecasting is to use data assimilation, a nonlinear regression that projects data onto a mechanistic physiologic model, instead of a set of functions, such as neural networks. Such regressions have an advantage of being useful with particularly sparse, non-stationary clinical data. However, physiological models are often nonlinear and can have many parameters, leading to potential problems with parameter identifiability, or the ability to find a unique set of parameters that minimize forecasting error. The identifiability problems can be minimized or eliminated by reducing the number of parameters estimated, but reducing the number of estimated parameters also reduces the flexibility of the model and hence increases forecasting error. We propose a method, the parameter Houlihan, that combines traditional machine learning techniques with data assimilation, to select the right set of model parameters to minimize forecasting error while reducing identifiability problems. The method worked well: the data assimilation-based glucose forecasts and estimates for our cohort using the Houlihan-selected parameter sets generally also minimize forecasting errors compared to other parameter selection methods such as by-hand parameter selection. Nevertheless, the forecast with the lowest forecast error does not always accurately represent physiology, but further advancements of the algorithm provide a path for improving physiologic fidelity as well. Our hope is that this methodology represents a first step toward combining machine learning with data assimilation and provides a lower-threshold entry point for using data assimilation with clinical data by helping select the right parameters to estimate."
featured: false
publication: "*arXiv:1902.01978 [q-bio, stat]*"
tags: ["Quantitative Biology - Quantitative Methods", "Statistics - Methodology"]
url_pdf: "http://arxiv.org/abs/1902.01978"
---

