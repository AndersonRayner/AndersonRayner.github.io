---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Neural Tree Expansion for Multi-Robot Planning in Non-Cooperative Environments"
authors: 
- Benjamin Riviere
- Wolfgang Hoenig
- Matthew Anderson
- Soon-Jo Chung
date: 2021-06-20

publication_types: 
  - article-journal

publication: "IEEE Robotics and Automation Letters"
publication_short: "IEEE RAL"

tags:
- robotics
featured: false

links:
- type: pdf
  url: https://arxiv.org/pdf/2104.09705.pdf

image:
  caption: ""
  focal_point: "smart"
  preview_only: false

projects:
- swarmAI

---

We present a self-improving, neural tree expansionmethod for multi-robot online planning in non-cooperative environments, where each robot tries to maximize its cumulative reward while interacting with other self-interested robots. Our algorithm adapts the centralized, perfect information, discrete-action space method from Alpha Zero to a decentralized, partial information, continuous action space setting for multi-robot applications. Our method has three interacting components:(i) a centralized, perfect-information ''expert'' Monte Carlo Tree Search (MCTS) with large computation resources that provides expert demonstrations, (ii) a decentralized, partial-information ''learner'' MCTS with small computation resources that runs in real-time and provides self-play examples, and (iii) policy & value neural networks that are trained with the expert demonstrations and bias both the expert and the learner tree growth. Our numerical experiments demonstrate neural expansion generates compact search trees with better solution quality and 20 times less computational expense compared to MCTS without neural expansion. The resulting policies are dynamically sophisticated, demonstrate coordination between robots, and play the Reach-Target-Avoid differential game significantly better than the state-of-the-art control-theoretic base-line for multi-robot, double-integrator systems. Our hardware experiments on an aerial swarm demonstrate the computational advantage of neural tree expansion, enabling online  planning at 20 Hz with effective policies in complex scenarios.
