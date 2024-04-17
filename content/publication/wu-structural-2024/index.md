---
title: "Learning About Structural Errors in Models of Complex Dynamical Systems"
date: 2023-12-29
publishDate: 2023-12-29T07:23:28.587662Z
authors: ["Jin-Long Wu", "Matthew E. Levine","Tapio Schneider", "Andrew Stuart"]
publication_types: ["2"]
abstract: "Complex dynamical systems are notoriously difficult to model because some degrees of freedom (e.g., small scales) may be computationally unresolvable or are incompletely understood, yet they are dynamically important. For example, the small scales of cloud dynamics and droplet formation are crucial for controlling climate, yet are unresolvable in global climate models. Semi-empirical closure models for the effects of unresolved degrees of freedom often exist and encode important domain-specific knowledge. Building on such closure models and correcting them through learning the structural errors can be an effective way of fusing data with domain knowledge. Here we describe a general approach, principles, and algorithms for learning about structural errors. Key to our approach is to include structural error models inside the models of complex systems, for example, in closure models for unresolved scales. The structural errors then map, usually nonlinearly, to observable data. As a result, however, mismatches between model output and data are only indirectly informative about structural errors, due to a lack of labeled pairs of inputs and outputs of structural error models. Additionally, derivatives of the model may not exist or be readily available. We discuss how structural error models can be learned from indirect data with derivative-free Kalman inversion algorithms and variants, how sparsity constraints enforce a 'do no harm' principle, and various ways of modeling structural errors. We also discuss the merits of using non-local and/or stochastic error models. In addition, we demonstrate how data assimilation techniques can assist the learning about structural errors in non-ergodic systems. The concepts and algorithms are illustrated in two numerical examples based on the Lorenz-96 system and a human glucose-insulin model."
featured: true
publication: "In Review"
tags: []
url_pdf: "https://arxiv.org/abs/2401.00035"
---
