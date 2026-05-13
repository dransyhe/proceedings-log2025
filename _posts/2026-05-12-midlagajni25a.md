---
abstract: |
 Simulating particle dynamics with high fidelity is crucial for solving real-world
 interaction and control tasks involving liquids in design, graphics, and robotics.
 Recently, data-driven approaches, particularly those based on graph neural networks
 (GNNs), have shown progress in tackling such problems. However, these approaches are
 often limited to learning fluid behavior in static free-fall environments or simple
 manipulation settings involving primitive objects, often overlooking complex
 interactions with dynamically moving kinematic rigid bodies. Here, we propose a
 GNN-based framework designed from the ground up to learn the dynamics of liquids under
 rigid body interactions and active manipulations, where particles are represented as
 graph nodes and particle-object collisions are handled using surface representations
 with the bounding volume hierarchy (BVH) algorithm. Our approach accurately captures
 fluid behavior in dynamic settings and can also function as a simulator in static
 free-fall environments. Despite being trained on single-object manipulation tasks, our
 model generalizes effectively to environments with novel objects and novel manipulation
 tasks. Finally, we show that the learned dynamics can be leveraged to solve control and
 manipulation tasks using gradient-based optimization methods.
openreview: vGjFGfHR42
section: Poster Presentations
title: |
 Learning Particle Dynamics Subject to Rigid Body Manipulations Using Graph Neural
 Networks
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: midlagajni25a
month: 0
tex_title: |
 Learning Particle Dynamics Subject to Rigid Body Manipulations Using Graph Neural
 Networks
firstpage: '23:1'
lastpage: '23:17'
page: 23:1-23:17
order: 23
cycles: false
bibtex_author: |
 Midlagajni, Niteesh and Rothkopf, Constantin A.
author:
- given: 'Niteesh'
  family: 'Midlagajni'
- given: 'Constantin A.'
  family: 'Rothkopf'
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
pdf: https://raw.githubusercontent.com/mlresearch/v0/main/assets/midlagajni25a/midlagajni25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
