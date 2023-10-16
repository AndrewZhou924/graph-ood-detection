# Graph OOD Detection

A curated list of resources for OOD detection with graph data.  
If some related papers are missing, please contact us via pull requests :)

### Relation to the anomaly detection problem

Unlike traditional anomaly detection, which assumes a small percentage of anomalies, 
in the graph domain, the OOD part may contain nodes that are comparable in size to the ID part. 

(taken from "Learning on Graphs with Out-of-Distribution Nodes", KDD 2022)

Anomaly graphs are usually malicious samples from a real system and available during training; while OOD graphs are samples from the distribution that the model has not seen during training.

(taken from "A Data-centric Framework to Endow Graph Neural Networks with Out-Of-Distribution Detection Ability", KDD 2023)


## Recent works
### Graph-level OOD detection
KDD 2023. A Data-centric Framework to Endow Graph Neural Networks with Out-Of-Distribution Detection Ability.
[[paper]](http://shichuan.org/doc/150.pdf)
[[code]](https://github.com/BUPT-GAMMA/AAGOD)
>- Graph-level, post-hoc, training without outlier exposure.

WSDM 2023. GOOD-D: On Unsupervised Graph Out-Of-Distribution Detection
[[paper]](https://arxiv.org/pdf/2211.04208.pdf)
[[code]](https://github.com/yixinliu233/G-OOD-D)
>- Graph-level, Self-supervised contrastive learning.

🔥 NeurIPS 2022. GraphDE: A Generative Framework for Debiased Learning and Out-of-Distribution Detection on Graphs.
[[paper]](https://openreview.net/pdf?id=mSiPuHIP7t8)
[[code]](https://github.com/Emiyalzn/GraphDE)
>- Graph-level, Generative, Variational inference.

ICML workshop 2022. Towards OOD Detection in Graph Classification from Uncertainty Estimation Perspective.
[[paper]](https://arxiv.org/pdf/2206.10691.pdf)
>- Graph-level, Uncertainty estimation.

### Node-level OOD detection
🔥 ICLR 2023. Energy-based out-of-distribution detection for graph neural networks.
[[paper]](https://arxiv.org/pdf/2302.02914.pdf)
[[code]](https://github.com/qitianwu/GraphOOD-GNNSafe)
>- Node-level with two disconnected graphs, Energy-based score with pagerank-based propagation.

KDD 2022. Learning on Graphs with Out-of-Distribution Nodes.
[[paper]](https://dl.acm.org/doi/10.1145/3534678.3539457)
[[code]](https://github.com/SongYYYY/KDD22-OODGAT)
>- Node-level with inter-edges, Semi-supervised outlier detection, a modified GAT with three regularization terms.

NeurIPS 2021. Graph Posterior Network: Bayesian Predictive Uncertainty for Node Classification.
[[paper]](https://proceedings.neurips.cc/paper/2021/file/95b431e51fc53692913da5263c214162-Paper.pdf)
>- Node-level, Bayesian posterior.

NeurIPS 2020. Uncertainty Aware Semi-Supervised Learning on Graph Data.
[[paper]](https://proceedings.neurips.cc/paper/2020/file/968c9b4f09cbb7d7925f38aea3484111-Paper.pdf)
[[code]](https://github.com/zxj32/uncertainty-GNN)
>- Node-level, a Graph-based Kernel Dirichlet distribution Estimation (GKDE) method.

### Anomaly Detection
ICLR 2023 submission. Revisiting Uncertainty Estimation for Node Classification: New Benchmark and Insights
[[paper]](https://openreview.net/pdf?id=DB3BH3arU2Y)

NeurIPS 2022. Dual-discriminative Graph Neural Network for Imbalanced Graph-level Anomaly Detection.
[[paper]](https://openreview.net/pdf?id=d6mf9AFoR-O)
[[code]](https://github.com/graph-level-anomalies/iGAD)

🔥 ICML 2022. Rethinking Graph Neural Networks for Anomaly Detection.
[[paper]](https://proceedings.mlr.press/v162/tang22b/tang22b.pdf)
[[code]](https://github.com/squareRoot3/Rethinking-Anomaly-Detection)
>- Anomalies leads to the ‘right-shift’ of spectral energy.

IJCAI 2022. Raising the Bar in Graph-level Anomaly Detection.
[[paper]](https://arxiv.org/pdf/2205.13845.pdf)
[[code]](https://github.com/boschresearch/GraphLevel-AnomalyDetection)

WSDM 2022. Deep Graph-level Anomaly Detection by Glocal Knowledge Distillation.
[[paper]](https://arxiv.org/pdf/2112.10063.pdf)
[[code]](https://github.com/RongrongMa/GLocalKD)
>- Graph-level Anomaly Detection, Joint random distillation of graph and node representations with two GNNs (GLocalKD).

Big Data 2021. On Using Classification Datasets to Evaluate Graph Outlier Detection: Peculiar Observations and New Insights.
[[paper]](https://arxiv.org/pdf/2012.12931.pdf)
>- Graph-level, Propagation-based outlier detection method (OCGIN).

## Other resources
### OOD Generalization
- Arxiv 2022. Out-Of-Distribution Generalization on Graphs: A Survey.
[paper](https://arxiv.org/pdf/2202.07987.pdf)
- [THUMNLab/awesome-graph-ood](https://github.com/THUMNLab/awesome-graph-ood)
- [Out-Of-Distribution Generalization on Graphs: Paper List](https://graph.ood-generalization.com/)
