---
abstract: |
 Dynamic graphs whose topology and nodes evolve over time are ubiquitous in multiple real
 world domains such as social networks, finance, and healthcare. Traditional graph
 learning methods fail to capture structural changes and temporal patterns in dynamic
 graphs. Recent advances in dynamic graph representation learning, such as
 meta-learning-based approaches, have addressed some of these challenges. However,
 existing methods still face three key limitations. First, most approaches capture either
 local or global structures of the graphs, neglecting to model both simultaneously.
 Second, meta-learning models often depend on user-specific window size, which must be
 carefully tuned for each dataset. A short window size may miss trends, and a long window
 size may blur recent updates. Third, most methods work on only discrete-time or
 continuous-time dynamic graphs, resulting in suboptimal performance across different
 temporal settings. To address these limitations in dynamic graph representation
 learning, we propose a novel method called DyGSSM (Multi-view Dynamic Graph Embeddings
 with SSM Gradient Update). We extract local and global features at each snapshot and
 fuse them using a lightweight attention mechanism for link prediction. To capture
 long-term dependencies when updating model parameters, we incorporate HiPPO (High-order
 Polynomial Projection Operators) algorithm, which has gained attention for its ability
 to efficiently optimize and preserve sequence history in State Space Models (SSMs).
 DyGSSM is designed to handle both discrete-time and continuous-time dynamic graphs.
 Parameter comparisons show that DyGSSM requires substantially fewer parameters than the
 other methods. Extensive experiments on 12 public datasets demonstrate that DyGSSM
 outperforms baselines and State-Of-The-Art (SOTA) methods in 32 out of 36 evaluation
 metrics. The source code and datasets are available at
 https://github.com/bozdaglab/DyGSSM.
openreview: uRLMoB6Ijx
section: Poster Presentations
title: |
 DyGSSM: Multi-view Dynamic Graph Embeddings with SSM Gradient Update
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: alipourpijani25a
month: 0
tex_title: |
 DyGSSM: Multi-view Dynamic Graph Embeddings with SSM Gradient Update
firstpage: '15:1'
lastpage: '15:20'
page: 15:1-15:20
order: 15
cycles: false
bibtex_author: |
 Alipourpijani, Bizhan and Bozdag, Serdar
author:
- given: 'Bizhan'
  family: 'Alipourpijani'
- given: 'Serdar'
  family: 'Bozdag'
date: 2026-05-12
address:
container-title: Proceedings of the Fourth Learning on Graphs Conference
volume: '0'
genre: inproceedings
issued:
 date-parts:
 - 2026
 - 5
 - 12
pdf: https://raw.githubusercontent.com/mlresearch/v0/main/assets/alipourpijani25a/alipourpijani25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
