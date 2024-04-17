---
title: "Hybrid Square Neural ODE Causal Modeling"
date: 2024-02-27
publishDate: 2024-02-27T07:23:28.587662Z
authors: ["Bob Junyi Zou", "Matthew E. Levine", "Dessi P. Zaharieva", "Ramesh Johari", "Emily Fox"]
publication_types: ["2"]
abstract: "Hybrid models combine mechanistic ODE-based dynamics with flexible and expressive neural network components. Such models have grown rapidly in popularity, especially in scientific domains where such ODE-based modeling offers important interpretability and validated causal grounding (e.g., for counterfactual reasoning). The incorporation of mechanistic models also provides inductive bias in standard blackbox modeling approaches, critical when learning from small datasets or partially observed, complex systems. Unfortunately, as hybrid models become more flexible, the causal grounding provided by the mechanistic model can quickly be lost. We address this problem by leveraging another common source of domain knowledge: ranking of treatment effects for a set of interventions, even if the precise treatment effect is unknown. We encode this information in a causal loss that we combine with the standard predictive loss to arrive at a hybrid loss that biases our learning towards causally valid hybrid models. We demonstrate our ability to achieve a win-win -- state-of-the-art predictive performance and causal validity -- in the challenging task of modeling glucose dynamics during exercise."
featured: true
publication: "In Review"
tags: []
url_pdf: "https://arxiv.org/abs/2402.17233"
---
