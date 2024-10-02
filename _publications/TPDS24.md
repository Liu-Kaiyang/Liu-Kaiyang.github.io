---
title: "[J1] Sampling-Based Multi-Job Placement for Heterogeneous Deep Learning Clusters"
collection: publications
category: manuscripts
permalink: /publication/TPDS24
excerpt: 'This paper is about multi-job placement to accelerate distributed deep learning in data center networks.'
date: 2024-06-01
venue: 'IEEE Transactions on Parallel and Distributed Systems'
paperurl: 'https://liu-kaiyang.github.io/files/TPDS24.pdf'
citation: 'Kaiyang Liu, Jingrong Wang, Zhiming Huang, Jianping Pan, Sampling-based multi-job placement for heterogeneous deep learning clusters, IEEE Transactions on Parallel and Distributed Systems, vol. 35, no. 6, pp. 874–888, 2024.'
---

Abstract: Heterogeneous deep learning clusters commonly host a variety of distributed learning jobs. In such scenarios, the training efficiency of learning models is negatively affected by the slowest worker. To accelerate the training process, multiple learning jobs may compete for limited computational resources, posing significant challenges to multi-job placement among heterogeneous workers. This article presents a heterogeneity-aware scheduler to solve the multi-job placement problem while taking into account job sizing and load balancing, minimizing the average Job Completion Time (JCT) of deep learning jobs. A novel scheme based on proportional training workload assignment, feasible solution categorization, and matching markets is proposed with theoretical guarantees. To further reduce the computational complexity for low latency decision-making and improve scheduling fairness, we propose to construct the sparsification of feasible solution categories through sampling, which has negligible performance loss in JCT. We evaluate the performance of our design with real-world deep neural network benchmarks on heterogeneous computing clusters. Experimental results show that, compared to existing solutions, the proposed sampling-based scheme can achieve 1) results within 2.04% of the optimal JCT with orders-of-magnitude improvements in algorithm running time, and 2) high scheduling fairness among learning jobs.
