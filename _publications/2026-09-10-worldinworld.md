---
title: "World in World: Explore the World with World Models"
collection: publications
category: manuscripts
permalink: /publication/2026-worldinworld
excerpt: 'A training-free inference-time interface that turns heterogeneous control evidence into camera- and time-labelled visual states, read through the native self-attention of a frozen causal video world model.'
date: 2026-09-10
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/abs/2609.11548'
citation: 'C Song, Y Yang, C Zhang. (2026). &quot;World in World: Explore the World with World Models.&quot; <i>arXiv preprint arXiv:2609.11548</i>.'
---

World in World is a training-free inference-time interface for controllable exploration with frozen autoregressive video world models. It converts heterogeneous control evidence -- source-video observations, target-view scene projections, geometry renderings that complete newly exposed regions, and retrieved generated states beyond the rolling cache -- into camera- and time-labelled clean visual states. A correspondence router combines persistent point identities with geometry to establish token correspondences, and evidence-wise attention CFG independently regulates each auxiliary channel using attention responses from the same denoising forward pass. The shared interface supports camera-controlled rerendering, long-horizon revisiting, and human-motion transfer with the same frozen backbone.

[Project Page](https://chenxi-song.github.io/worldinworld/) \| [PDF](https://arxiv.org/abs/2609.11548) \| [Code](https://github.com/Westlake-AGI-Lab/WorldinWorld)
