<div align="center">

# 🌟 Awesome-DPGL  
### **A Curated List of Differential Privacy in Graph Learning (DPGL)**

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![Stars](https://img.shields.io/github/stars/YOUR_NAME/Awesome-DPGL?style=flat&color=yellow)
![Last Commit](https://img.shields.io/github/last-commit/YOUR_NAME/Awesome-DPGL)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

---

**Differential Privacy × Graph Machine Learning**

An up-to-date, high-quality collection of papers, surveys, benchmarks, tools, and resources in **Differential Privacy Graph Learning (DPGL)** — covering Local DP, Global DP, private GNNs, structure perturbation, node feature privacy, private graph embeddings, attacks & defenses, and theoretical foundations.

</div>

---

# 📑 Table of Contents
- [Introduction](#introduction)
- [Surveys](#surveys)
- [Fundamentals of Differential Privacy](#fundamentals-of-differential-privacy)
- [Local Differential Privacy for Graphs](#local-differential-privacy-for-graphs)
- [Global Differential Privacy for Graphs](#global-differential-privacy-for-graphs)
- [DP Graph Neural Networks](#dp-graph-neural-networks)
- [DP for Node Classification](#dp-for-node-classification)
- [DP Graph Embedding](#dp-graph-embedding)
- [Privacy Attacks](#privacy-attacks)
- [Defense Mechanisms](#defense-mechanisms)
- [Benchmarks & Datasets](#benchmarks--datasets)
- [Code Implementations](#code-implementations)
- [Contributing](#contributing)
- [Citation](#citation)

---

# 🔍 Introduction

**Differential Privacy Graph Learning (DPGL)** aims to protect sensitive information in graph data during training, inference, and publication.

This repository highlights:

- 📘 *Local DP (LDP)* on nodes, edges, and features  
- 🧠 Differentially private GNN architectures  
- 🔐 Private message passing, aggregation, and propagation  
- 🛡 Privacy-preserving graph representation learning  
- ⚔ Privacy attacks on DP graph systems  
- 📊 Benchmarks and real-world datasets  
- 🧮 Theoretical foundations  

The list is continuously updated. **Pull Requests are welcome!**

---

# 📘 Surveys

- **Graph Privacy Survey** – A comprehensive overview of privacy in graph ML  
- **Differential Privacy: Theory & Applications** – Classical DP overview  
- **Local Differential Privacy in ML** – Mechanisms & applications  
- **Privacy in Graph Neural Networks** – Specific to GNN privacy risks  

(欢迎补充)

---

# 🔐 Fundamentals of Differential Privacy

### Classical DP
- Dwork & Roth, *The Algorithmic Foundations of Differential Privacy*, 2014  
- Gaussian Mechanism  
- Laplace Mechanism  
- Composition Theorems  

### Local Differential Privacy (LDP)
- Piecewise Mechanism (PM)
- Marginal-Based Mechanism (MB)
- Subspace Walk (SW)
- Unary Encoding / Local Hashing (LH)

---

# 🧩 Local Differential Privacy for Graphs

### Node-feature LDP
- Methods applying LDP to node attributes before model training  

### Structural LDP
- Local DP for edges / adjacency perturbation  
- LDP-based graph anonymization and topology obfuscation  

### Private message passing (LDP × GNN)
- Works that introduce noise in propagation / aggregation  
- Private Laplacian smoothing  
- LDP-based neighborhood sampling  

---

# 🧠 DP Graph Neural Networks

### DP-GNN Families
- Gradient-level DP (DP-SGD for GNNs)  
- Model-level DP  
- Feature-aggregation DP  
- Structure-aware DP GNNs  

### Representative Works  
- DP-GCN  
- DP-GraphSAGE  
- DP-GAT  
(请补充具体论文信息)

---

# 🧬 DP for Node Classification

- LDP node feature perturbation methods  
- DP-SGD applied to node classification  
- Private label prediction  
- Private semi-supervised graph learning  

---

# 🔷 DP Graph Embedding

- DP random walk–based embeddings  
- DP matrix factorization  
- DP graph representation learning  
- Local DP embedding release  
- Private PPR (Personalized PageRank) embedding  

---

# ⚔ Privacy Attacks

### Inference Attacks
- Node attribute inference  
- Link prediction attacks  
- Membership inference attacks on GNNs  

### Poisoning Attacks
- Fake node injection under DP  
- Graph perturbation to cause DP degradation  
- Local DP–aware poisoning strategies  

### DP-breaking Attacks
- Attacks exploiting noise correlation  
- Reconstruction attacks on DP-protected graphs  

---

# 🛡 Defense Mechanisms

- Certified robustness with DP  
- Noise optimization and adaptive mechanisms  
- Graph sanitization  
- Defense against inference & poisoning attacks  
- Privacy budget allocation strategies  

---

# 📊 Benchmarks & Datasets

Public graph datasets widely used in DPGL experiments:

- Cora / Citeseer / PubMed  
- OGB datasets (ogbn-arxiv, ogbn-products, …)  
- Facebook / Twitter subgraphs  
- Amazon / Yelp graph datasets  
- Synthetic DP graph generators  

---

# 💻 Code Implementations

Open-source implementations of DP graph learning algorithms:

