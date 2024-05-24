---
title: "Wasserstein Dependent Graph Attention Network for Collaborative Filtering with Uncertainty"
date: 2024-04-09
categories:
  - Preprint
tags:
  - Collaborative Filtering
  - Mutual Information
  - Uncertainty
  - Wasserstein Distance
---

#### Authors
Haoxuan Li, Yuanxin Ouyang, Zhuang Liu, Wenge Rong, Zhang Xiong

#### Abstract
Collaborative filtering (CF) is an essential technique in recommender systems that provides personalized recommendations by only leveraging user-item interactions. However, most CF methods represent users and items as fixed points in the latent space, lacking the ability to capture uncertainty. In this paper, we propose a novel approach, called the Wasserstein dependent Graph ATtention network (W-GAT), for collaborative filtering with uncertainty. We utilize graph attention network and Wasserstein distance to address the limitations of LightGCN and Kullback-Leibler divergence (KL) divergence to learn Gaussian embedding for each user and item. Additionally, our method incorporates Wasserstein-dependent mutual information further to increase the similarity between positive pairs and to tackle the challenges induced by KL divergence. Experimental results on three benchmark datasets show the superiority of W-GAT compared to several representative baselines. Extensive experimental analysis validates the effectiveness of W-GAT in capturing uncertainty by modeling the range of user preferences and categories associated with items.

#### Link
https://arxiv.org/abs/2404.05962