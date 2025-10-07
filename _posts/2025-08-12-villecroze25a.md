---
title: Last Layer Empirical Bayes
abstract: The task of quantifying the inherent uncertainty associated with neural
  network predictions is a key challenge in artificial intelligence. Bayesian neural
  networks (BNNs) and deep ensembles are among the most prominent approaches to tackle
  this task. Both approaches produce predictions by computing an expectation of neural
  network outputs over some distribution on the corresponding weights; this distribution
  is given by the posterior in the case of BNNs, and by a mixture of point masses
  for ensembles. Inspired by recent work showing that the distribution used by ensembles
  can be understood as a posterior corresponding to a learned data-dependent prior,
  we propose last layer empirical Bayes (LLEB). LLEB instantiates a learnable prior
  as a normalizing flow, which is then trained to maximize the evidence lower bound;
  to retain tractability we use the flow only on the last layer. We show why LLEB
  is well motivated, and how it interpolates between standard BNNs and ensembles in
  terms of the strength of the prior that they use. LLEB performs on par with existing
  approaches, highlighting that empirical Bayes is a promising direction for future
  research in uncertainty quantification.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: villecroze25a
month: 0
tex_title: Last Layer Empirical Bayes
firstpage: 75
lastpage: 83
page: 75-83
order: 75
cycles: false
bibtex_author: Villecroze, Valentin and Wang, Yixin and Loaiza-Ganem, Gabriel
author:
- given: Valentin
  family: Villecroze
- given: Yixin
  family: Wang
- given: Gabriel
  family: Loaiza-Ganem
date: 2025-08-12
address:
container-title: 'Proceedings on "I Can''t Believe It''s Not Better: Challenges in
  Applied Deep Learning" at ICLR 2025 Workshops'
volume: '296'
genre: inproceedings
issued:
  date-parts:
  - 2025
  - 8
  - 12
pdf: https://raw.githubusercontent.com/mlresearch/v296/main/assets/villecroze25a/villecroze25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
