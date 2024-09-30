---
title: "An Instance Reservation Framework for Cost Effective Services in Geo-Distributed Data Centers"
collection: publications
category: manuscripts
permalink: /publication/TSC21
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2021-03-01
venue: 'IEEE Transactions on Services Computing'
paperurl: '[http://academicpages.github.io/files/TSC21.pdf](https://github.com/Liu-Kaiyang/Liu-Kaiyang.github.io/blob/master/files/TSC21.pdf)'
citation: 'Kaiyang Liu, Jun Peng, Boyang Yu, Weirong Liu, Zhiwu Huang, Jianping Pan. An instance reservation framework for cost effective services in geo-distributed data centers, IEEE Transactions on Services Computing, vol. 14, no.
2, pp. 356–370, 2021.'
---

Infrastructure-as-a-Service clouds in geo-distributed data centers offer various pricing options, including on-demand and reserved instances, which provide an elastic and cost-effective infrastructure to support High Performance Computing (HPC) applications. In this paper, we propose an instance reservation based cloud service framework, modeling the cost-minimizing reservation decision issue as an NP-hard integer programming problem for distributed data centers. To ease its computation complexity, two algorithms are proposed to minimize the HPC service cost with the worst-case performance guarantees: an offline heuristic-greedy algorithm, and a rolling-horizon based online algorithm when only short-term demand prediction is available. Facing fluctuating demands, instance reservation in a single data center may incur the highly underutilized capacity. To address this issue for further cost reduction, we extend the scheme with a novel cloud broker federation based resource sharing mechanism, reallocating already reserved but unused instances to computation-intensive and short-lived tasks for continuous execution without interruption. Extensive evaluations driven by large-scale trace-based datasets demonstrate that the proposed mechanism can effectively handle large volumes of service requests, saving considerable service costs with higher reservation resource utilization.
