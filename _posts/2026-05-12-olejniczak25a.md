---
abstract: |
 Motivated by the incompleteness of modern knowledge graphs, a new setup for query
 answering has emerged, where the goal is to predict answers that do not necessarily
 appear in the knowledge graph, but are present in its *completion*. In this paper, we
 formally introduce and study two query answering problems, namely, *query answer
 classification* and *query answer retrieval*. To solve these problems, we propose ANYCQ,
 a model that can classify answers to *any* conjunctive query on *any* knowledge graph.
 At the core of our framework lies a graph neural network trained using a reinforcement
 learning objective to answer Boolean queries. Trained only on simple, small instances,
 ANYCQ generalizes to *large queries* of *arbitrary* structure, reliably classifying and
 retrieving answers to queries that existing approaches fail to handle. This is
 empirically validated through our newly proposed, challenging benchmarks. Finally, we
 empirically show that ANYCQ can effectively transfer to *completely novel* knowledge
 graphs when equipped with an appropriate link prediction model, highlighting its
 potential for querying incomplete data.
openreview: Fo2GLDelI1
section: Oral Presentations
software: https://github.com/kolejnyy/ANYCQ/
title: |
 One Model, Any Conjunctive Query: Graph Neural Networks for Answering Queries over
 Incomplete Knowledge Graphs
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: olejniczak25a
month: 0
tex_title: |
 One Model, Any Conjunctive Query: Graph Neural Networks for Answering Queries over
 Incomplete Knowledge Graphs
firstpage: '6:1'
lastpage: '6:30'
page: 6:1-6:30
order: 6
cycles: false
bibtex_author: |
 Olejniczak, Krzysztof and Huang, Xingyue and Galkin, Mikhail and Ceylan, Ismail Ilkan
author:
- given: 'Krzysztof'
  family: 'Olejniczak'
- given: 'Xingyue'
  family: 'Huang'
- given: 'Mikhail'
  family: 'Galkin'
- given: 'Ismail Ilkan'
  family: 'Ceylan'
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
pdf: https://raw.githubusercontent.com/mlresearch/v0/main/assets/olejniczak25a/olejniczak25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
