---
title: "Learning Task Belief Similarity with Latent Dynamics for Meta-Reinforcement Learning"
collection: publications
category: conferences
permalink: /redirect-to-external
redirect_to:
  - https://openreview.net/forum?id=5YbuOTUFQ4
excerpt: '**Menglong zhang**, Fuyuan Qian, Quanying Liu<br/>Under review as a conference paper at ICLR 2025 (rating: 8,6,6,6) (12.69%)<br/><br/><img src="/images/SimBelief.png" alt="SimBelief Illustration" style="width: 500px; height: auto;">'
date: 2024-10-02
paperurl: 'http://menglong-zhang.github.io/files/ICLR_simbelief__12_18___preprint_.pdf'
---
Meta-reinforcement learning requires utilizing prior task distribution information obtained during exploration to rapidly adapt to unknown tasks. The efficiency of an agent's exploration hinges on accurately identifying the current task. Recent Bayes-Adaptive Deep RL approaches often rely on reconstructing the environment's reward signal, which is challenging in sparse reward settings, leading to suboptimal exploitation. Inspired by bisimulation metrics, which robustly extracts behavioral similarity in continuous MDPs, we propose SimBelief—a novel meta-RL framework via measuring similarity of task belief in Bayes-Adaptive MDP (BAMDP). SimBelief effectively extracts common features of similar task distributions, enabling efficient task identification and exploration in sparse reward environments. We introduce latent task belief metric to learn the common structure of similar tasks and incorporate it into the specific task belief. By learning the latent dynamics across task distributions, we connect shared latent task belief features with specific task features, facilitating rapid task identification and adaptation. Our method outperforms state-of-the-art baselines on sparse reward MuJoCo and panda-gym tasks.The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font.
