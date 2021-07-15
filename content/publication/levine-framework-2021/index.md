---
title: "A Framework for Machine Learning of Model Error in Dynamical Systems"
date: 2021-07-14
publishDate: 2022-07-14T07:23:28.587662Z
authors: ["Matthew E. Levine", "Andrew M. Stuart"]
publication_types: ["2"]
abstract: "The development of data-informed predictive models for dynamical systems is of widespread interest in many disciplines. We present a unifying framework for blending mechanistic and machine-learning approaches to identify dynamical systems from data. We compare pure data-driven learning with hybrid models which incorporate imperfect domain knowledge. We cast the problem in both continuous- and discrete-time, for problems in which the model error is memoryless and in which it has significant memory, and we compare data-driven and hybrid approaches experimentally. Our formulation is agnostic to the chosen machine learning model. Using Lorenz '63 and Lorenz '96 Multiscale systems, we find that hybrid methods substantially outperform solely data-driven approaches in terms of data hunger, demands for model complexity, and overall predictive performance. We also find that, while a continuous-time framing allows for robustness to irregular sampling and desirable domain-interpretability, a discrete-time framing can provide similar or better predictive performance, especially when data are undersampled and the vector field cannot be resolved. We study model error from the learning theory perspective, defining excess risk and generalization error; for a linear model of the error used to learn about ergodic dynamical systems, both errors are bounded by terms that diminish with the square-root of T. We also illustrate scenarios that benefit from modeling with memory, proving that continuous-time recurrent neural networks (RNNs) can, in principle, learn memory-dependent model error and reconstruct the original system arbitrarily well; numerical results depict challenges in representing memory by this approach. We also connect RNNs to reservoir computing and thereby relate the learning of memory-dependent error to recent work on supervised learning between Banach spaces using random features."
featured: true
publication: "*arXiv:2107.06658 [math, stat, cs]*"
tags: ["Adult", "Algorithms", "Blood Glucose", "Computational Biology", "Diabetes Mellitus", "Type 2", "Female", "Humans", "Insulin", "Male", "Patient-Specific Modeling"]
url_pdf: "https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005232"
doi: "10.1371/journal.pcbi.1005232"
---
