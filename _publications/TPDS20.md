---
title: "[J11] Scalable and Adaptive Data Replica Placement for Geo-Distributed Cloud Storages"
collection: publications
category: manuscripts
permalink: /publication/TPDS20
excerpt: 'This paper is about community discovery and adjustment based data replica placement schemes in geo-distributed cloud storage systems.'
date: 2020-07-01
venue: 'IEEE Transactions on Parallel and Distributed Systems'
paperurl: 'https://liu-kaiyang.github.io/files/TPDS20.pdf'
citation: 'Kaiyang Liu, Jun Peng, Jingrong Wang, Weirong Liu, Zhiwu Huang, Jianping Pan. Scalable and adaptive data replica placement for geo-distributed cloud storages, IEEE Transactions on Parallel and Distributed Systems, vol. 31, no. 7, pp. 1575–1587, 2020.'
---

Abstract: In geo-distributed cloud storage systems, data replication has been widely used to serve the ever more users around the world for high data reliability and availability. How to optimize the data replica placement has become one of the fundamental problems to reduce the inter-node traffic and the system overhead of accessing associated data items. In the big data era, traditional solutions may face the challenges of long running time and large overheads to handle the increasing scale of data items with time-varying user requests. Therefore, novel offline community discovery and online community adjustment schemes are proposed to solve the replica placement problem in a scalable and adaptive way. The offline scheme can find a replica placement solution based on the average read/write rates for a certain period of time. The scalability can be achieved as 1) the computation complexity is linear to the amount of data items and 2) the data-node communities can evolve in parallel for a distributed replica placement. Furthermore, the online scheme is adaptive to handle the bursty data requests, without the need to completely override the existing replica placement. Driven by real-world data traces, extensive performance evaluations demonstrate the effectiveness of our design to handle large-scale datasets..
