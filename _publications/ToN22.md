---
title: "[J4] Optimal Caching for Low Latency in Distributed Coded Storage Systems"
collection: publications
category: manuscripts
permalink: /publication/ToN22
excerpt: 'This paper is about an optimal cache content replacement scheme in geo-distributed cloud/edge networks.'
date: 2022-06-01
venue: 'IEEE/ACM Transactions on Networking'
paperurl: 'https://liu-kaiyang.github.io/files/ToN22.pdf'
citation: 'Kaiyang Liu, Jun Peng, Jingrong Wang, Jianping Pan, Optimal caching for low latency in distributed coded storage systems, IEEE/ACM Transactions on Networking, vol. 30, no. 3, pp. 1132–1145, 2022.'
---

Abstract: Erasure codes have been widely considered as a promising solution to enhance data reliability at low storage costs. However, in modern geo-distributed storage systems, erasure codes may incur high data access latency as they require data retrieval from multiple remote storage nodes. This hinders the extensive application of erasure codes to data-intensive applications. This paper proposes novel caching schemes to achieve low latency in distributed coded storage systems. Assuming that future data popularity and network latency information are available, an offline caching scheme is proposed to explore the optimal caching solution for low latency. The proposed scheme categorizes all feasible caching decisions into a set of cache partitions, and then obtains the optimal caching decision through market clearing price for each cache partition. Furthermore, guided by the optimal scheme, an online caching scheme is proposed according to the measured data popularity and network latency information in real time, without the need to completely override the existing caching decisions. Both theoretical analysis and experiment results demonstrate that the online scheme can approximate the offline optimal scheme well with dramatically reduced computation complexity.
