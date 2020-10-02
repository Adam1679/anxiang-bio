---
title: Auto-ML Library Design
date: 2020-10-02T05:55:35.100Z
draft: false
featured: false
tags:
  - system
external_link: http://8.210.65.111/
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
---
* Designed a heuristic tree-based distributed Auto-ML training framework using Dask.distributed, a Python distributed framework.

* Implemented successive halving algorithm during hyper-parameter tuning to attain high parallelism; Results showed 5x speedup using two 4-core nodes and 94% prediction accuracy on KC1 dataset.

