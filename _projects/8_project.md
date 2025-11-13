---
layout: page
title: Super Mario RL Agent
description: Deep Q-Network agent to complete Super Mario Bros
img:
importance: 2
category: Misc.
---

<p align="justify">A Deep Q-Network (DQN) agent trained to complete Super Mario Bros World 1-1. The project implements advanced reinforcement learning techniques including Double DQN, prioritized experience replay, and target networks. The agent achieved 25 successful level completions during training with a 5% completion rate during evaluation.</p>

<p align="justify">Built with PyTorch and gym-super-mario-bros environment. Features custom preprocessing with frame stacking (4 frames), grayscale conversion, and 84x84 resizing. Includes reward shaping to encourage forward progress and epsilon-decay exploration strategy. Training was conducted over 10,000 episodes (6-8 hours on GPU) with checkpoint saving every 100 episodes. Interestingly, the model requires approximately 15% exploration at test time to avoid local optima and achieve consistent level completion.</p>

Implementation of entire project can be found here: <a href="https://github.com/skala3/super-mario-rl-agent"> Code </a>
