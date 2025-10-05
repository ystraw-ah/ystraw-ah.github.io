---
title:          "GoVector:基于向量相似性的I/O高效向量近邻查询缓存策略 (GoVector: An I/O-Efficient Caching Strategy for High-Dimensional Vector Neighbor Search)"
# date:           2025-01-01 00:01:00 +0800
selected:       true
pub:            "软件学报, 2025, 37(3): 0-0."
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2025"

abstract: >-
  We propose GoVector, an I/O-efficient caching strategy tailored for disk-based graph indices. GoVector combines (1) a static cache that stores entry points and frequently accessed neighbors, and (2) a dynamic cache that adaptively captures nodes with high spatial locality during the second search phase. To further align storage layout with similarity-driven search patterns, GoVector reorders nodes on disk so that similar vectors are colocated on the same or adjacent pages, thereby improving locality and reducing I/O overhead. Extensive experiments on multiple public datasets show that GoVector achieves substantial performance improvements.
cover:          /assets/images/covers/GoVector.png
authors:
  - 周依杰
  - 林圣原
  - 巩树凤
  - <b style='font-weight:900;color:#000;'>余松</b>
  - 范书豪
  - 张岩峰
  - 于戈
links:
  Paper: https://jos.org.cn/jos/article/abstract/qu015
  # Code: https://github.com/iDC-NEU/NeutronRAG
---