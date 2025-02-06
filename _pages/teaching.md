---
layout: page
permalink: /teaching/
title: teaching
description: 
nav: true
nav_order: 7
---

## CS7170 Seminar in Artificial Intelligence: Frontier in AI for Science (Spring 2025)

* Time: Tuesday 11:45 am - 1:25 pm, Thursday 2:50 pm - 4:30 pm
* Location: Hastings Suite 113
* Lecturer: Wengong Jin
* Pre-requisites: N/A

### Course Description

This course provides an introduction of how Artificial Intelligence (AI) and Machine Learning (ML) techniques are transforming scientific discovery. Students will learn various deep learning architectures, such as graph neural networks, transformers, diffusion models, and explore how these models can be applied across scientific disciplines such as chemistry, biology, and material science. Students from non-CS disciplines are encouraged to attend.

### Course Deliverables

* Participation and Discussions (20%).
* Research frontier presentation (40%): present a list of papers related to a research topic in the field (~30min)
* Project presentation (40%): Present a project in any topic related to AI for science. If you are working on any research projects in the intersection of science and AI, you are welcome to present your existing research work (~30min)

### Schedule

Each class will cover a deep learning topic and demonstrate how it can be applied to different problems in scientific disciplines. The class is divided into two parts. The first part focuses on state-of-the-art AI methods and their applications in science, with the goal of helping students understand the current state of the field (AI in science). The second part focuses on research frontiers, with the goal of prompting students think about directions that may shape the future of this field. This part will be presentations from students or guest speakers. The class will end with a few project presentations.

| Date     | AI topics | Reading |
| -------- | ------- | ------- | ----------- |
| 1/7 | [Introduction](https://www.dropbox.com/scl/fi/6xnjrz69pixyx3bplebht/01-Introduction.pdf?rlkey=y4lf6zw2jdgg68mr5guqkb8q4&dl=0) | Miscellaneous | [Antibiotic discovery](https://www.cell.com/action/showPdf?pii=S0092-8674%2820%2930102-1); [Protein folding](https://www.nature.com/articles/s41586-021-03819-2); [Material design](https://www.nature.com/articles/s41586-023-06735-9);
| 1/9  | [Graph neural network I ](https://www.dropbox.com/scl/fi/innadlmjtodkovm653gwz/02-GNN.pdf?rlkey=bawc1g9v5tye812cifxo0v24n&dl=0)| Molecule/material property prediction | [MPNN](https://arxiv.org/abs/1704.01212); [GAT](https://arxiv.org/abs/1710.10903v3); [Chemprop](https://pubs.acs.org/doi/pdf/10.1021/acs.jcim.9b00237); [Crystal GCN](https://arxiv.org/pdf/1710.10324);
| 1/14 | [Graph neural network II](https://www.dropbox.com/scl/fi/ra2q2ve9plqeddgu3z9zr/03-GNN.pdf?rlkey=jsq6wog8s29n65485etjwltk4&dl=0)  | Molecule property prediction | [GNNExplainer](https://arxiv.org/pdf/1903.03894); [RationaleRL](https://proceedings.mlr.press/v119/jin20b/jin20b.pdf); [Pretraining GNN](https://cs.stanford.edu/people/jure/pubs/pretrain-iclr20.pdf)
| 1/16 | [Graph generation](https://www.dropbox.com/scl/fi/zg5f1509256evir7q34dg/04-Graph-Generation.pdf?rlkey=re811fkpd2hr0jg31mffjvt0a&dl=0)  | De novo drug design | [GraphRNN](https://arxiv.org/abs/1802.08773); [Junction Tree VAE](https://arxiv.org/abs/1802.04364);
| 1/21 | [Transformer I](https://www.dropbox.com/scl/fi/rm3uraxu9ztze11nz2y9v/05-Transformers.pdf?rlkey=ucirp2ppnf1mrlb90vp7vabtl&dl=0) | Protein language models | [ESM](https://www.pnas.org/doi/full/10.1073/pnas.2016239118); [ESM-3](https://www.biorxiv.org/content/10.1101/2024.07.01.600583v1)
| 1/23 | [Transformer II](https://www.dropbox.com/scl/fi/i9sd0hrx39r1tnfsk2aoq/06-SSM.pdf?rlkey=o2j3hdx5ystwx3rbugvi2dc4u&dl=0) | DNA language models | [MAMBA](https://arxiv.org/abs/2312.00752); [Evo](https://www.science.org/doi/10.1126/science.ado9336)
| 1/28 | [Equivariant neural networks I](https://www.dropbox.com/scl/fi/b8rt00kyvasquj8j5tgm4/07-ENN.pdf?rlkey=3v2uwawk49cxtl27xio017pbe&dl=0) | Molecular property prediction |
| 1/30 | [Equivariant neural networks II](https://www.dropbox.com/scl/fi/jqzp59zvkua25ooc747iv/08-MD.pdf?rlkey=v1qddbu5yewoqmppblrnpy7pz&dl=0) | Molecular dynamics|
| 2/4  | [Diffusion models I (Gaussian diffusion)](https://www.dropbox.com/scl/fi/y4xo8csqitzntojk1l1ie/09-Diffusion.pdf?rlkey=yhup70dr8v9tcvm7zlmgrawbp&dl=0) | Protein structure prediction |
| 2/6  | [Diffusion models II (Flow matching)](https://www.dropbox.com/scl/fi/ct79gjrrba0qtaj1is0qq/10-FM.pdf?rlkey=1l4yd04i4nxao2siosaiix13a&dl=0) | Protein structure prediction | 
| 2/11 | Diffusion models III (Discrete diffusion) | Protein design |
| 2/13 | Reinforcement learning I (PPO) | De novo drug design | 
| 2/18 | Reinforcement learning II (Monte Carlo tree search) | Chemical retrosynthesis |
| 2/20 | Self-supervised learning | Biomedical image analysis |
| 2/25 | Explainable AI | Miscellaneous |
| 2/27 | Project Proposal presentation  |
| 3/4-3/6  | Spring break (no class) |
| 3/11 | Guest Lecture: Wenhao Gao (MIT) | Chemistry |
| 3/13 | Research frontier presentation  | 
| 3/18 | Research frontier presentation  | 
| 3/20 | Research frontier presentation  |
| 3/25 | Research frontier presentation  |
| 3/27 | Guest Lecture: Kyle Swanson (Stanford) |
| 4/1  | Research frontier presentation | 
| 4/3  | Research frontier presentation | 
| 4/8  | Project presentation by students |
| 4/10 | Project presentation by students |
| 4/15 | Project presentation by students |


### Research frontier presentation: example topics
* Scalability: faster equivariant neural networks and diffusion models
* Interpretability: how to understand the rationale behind model predictions?
* Physics-informed neural networks: how to incorporate domain knowledge (e.g. biophysics and chemistry)?
* LLM agent: how to apply LLM agents to accelerate scientific discovery?
* Federated learning: how to share sensitive data for model training?
* Lab-in-the-loop learning: how to learn from experimental feedback?
* (More based on your interest)
