---
title: "[J2] Sampling-Based Caching for Low Latency in Distributed Coded Storage Systems"
collection: publications
category: manuscripts
permalink: /publication/TSC23
excerpt: 'This paper is about a sampling-based cache content replacement scheme in geo-distributed cloud/edge networks.'
date: 2023-11-01
venue: 'IEEE Transactions on Services Computing'
paperurl: 'https://liu-kaiyang.github.io/files/TSC23.pdf'
citation: 'Kaiyang Liu, Jingrong Wang, Heng Li, Jun Peng, Jianping Pan, Sampling-based caching for low latency in distributed coded storage systems, IEEE Transactions on Services Computing, vol. 16, no. 6, pp. 4275–4287, 2023.'
---

Abstract: Caching has been considered as a promising solution to achieve low latency in distributed erasure coded storage systems. The previous research work categorizes all feasible caching decisions into a set of cache partitions, and then obtains the optimal solution by applying the market clearing price on each cache partition. While enjoying the ultimate performance of low data access latency, the optimal scheme suffers from high computation overheads when applied to large-scale storage systems. This paper presents SampleX, which constructs the sparsification of cache partitions through sampling to approximate the optimal caching scheme with substantially reduced computation complexity. Theoretical analysis guarantees the performance of SampleX. Furthermore, SampleX is implemented in a streaming fashion, capturing the characteristics of recent traffic for online cache content replacement. Trace-driven experimental results show that online SampleX is up to 95× faster than the state-of-the-art online scheme while only incurring a performance loss of 0.81%.
