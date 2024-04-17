---
title: "Learning Absorption Rates in Glucose-Insulin Dynamics from Meal Covariates"
date: 2022-12-02
publishDate: 2022-07-14T07:23:28.587662Z
authors: ["Ke Alexander Wang", "Matthew E. Levine", "Jiaxin Shi", "Emily Fox"]
publication_types: ["2"]
abstract: "Traditional models of glucose-insulin dynamics rely on heuristic parameterizations chosen to fit observations within a laboratory setting. However, these models cannot describe glucose dynamics in daily life. One source of failure is in their descriptions of glucose absorption rates after meal events. A meal's macronutritional content has nuanced effects on the absorption profile, which is difficult to model mechanistically. In this paper, we propose to learn the effects of macronutrition content from glucose-insulin data and meal covariates.  Given macronutrition information and meal times, we use a neural network to predict an individual's glucose absorption rate. We use this neural rate function as the control function in a differential equation of glucose dynamics, enabling end-to-end training. On simulated data, our approach is able to closely approximate true absorption rates, resulting in better forecast than heuristic parameterizations, despite only observing glucose, insulin, and macronutritional information.  Our work readily generalizes to meal events with higher-dimensional covariates, such as images, setting the stage for glucose dynamics models that are personalized to each individual's daily life."
featured: false
publication: "NeurIPS Timeseries for Health Workshop 2022"
tags: []
url_pdf: "https://openreview.net/forum?id=cbn7xvCCq6e"
---
