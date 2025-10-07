---
title: In Search of Forgotten Domain Generalization
abstract: Out-of-Domain (OOD) generalization is the ability of a model trained on
  one or more domains to generalize to unseen domains. In the ImageNet era of computer
  vision, evaluation sets for measuring a model’s OOD performance were designed to
  be strictly OOD with respect to style. However, the emergence of foundation models
  and expansive web-scale datasets has obfuscated this evaluation process, as datasets
  cover a broad range of domains and risk test domain contamination. In search of
  the forgotten domain generalization, we create large-scale datasets subsampled from
  LAION—LAION-Natural and LAION-Rendition—that are strictly OOD to corresponding ImageNet
  and DomainNet test sets in terms of style. Training CLIP models on these datasets
  reveals that a significant portion of their performance is explained by in-domain
  examples. This indicates that the OOD generalization challenges from the ImageNet
  era still prevail and that training on web-scale data merely creates the illusion
  of OOD generalization. Furthermore, through a systematic exploration of combining
  natural and rendition datasets in varying proportions, we identify optimal mixing
  ratios for model generalization across these domains. Our datasets and results re-enable
  meaningful assessment of OOD robustness at scale—a crucial prerequisite for improving
  model robustness.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: mayilvahanan25a
month: 0
tex_title: In Search of Forgotten Domain Generalization
firstpage: 90
lastpage: 130
page: 90-130
order: 90
cycles: false
bibtex_author: Mayilvahanan, Prasanna and Zimmermann, Roland S. and Wiedemer, Thadd\"{a}us
  and Rusak, Evgenia and Juhos, Attila and Bethge, Matthias and Brendel, Wieland
author:
- given: Prasanna
  family: Mayilvahanan
- given: Roland S.
  family: Zimmermann
- given: Thaddäus
  family: Wiedemer
- given: Evgenia
  family: Rusak
- given: Attila
  family: Juhos
- given: Matthias
  family: Bethge
- given: Wieland
  family: Brendel
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
pdf: https://raw.githubusercontent.com/mlresearch/v296/main/assets/mayilvahanan25a/mayilvahanan25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
