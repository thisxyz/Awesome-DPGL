<div align="center">
  
# 🌟 Awesome-DPGL  
### **A Curated List of Differentially Private Graph Learning (DPGL)**

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![Stars](https://img.shields.io/github/stars/YOUR_NAME/Awesome-DPGL?style=flat&color=yellow)
![Last Commit](https://img.shields.io/github/last-commit/YOUR_NAME/Awesome-DPGL)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
</div>

---

**Abstract:** Graph learning has been widely applied across diverse domains, including social networks, recommendation systems, and bioinformatics. However, real-world graph data often contains highly sensitive information, raising serious privacy concerns. Differential Privacy (DP) has emerged as a rigorous mathematical framework to protect sensitive information in graph learning while providing formal privacy guarantees. This survey presents the first comprehensive and systematic review of Differentially Private Graph Learning (DPGL). We organize existing DPGL methods according to privacy granularity, learning paradigms, and perturbation mechanisms, analyze their respective strengths and limitations, and identify key technical challenges in the field. Furthermore, we identify future research directions critical for advancing DPGL toward practical deployment in real-world applications. This survey paper aims to provide a unified reference for researchers and practitioners while inspiring future innovations in privacy-preserving graph learning.

---

<img width="2282" height="1300" alt="image" src="https://github.com/user-attachments/assets/1741ed88-533b-4af4-8fff-7615a8dc074f" />


<img width="2052" height="1852" alt="image" src="https://github.com/user-attachments/assets/a62fd20d-5c95-4411-a50d-56c59c6b8e74" />



## 🧩 Node-level DP

 Title                                                                 | Venue                  | Year |
-----------------------------------------------------------------------|------------------------|------|
 [Node-level differentially private graph neural networks](https://arxiv.org/abs/2111.15521) |  PAIR2Struct (ICLR Workshop) | 2022 |
 [Releasing graph neural networks with differential privacy guarantees](https://arxiv.org/abs/2109.08907) | TMLR | 2023 |
 [GAP: Differentially private graph neural networks with aggregation perturbation](https://arxiv.org/abs/2203.00949) | USENIX Security | 2023 |
 [Differentially private decoupled graph convolutions for multigranular topology protection](https://arxiv.org/abs/2307.06422) | NeurIPS | 2023 |
[Preserving node-level privacy in graph neural networks](https://arxiv.org/abs/2311.06888) | S&P | 2024 |
[ProGAP: Progressive graph neural networks with differential privacy guarantees](https://arxiv.org/abs/2304.08928) | WSDM | 2024 |
[DPAR: Decoupled graph neural networks with node-level differential privacy](https://arxiv.org/abs/2210.04442) | WWW | 2024 |
[PrivIM: Differentially Private Graph Neural Networks for Influence Maximization](https://ieeexplore.ieee.org/document/11112938/) | ICDE | 2025 |
[Structure-Preference Enabled Graph Embedding Generation under Differential Privacy](https://arxiv.org/abs/2501.03451) | ICDE | 2025 |
[AdvSGM: Differentially Private Graph Learning via Adversarial Skip-gram Model](https://arxiv.org/abs/2503.21426) |  ICDE | 2025 |
[Differentially Private Adaptive Noise for Graph Neural Network in Online Social Networks](https://www.sciencedirect.com/science/article/pii/S1389128625007236) | Computer Networks | 2025 |
[Adversarial Signed Graph Learning with Differential Privacy](https://www.arxiv.org/abs/2512.00307) | KDD | 2026 |
[Convergent Privacy Framework with Contractive GNN Layers for Multi-hop Aggregations](https://arxiv.org/abs/2506.22727) | NDSS | 2026 |

---

## 🧩 Eode-level DP

 Title                                                                 | Venue                  | Year |
-----------------------------------------------------------------------|------------------------|------|
 [LinkTeller: Recovering Private Edges from Graph Neural Networks via Influence Analysis](https://arxiv.org/abs/2108.06504) | S&P | 2022 |
 [LPGNet: Link private graph networks for node classification](https://dl.acm.org/doi/abs/10.1145/3548606.3560705) | CCS | 2022 |
 [GAP: Differentially private graph neural networks with aggregation perturbation](https://arxiv.org/abs/2203.00949) | USENIX Security | 2023 |
 [Differentially private decoupled graph convolutions for multigranular topology protection](https://arxiv.org/abs/2307.06422) | NeurIPS | 2023 |
[ProGAP: Progressive graph neural networks with differential privacy guarantees](https://arxiv.org/abs/2304.08928) | WSDM | 2024 |
[Differentially private graph neural networks for link prediction](https://ieeexplore.ieee.org/document/10597978/) | ICDE | 2024 |
[Edge Private Graph Neural Networks with Singular Value Perturbation](https://arxiv.org/abs/2403.10995) | PETS | 2024 |
[GCON: Differentially private graph convolutional network via objective perturbation](https://arxiv.org/abs/2407.05034) |  ICDE | 2025 |
[Safeguarding Graph Neural Networks against Topology Inference Attacks](https://arxiv.org/abs/2509.05429) | CCS | 2025 |
[GRASP: Differentially private graph reconstruction defense with structured perturbation](https://dl.acm.org/doi/10.1145/3711896.3736992) | KDD | 2025 |
[Convergent Privacy Framework with Contractive GNN Layers for Multi-hop Aggregations](https://arxiv.org/abs/2506.22727) | NDSS | 2026 |

---

## 🧩 Graph-level DP

 Title                                                                 | Venue                  | Year |
-----------------------------------------------------------------------|------------------------|------|
 [Differentially Private Graph Neural Networks for Whole-Graph Classification](https://ieeexplore.ieee.org/abstract/document/9980390/) | TPAMI | 2022 |
[Differentially private graph neural networks for graph classification and its adaptive optimization](https://www.sciencedirect.com/science/article/pii/S0957417424026654) | ESWA | 2025 |
[A semi-supervised privacy-preserving graph classification framework enhanced by graph contrastive learning](https://www.sciencedirect.com/science/article/pii/S0957417425037649) | ESWA | 2025 |
[DPRO-GNN: Bridging differential privacy and advanced optimization for privacy-preserving graph learning](https://www.sciencedirect.com/science/article/abs/pii/S002002552500828X) | Information Sciences | 2025 |

---


## 🧩 Local Setting

| Title                                                                 | Venue                  | Year |
|-----------------------------------------------------------------------|------------------------|------|
| [Locally private graph neural networks](https://dl.acm.org/doi/abs/10.1145/3460120.3484565) | CCS | 2021 |
| [Towards private learning on decentralized graphs with local differential privacy](https://ieeexplore.ieee.org/abstract/document/9855440/) | TIFS | 2022 |
| [Gromov-wasserstein discrepancy with local differential privacy for distributed structural graphs](https://www.ijcai.org/proceedings/2022/294) | IJCAI | 2022 |
| [Privacy-enhanced graph neural network for decentralized local graphs](https://ieeexplore.ieee.org/abstract/document/10305592/) | TIFS | 2023 |
| [Blink: link local differential privacy in graph neural networks via Bayesian estimation](https://dl.acm.org/doi/abs/10.1145/3576915.3623165) | CCS | 2023 |
| [Individual fairness for local private graph neural network](https://www.sciencedirect.com/science/article/pii/S095070512300240X) | KBS | 2023 |
| [Locally differentially private graph learning on decentralized social graph](https://www.sciencedirect.com/science/article/pii/S0950705124011225) | KBS | 2024 |
[Towards differential privacy in sequential recommendation: A noisy graph neural network approach](https://arxiv.org/abs/2309.11515) | TKDD | 2024 |
| [Degree-preserving randomized response for graph neural networks under local differential privacy](https://arxiv.org/abs/2202.10209) | TDP | 2024 |
| [Local differential privacy in graph neural networks: a reconstruction approach](https://epubs.siam.org/doi/abs/10.1137/1.9781611978032.1) | SDM | 2024 |
| [LinkGuard: Link Locally Privacy-Preserving Graph Neural Networks with Integrated Denoising and Private Learning](https://dl.acm.org/doi/abs/10.1145/3589335.3651533) | WWW | 2024 |
| [Privacy-Preserving Graph Embedding based on Local Differential Privacy](https://dl.acm.org/doi/abs/10.1145/3627673.3679759) | CIKM | 2024 |
| [GraphPrivatizer: Improved Structural Differential Privacy for Graph Neural Networks](https://openreview.net/forum?id=lcPtUhoGYc) | TMLR | 2024 |
[Achieving Personalized Privacy-Preserving Graph Neural Network via Topology Awareness](https://dl.acm.org/doi/10.1145/3696410.3714555) | WWW | 2025 |
| [Leveraging Homophily Under Local Differential Privacy for Effective Graph Neural Networks](https://link.springer.com/chapter/10.1007/978-3-032-06096-9_22) | ECML-PKDD | 2025 |
| [Going Deeper into Locally Differentially Private Graph Neural Networks](https://openreview.net/forum?id=2aKHuXdr7Q) | ICML | 2025 |
| [Devil's Hand: Data Poisoning Attacks to Locally Private Graph Learning Protocols](https://arxiv.org/abs/2506.09803) | KDD | 2026 |
