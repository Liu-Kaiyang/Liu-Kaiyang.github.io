---
title: "[C2] End-to-End Congestion Control as Learning for Unknown Games with Bandit Feedback"
collection: publications
category: conferences
permalink: /publication/ICDCS18
excerpt: 'This paper is about learning-based congestion control for computer networks.'
date: 2023-07-18
venue: 'IEEE 43rd International Conference on Distributed Computing Systems (ICDCS)'
paperurl: 'https://liu-kaiyang.github.io/files/ICDCS23.pdf'
citation: 'Zhiming Huang, Kaiyang Liu, Jianping Pan. End-to-end congestion control as learning for unknown games with Bandit feedback, IEEE International Conference on Distributed Computing Systems, 2023.'
---

Abstract: In this paper, we study the open problems raised by Karp et al. in FOCS 2000, where the authors formulated the end-to-end congestion control as a repeated game between a flow and an adversary. They mentioned several open problems including finding equilibria in a more realistic game model for the situation where the available bandwidth is a result of competition among multiple flows instead of being chosen by an adversary, and designing the randomized algorithm to deal with the dynamic change of network bandwidth. Although there have been many game-theoretic works for congestion control, to the best of our knowledge, the above two problems still remain unsolved over the past decades. We take a step further to address the above two problems by first modeling the end-to-end congestion control as a repeated unknown general-sum game among multiple flows with bandit feedback. Each flow is a player in this unknown game, making decisions on how many packets to send. The throughput for each flow depends on all the flows' rates and the network capacity. The unknown setting and bandit feedback capture the essence of end-to-end congestion control: each flow has no information about others (e.g., the number, actions, and packet loss of other flows), and only receives limited information for its chosen action. Then, we propose a randomized no-regret learning algorithm for each flow called LUC based on a swap-regret-minimizing technique. We prove that LUC can guarantee a polynomial-time convergence rate to correlated equilibria in the multi-player setting. Finally, we have implemented LUC through the Linux kernel, and conducted extensive fairness-related experiments in Mininet and trace-driven experiments with Pantheon to show that each flow with LUC can fairly share the bandwidth in homogeneous scenarios, and be competitive but TCP-friendly in heterogeneous scenarios.
