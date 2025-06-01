---
title:          "Ingress: an automated incremental graph processing system"
date:           2024-01-01 00:01:00 +0800
selected:       false
pub:            "VLDB J"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2024"

abstract: >-
  We propose Ingress, an automated system for incremental graph processing. Ingressis able to deduce the incremental counterpart of a batch vertex-centric algorithm, without the need of redesigned logic or data structures from users. Underlying Ingressis an automated incrementalization framework equipped with four different memoization policies, to support all kinds of vertexcentric computations with optimized memory utilization. We identify sufficient conditions for the applicability of these policies. Ingress chooses the best-fit policy for a given algorithm automatically by verifying these conditions. In addition to the ease-of-use and generalization, Ingress outperforms state-of-the-art incremental graph systems by 12.14× on average (up to 49.23×) in efficiency
# cover:          /assets/images/covers/kbs-neutronsketch.png
authors:
  - Shufeng Gong
  - Chao Tian
  - Qiang Yin
  - Zhengdong Wang
  - "<b style='font-weight:900;color:#000;'>Song Yu</b>"
  - Yanfeng Zhang
  - Wenyuan Yu
  - Liang Geng
  - Chong Fu
  - Ge Yu
  - Jingren Zhou
links:
  Paper: https://link.springer.com/article/10.1007/s00778-024-00838-z
  Code: https://github.com/gongsf-neu/Ingress
---
