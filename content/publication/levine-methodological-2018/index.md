---
title: "Methodological variations in lagged regression for detecting physiologic drug effects in EHR data"
date: 2018-01-01
publishDate: 2020-04-22T07:23:28.586798Z
authors: ["Matthew E. Levine", "David J. Albers", "George Hripcsak"]
publication_types: ["2"]
abstract: "We studied how lagged linear regression can be used to detect the physiologic effects of drugs from data in the electronic health record (EHR). We systematically examined the effect of methodological variations ((i) time series construction, (ii) temporal parameterization, (iii) intra-subject normalization, (iv) differencing (lagged rates of change achieved by taking differences between consecutive measurements), (v) explanatory variables, and (vi) regression models) on performance of lagged linear methods in this context. We generated two gold standards (one knowledge-base derived, one expert-curated) for expected pairwise relationships between 7 drugs and 4 labs, and evaluated how the 64 unique combinations of methodological perturbations reproduce the gold standards. Our 28 cohorts included patients in the Columbia University Medical Center/NewYork-Presbyterian Hospital clinical database, and ranged from 2820 to 79,514 patients with between 8 and 209 average time points per patient. The most accurate methods achieved AUROC of 0.794 for knowledge-base derived gold standard (95%CI [0.741, 0.847]) and 0.705 for expert-curated gold standard (95% CI [0.629, 0.781]). We observed a mean AUROC of 0.633 (95%CI [0.610, 0.657], expert-curated gold standard) across all methods that re-parameterize time according to sequence and use either a joint autoregressive model with time-series differencing or an independent lag model without differencing. The complement of this set of methods achieved a mean AUROC close to 0.5, indicating the importance of these choices. We conclude that time-series analysis of EHR data will likely rely on some of the beneficial pre-processing and modeling methodologies identified, and will certainly benefit from continued careful analysis of methodological perturbations. This study found that methodological variations, such as pre-processing and representations, have a large effect on results, exposing the importance of thoroughly evaluating these components when comparing machine-learning methods."
featured: false
publication: "*Journal of Biomedical Informatics*"
tags: ["Academic Medical Centers", "Area Under Curve", "Data Collection", "Databases", "Factual", "Drug Therapy", "Electronic Health Records", "Humans", "Linear Models", "Machine Learning", "New York City", "Pharmaceutical Preparations", "Regression Analysis", "Reproducibility of Results", "ROC Curve", "Time Factors"]
doi: "10.1016/j.jbi.2018.08.014"
---
