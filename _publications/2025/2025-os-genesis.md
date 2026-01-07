---
title:          "OS-Genesis: Automating GUI Agent Trajectory Construction via Reverse Task Synthesis"
date:           2025-06-27
selected:       true
pub:            '<span class="badge badge-pill badge-primary">ACL main 2025</span>'
pub_date:       ""
abstract: >-
  Graphical User Interface (GUI) agents powered by Vision-Language Models (VLMs) have demonstrated human-like computer control capability. Despite their utility in advancing digital automation, a critical bottleneck persists: collecting high-quality trajectory data for training. Common practices for collecting such data rely on human supervision or synthetic data generation through executing pre-defined tasks, which are either resource-intensive or unable to guarantee data quality. Moreover, these methods suffer from limited data diversity and significant gaps between synthetic data and real-world environments. To address these challenges, we propose OS-Genesis, a novel GUI data synthesis pipeline that reverses the conventional trajectory collection process. Instead of relying on pre-defined tasks, OS-Genesis enables agents first to perceive environments and perform step-wise interactions, then retrospectively derive high-quality tasks to enable trajectory-level exploration. A trajectory reward model is then employed to ensure the quality of the generated trajectories. We demonstrate that training GUI agents with OS-Genesis significantly improves their performance on highly challenging online benchmarks. In-depth analysis further validates OS-Genesis's efficiency and its superior data quality and diversity compared to existing synthesis methods.
cover:          /assets/images/covers/cover2.jpg
authors:
- Qiushi Sun
- Kanzhi Cheng
- Zichen Ding
- Chuanyang Jin
- Yian Wang
- Fangzhi Xu
- Zhenyu Wu
- Chengyou Jia
- Liheng Chen
- Zhoumianze Liu
- Ben Kao
- Guohao Li
- Junxian He
- Yu Qiao
- Zhiyong Wu
links:
  Website: https://qiushisun.github.io/OS-Genesis-Home/
  Paper: https://arxiv.org/abs/2412.19723
  Code: https://github.com/OS-Copilot/OS-Genesis
---
