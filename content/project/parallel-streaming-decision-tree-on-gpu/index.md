---
title: Parallel Streaming Decision Tree on GPU
date: 2020-10-02T05:46:51.298Z
summary: >-
  * Built a renderer to draw colored circles having sequential dependency.
  Utilized exclusive-scan to leverage shared memory

  in CUDA blocks, achieving 10 times improvement compared to benchmark.


  * Applied message passing model using OpenMPI, CUDA to parallelize streaming histogram-based decision tree building process; applied OpenMPI gather, scatter collective operation to do decentralized ring allreduce synchronization to achieve better bandwidth usage and load balancing.


  * Bundled 4 binned features into a 4-feature tuple to leverage locality of GPU memory access.
draft: false
featured: false
tags:
  - system
external_link: https://linna1998.github.io/Parallel-Decision-Tree-on-GPU/
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
---


