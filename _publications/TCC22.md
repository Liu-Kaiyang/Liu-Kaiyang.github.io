---
title: "[J5] A Learning-Based Data Placement Framework for Low Latency in Data Center Networks"
collection: publications
category: manuscripts
permalink: /publication/TCC22
excerpt: 'This paper is about learning-based data placement for intra-data center networks.'
date: 2022-01-01
venue: 'IEEE Transactions on Cloud Computing'
paperurl: 'https://liu-kaiyang.github.io/files/TCC22.pdf'
citation: 'Kaiyang Liu, Jun Peng, Jingrong Wang, Boyang Yu, Zhuofan Liao, Zhiwu Huang, Jianping Pan. A learning-based data placement framework for low latency in data center networks, IEEE Transactions on Cloud Computing, vol. 10, no. 1, pp. 146–157, 2022.'
---

Abstract: Low-latency data service is an increasingly critical challenge for data center applications. In modern distributed storage systems, proper data placement helps reduce the data movement delay, which can contribute to the service latency reduction tremendously. Existing data placement solutions have often assumed the prior distribution of data requests or discovered it via trace analysis. However, data placement is a difficult online decision-making problem faced with dynamic network conditions and time-varying user request patterns. The conventional static model-based solutions are less effective to handle the dynamic system. With an overall consideration of data movement and analytical latency, we develop a reinforcement learning-based framework DataBot+, automatically learning the optimal placement policies. DataBot+ adopts neural networks, trained with a variant of Q-learning, whose input is the real-time data flow measurements and whose output is a value function estimating the near-future latency. For instantaneous decision making, DataBot+ is decoupled into two asynchronous production and training components, ensuring that the training delay will not introduce extra overheads to handle the data flows. Evaluation results driven by real-world traces demonstrate the effectiveness of our design.
