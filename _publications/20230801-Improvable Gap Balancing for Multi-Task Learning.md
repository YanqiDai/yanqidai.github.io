---
title: "Improvable Gap Balancing for Multi-Task Learning"
collection: publications
permalink: /publication/20230801-Improvable Gap Balancing for Multi-Task Learning
excerpt: 'We propose two novel improvable gap balancing algorithms for multi-task learning, instead of the classic loss balancing strategy.'
date: 2023-08-01
venue: '39th Conference on Uncertainty in Artificial Intelligence (UAI 2023)'
paperurl: 'https://proceedings.mlr.press/v216/dai23a/dai23a.pdf'
citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
In multi-task learning (MTL), gradient balancing has recently attracted more research interest than loss balancing since it often leads to better performance. However, loss balancing is much more efficient than gradient balancing, and thus it is still worth further exploration in MTL. Note that prior studies typically ignore that there exist varying improvable gaps across multiple tasks, where the improvable gap per task is defined as the distance between the current training progress and desired final training progress. Therefore, after loss balancing, the performance imbalance still arises in many cases. In this paper, following the loss balancing framework, we propose two novel improvable gap balancing (IGB) algorithms for MTL: one takes a simple heuristic, and the other (for the first time) deploys deep reinforcement learning for MTL. Particularly, instead of directly balancing the losses in MTL, both algorithms choose to dynamically assign task weights for improvable gap balancing. Moreover, we combine IGB and gradient balancing to show the complementarity between the two types of algorithms. Extensive experiments on two benchmark datasets demonstrate that our IGB algorithms lead to the best results in MTL via loss balancing and achieve further improvements when combined with gradient balancing.
[Download paper here](https://proceedings.mlr.press/v216/dai23a/dai23a.pdf)

Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1).
