---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "MAGIC-VFM - Meta Adaptive Control for Ground Vehicles with Visual Foundation Models"

authors:
- Elena Sorina Lupu
- Fengze Xie
- James A. Preiss
- Matthew Anderson
- Jedidiah Alindogan
- Soon-Jo Chung

date: 2024-01-24

publication_types: 
  - paper-conference

publication: "IEEE Transactions on Robotics"
publication_short: "TRO"

tags:
- robotics

featured: true

image:
  caption: ""
  focal_point: "smart"
  preview_only: false

projects: 
- linc

---

Planning and control of ground vehicles are challenging because of complex dynamic interactions with the terrain.  Therefore, accurate modeling of terrain interaction forces is important to optimize their driving performance.  We present an offline meta-learning algorithm to construct a rapidly-tunable model of residual dynamics and disturbance using both visual foundation models and vehicle states.  This model is then integrated with composite adaptive control for the control matrix to adapt to changes in both the terrain and vehicle dynamics conditions in real time.  We provide mathematical guarantees of stability and robustness for this controller that provides rapid adaptation for the last layer of the deep neural network, which encodes the terrain disturbance.  The effectiveness of our meta-adaptive algorithm is demonstrated through results of simulation and experimentation using a tracked vehicle.  In particular, the experimental results show its superior performance outdoors on different slopes with varying slippage and track degradation disturbances.  We also compare our controller against an adaptive controller that does not use the visual foundation model terrain features, thereby showing significant improvement over the baseline in both hardware experimentation and simulation.
