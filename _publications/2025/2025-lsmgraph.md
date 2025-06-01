---
title:          "LSMGraph: A High-Performance Dynamic Graph Storage System with Multi-level CSR"
date:           2025-01-01 00:01:00 +0800
selected:       true
pub:            "Proceedings of the International Conference on Management of Data (SIGMOD)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2025"

abstract: >-
  We propose LSMGraph, a novel dynamic graph storage system that combines the write-friendly LSM-tree and the read-friendly CSR. It leverages the multi-level structure of LSM-trees to optimize write performance while utilizing the compact CSR structures embedded in the LSM-trees to boost read performance. LSMGraph uses a new memory structure, MemGraph, to efficiently cache graph updates and uses a multi-level index to speed up reads within the multi-level structure. Furthermore, LSMGraph incorporates a vertex-grained version control mechanism to mitigate the impact of LSM-tree compaction on read performance and ensure the correctness of concurrent read and write operations.
# cover:          /assets/images/covers/sigmod-neutronrag.png
authors:
  - "<b style='font-weight:900;color:#000;'>Song Yu</b>"
  - Shufeng Gong
  - Qian Tao
  - Sijie Shen
  - Wenyuan Yu
  - Pengxi Liu
  - Zhixin Zhang
  - Hongfu Li
  - Xiaojian Luo
  - Ge Yu
  - Jingren Zhou
links:
  Paper: https://dl.acm.org/doi/10.1145/3698818
  # Code: https://github.com/iDC-NEU/NeutronRAG
---