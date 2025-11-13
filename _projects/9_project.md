---
layout: page
title: People You May Know
description: Production-ready friend recommendation system
img:
importance: 3
category: Misc.
---

<p align="justify">A production-ready friend recommendation system designed for medium-scale networks (100K-1M users). The system implements graph-based algorithms to suggest potential connections, leveraging concepts from "Machine Learning System Design Interview" by Ali Aminian and Alex Xu. Uses NetworkX for friend-of-friend candidate generation with intelligent pruning.</p>

<p align="justify">Features multiple ranking models including rule-based (V1), ML-based simulating gradient boosting (V2), and ensemble methods. Built with FastAPI REST API achieving sub-100ms latency with LRU caching. Evaluated on real Stanford SNAP Facebook dataset (4,039 users) using metrics including Precision@K, Recall@K, NDCG, and MRR. The V2 model achieves 14.7% precision@10 with 18ms latency. Implements advanced ensemble approaches including weighted combination and Reciprocal Rank Fusion (RRF) across five different algorithms.</p>

Implementation of entire project can be found here: <a href="https://github.com/skala3/people-you-may-know"> Code </a>
