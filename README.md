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

<img width="2062" height="1200" alt="image" src="https://github.com/user-attachments/assets/9b6a36de-4c73-4ddf-9c7e-55b8c6947536" />


<img width="1698" height="1528" alt="image" src="https://github.com/user-attachments/assets/d675644e-054d-47a9-95dc-f4196aa9667e" />

## 🧩 Node-level DP

ID | Title                                                                 | Venue                  | Year |
-|-----------------------------------------------------------------------|------------------------|------|
1| [LinkTeller: Recovering Private Edges from Graph Neural Networks via Influence Analysis](https://arxiv.org/abs/2108.06504) | SP | 2022 |
2| [Training Differentially Private Graph Neural Networks with Random Walk Sampling](https://arxiv.org/abs/2301.00738) | TSRML (NeurIPS Workshop) | 2022 |
3| [Node-level differentially private graph neural networks](https://arxiv.org/abs/2111.15521) |  PAIR2Struct (ICLR Workshop) | 2022 |
4| [Differentially Private Graph Neural Networks for Whole-Graph Classification](https://ieeexplore.ieee.org/abstract/document/9980390/) | TPAMI | 2022 |
5| [LPGNet: Link private graph networks for node classification](https://dl.acm.org/doi/abs/10.1145/3548606.3560705) | CCS | 2022 |
6| [Releasing graph neural networks with differential privacy guarantees](https://arxiv.org/abs/2109.08907) | TMLR | 2023 |
7| [GAP: Differentially private graph neural networks with aggregation perturbation](https://arxiv.org/abs/2203.00949) | USENIX Security | 2023 |
8| [Differentially private decoupled graph convolutions for multigranular topology protection](https://arxiv.org/abs/2307.06422) | NeurIPS | 2023 |
9| [Differentially Private Graph Neural Networks for Medical Population Graphs and The Impact of The Graph Structure](https://ieeexplore.ieee.org/abstract/document/10635840) | ISBI | 2024 |
10| [Preserving node-level privacy in graph neural networks](https://arxiv.org/abs/2311.06888) | SP | 2024 |
11| [Poincaré differential privacy for hierarchy-aware graph embedding](https://arxiv.org/abs/2312.12183) | AAAI | 2024 |
12| [ProGAP: Progressive graph neural networks with differential privacy guarantees](https://arxiv.org/abs/2304.08928) | WSDM | 2024 |
13| [DPAR: Decoupled graph neural networks with node-level differential privacy](https://arxiv.org/abs/2210.04442) | WWW | 2024 |
14| [Differentially private graph neural networks for link prediction](https://ieeexplore.ieee.org/document/10597978/) | ICDE | 2024 |
15| [Towards differential privacy in sequential recommendation: A noisy graph neural network approach](https://arxiv.org/abs/2309.11515) | TKDD | 2024 |
16| [Edge Private Graph Neural Networks with Singular Value Perturbation](https://arxiv.org/abs/2403.10995) | PETS | 2024 |
17| [Leveraging Graph Clustering for Differentially Private Graph Neural Networks](https://ieeexplore.ieee.org/document/10825799/) | BigData | 2024 |
18| [NAGG: Noised graph node feature aggregations for preserving privacy](https://www.computer.org/csdl/proceedings-article/trustcom/2024/062000b389/25DI0aiYmQg) | TrustCom | 2024 |
19| [Differentially private graph neural networks for graph classification and its adaptive optimization](https://www.sciencedirect.com/science/article/pii/S0957417424026654) | ESWA | 2025 |
20| [Achieving Personalized Privacy-Preserving Graph Neural Network via Topology Awareness](https://dl.acm.org/doi/10.1145/3696410.3714555) | WWW | 2025 |
21| [PrivIM: Differentially Private Graph Neural Networks for Influence Maximization](https://ieeexplore.ieee.org/document/11112938/) | ICDE | 2025 |
22| [Structure-Preference Enabled Graph Embedding Generation under Differential Privacy](https://arxiv.org/abs/2501.03451) | ICDE | 2025 |
23| [GCON: Differentially private graph convolutional network via objective perturbation](https://arxiv.org/abs/2407.05034) |  ICDE | 2025 |
24| [AdvSGM: Differentially Private Graph Learning via Adversarial Skip-gram Model](https://arxiv.org/abs/2503.21426) |  ICDE | 2025 |
25| [A semi-supervised privacy-preserving graph classification framework enhanced by graph contrastive learning](https://www.sciencedirect.com/science/article/pii/S0957417425037649) | ESWA | 2025 |
26| [Safeguarding Graph Neural Networks against Topology Inference Attacks](https://arxiv.org/abs/2509.05429) | CCS | 2025 |
27| [GRASP: Differentially private graph reconstruction defense with structured perturbation](https://dl.acm.org/doi/10.1145/3711896.3736992) | KDD | 2025 |
28| [Hiding in the Network: Attribute-Oriented Differential Privacy for Graph Neural Networks](https://ieeexplore.ieee.org/document/11104233/) | TIFS | 2025 |
29| [PrivAGM: Secure Construction of Diferentially Private Directed Atributed Graph Models on Decentralized Social Graphs](https://dl.acm.org/doi/10.14778/3749646.3749722) | VLDB | 2025 |
30| [Differentially Private Adaptive Noise for Graph Neural Network in Online Social Networks](https://www.sciencedirect.com/science/article/pii/S1389128625007236) | Computer Networks | 2025 |
31| [Public data-enhanced multi-stage differentially private graph neural networks](https://www.sciencedirect.com/science/article/pii/S2214212625000237) | JISA | 2025 |
32| [HDAGAP: Hierarchical Deep Adaptive Graph Neural Networks Based on Aggregation Perturbation Differential Privacy](https://ieeexplore.ieee.org/document/11033647/) | CSCWD | 2025 |
33| [DPRO-GNN: Bridging differential privacy and advanced optimization for privacy-preserving graph learning](https://www.sciencedirect.com/science/article/abs/pii/S002002552500828X) | Information Sciences | 2025 |
34| [Adversarial Signed Graph Learning with Differential Privacy](https://www.arxiv.org/abs/2512.00307) | KDD | 2026 |
35| [Convergent Privacy Framework with Contractive GNN Layers for Multi-hop Aggregations](https://arxiv.org/abs/2506.22727) | NDSS | 2026 |

---

# 🧩 Local Setting

| Title                                                                 | Venue                  | Year |
|-----------------------------------------------------------------------|------------------------|------|
| [Locally private graph neural networks](https://dl.acm.org/doi/abs/10.1145/3460120.3484565) | CCS | 2021 |
| [Towards private learning on decentralized graphs with local differential privacy](https://ieeexplore.ieee.org/abstract/document/9855440/) | TIFS | 2022 |
| [Gromov-wasserstein discrepancy with local differential privacy for distributed structural graphs](https://www.ijcai.org/proceedings/2022/294) | IJCAI | 2022 |
| [Heterogeneous Randomized Response for Differential Privacy in Graph Neural Networks](https://arxiv.org/abs/2211.05766) | BigData | 2022 |
| [Privacy-enhanced graph neural network for decentralized local graphs](https://ieeexplore.ieee.org/abstract/document/10305592/) | TIFS | 2023 |
| [Blink: link local differential privacy in graph neural networks via Bayesian estimation](https://dl.acm.org/doi/abs/10.1145/3576915.3623165) | CCS | 2023 |
| [Individual fairness for local private graph neural network](https://www.sciencedirect.com/science/article/pii/S095070512300240X) | KBS | 2023 |
| [Privacy-preserving decentralized inference with graph neural networks in wireless networks](https://ieeexplore.ieee.org/abstract/document/10140175/) | TWC | 2023 |
| [Locally differentially private graph learning on decentralized social graph](https://www.sciencedirect.com/science/article/pii/S0950705124011225) | KBS | 2024 |
| [Degree-preserving randomized response for graph neural networks under local differential privacy](https://arxiv.org/abs/2202.10209) | TDP | 2024 |
| [Local differential privacy in graph neural networks: a reconstruction approach](https://epubs.siam.org/doi/abs/10.1137/1.9781611978032.1) | SIAM | 2024 |
| [LinkGuard: Link Locally Privacy-Preserving Graph Neural Networks with Integrated Denoising and Private Learning](https://dl.acm.org/doi/abs/10.1145/3589335.3651533) | WWW (Companion) | 2024 |
| [Locally and Structurally Private Graph Neural Networks](https://dl.acm.org/doi/abs/10.1145/3624485) | DTRAP | 2024 |
| [Achieving Adaptive Privacy-Preserving Graph Neural Networks Training in Cloud Environment](https://ieeexplore.ieee.org/document/10761771/) | ICICN | 2024 |
| [Privacy-Preserving Graph Embedding based on Local Differential Privacy](https://dl.acm.org/doi/abs/10.1145/3627673.3679759) | CIKM | 2024 |
| [GraphPrivatizer: Improved Structural Differential Privacy for Graph Neural Networks](https://openreview.net/forum?id=lcPtUhoGYc) | JMLR | 2024 |
| [Leveraging Homophily Under Local Differential Privacy for Effective Graph Neural Networks](https://link.springer.com/chapter/10.1007/978-3-032-06096-9_22) | ECML-PKDD | 2025 |
| [Going Deeper into Locally Differentially Private Graph Neural Networks](https://openreview.net/forum?id=2aKHuXdr7Q) | ICML | 2025 |
| [Devil's Hand: Data Poisoning Attacks to Locally Private Graph Learning Protocols](https://arxiv.org/abs/2506.09803) | KDD | 2026 |


---

# 📊 Benchmarks & Datasets

Public graph datasets widely used in DPGL experiments:

- Cora / Citeseer / PubMed  
- OGB datasets (ogbn-arxiv, ogbn-products, …)  
- Facebook / Twitter subgraphs  
- Amazon / Yelp graph datasets  
- Synthetic DP graph generators  



