---
title:          "A Topology-Aware Localized Update Strategy for Graph-Based ANN Index"
# date:           2025-01-01 00:01:00 +0800
selected:       true
pub:            "Very Large Data Bases (VLDB)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2026"

abstract: >-
  We propose a topology-aware localized update strategy that exploits the locality of small-batch updates to reduce unnecessary I/O and computation. Specifically, we introduce a lightweight graph topology to efficiently identify affected nodes without full index scans and adopt a localized update mechanism that confines index modifications to only the affected file pages, thereby greatly reducing unnecessary I/O overhead. Moreover, we design a similarity-aware local connection method that links each affected node to a small set of the most similar neighbors in the deleted node’s local region, reducing redundant connections and avoiding expensive pruning.
cover:          /assets/images/covers/VLDB26-Greator.png
authors:
  - "<b style='font-weight:900;color:#000;'>Song Yu</b>"
  - Shengyuan Lin
  - Shufeng Gong
  - Yongqing Xie
  - Ruicheng Liu
  - Yijie Zhou
  - Ji Sun
  - Yanfeng Zhang
  - Guoliang Li
  - Ge Yu
links:
  Paper: xxxx
  # Code: https://github.com/iDC-NEU/NeutronRAG
---