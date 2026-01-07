---
title:          "Point Mamba: A Novel Point Cloud Backbone Based on State Space Model with Octree-Based Ordering Strategy"
date:           2024-5-11
selected:       true
pub:            "Preprint"
# pub_last:       '<span class="badge badge-pill badge-publication badge-success">ICLR 2025</span> <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       ""
abstract: >-
  Recently, state space model (SSM) has gained great attention due to its promising performance, linear complexity, and long sequence modeling ability in both language and image domains. However, it is non-trivial to extend SSM to the point cloud field, because of the causality requirement of SSM and the disorder and irregularity nature of point clouds. In this paper, we propose a novel SSM-based point cloud processing backbone, named Point Mamba, with a causality-aware ordering mechanism. To construct the causal dependency relationship, we design an octree-based ordering strategy on raw irregular points, globally sorting points in a z-order sequence and also retaining their spatial proximity. Our method achieves state-of-the-art performance compared with transformer-based counterparts, with 93.4% accuracy and 75.7 mIOU respectively on the ModelNet40 classification dataset and ScanNet semantic segmentation dataset. Furthermore, our Point Mamba has linear complexity, which is more efficient than transformer-based methods. Our method demonstrates the great potential that SSM can serve as a generic backbone in point cloud understanding.
cover:          /assets/images/covers/cover3.jpg
authors:
- Jiuming Liu*
- Ruiji Yu*
- Yian Wang
- Yu Zheng
- Tianchen Deng
- Weicai Ye
- Hesheng Wang
links:
  Paper: https://arxiv.org/abs/2403.06467
  Code:  https://github.com/IRMVLab/Point-Mamba
---
