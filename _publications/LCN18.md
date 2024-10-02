---
title: "[C5] Learning-based Adaptive Data Placement for Low Latency in Data Center Networks"
collection: publications
category: conferences
permalink: /publication/LCN18
excerpt: 'This paper is about learning-based data placement for intra-data center networks.'
date: 2018-10-01
venue: 'IEEE Conference on Local Computer Networks (LCN)'
slidesurl: 'http://academicpages.github.io/files/LCN18_slides.pdf'
paperurl: 'https://liu-kaiyang.github.io/files/LCN18.pdf'
citation: 'Kaiyang Liu, Jingrong Wang, Zhuofan Liao, Boyang Yu, Jianping Pan. Learning-based adaptive data placement for low latency in data center networks, IEEE Conference on Local Computer Networks, pp. 142–149, 2018.'
---

Abstract: Low-latency data access is an important challenge for data center networks. Proper placement of the data items can reduce the data travel time in the distributed storage systems, which contributes significantly to the latency reduction. Most existing data placement approaches have often assumed the prior distribution of data requests or discovered so through trace analysis. However, the traditional static model-based solutions are less effective to handle the system uncertainties in a dynamic environment. We present DataBot, a reinforcement learning-based adaptive framework, to learn the optimal data placement policies faced with the dynamic network conditions and time-varying request patterns. DataBot utilizes a neural network, trained with a variant of Q-learning, whose input is the realtime data flow measurements and whose output is a value function estimating the near-future latency. For rapid decision making, DataBot is divided into two decoupled production and training components, ensuring that the convergence time of the training will not introduce more overheads to serve the read/write requests. Evaluation results demonstrate that the average write and read latency of the whole system can be lowered by about 35% and 40%, respectively.
