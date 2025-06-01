---
title:          "Fast Iterative Graph Computing with Updated Neighbor States"
# date:           2024-02-01 00:01:00 +0800
selected:       true
pub:            "International Conference on Data Engineering (ICDE)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2024"

abstract: >-
  We propose a graph reordering method, GoGraph, which can construct a well-formed vertex processing order effectively reducing the number of iteration rounds and, consequently, accelerating iterative computation. Before delving into GoGraph, a metric function is introduced to quantify the efficiency of vertex processing order in accelerating iterative computation. This metric reflects the quality of the processing order by counting the number of edges whose source precedes the destination. GoGraph employs a divide-and-conquer mindset to establish the vertex processing order by maximizing the value of the metric function. 

# cover:          /assets/images/covers/vldb-neutronbench.png
authors:
  - Yijie Zhou
  - Shufeng Gong
  - Feng Yao
  - Hanzhang Chen
  - Song Yu
  - Pengxi Liu
  - Yanfeng Zhang
  - Ge Yu
  - Jeffrey Xu Yu
links:
  Paper: https://ieeexplore.ieee.org/abstract/document/10597711
  Code: https://github.com/iDC-NEU/GoGraph
  Slides: https://github.com/iDC-NEU/iDC-NEU.github.io/blob/master/slides/GoGraph_ICDE24.pdf
---
