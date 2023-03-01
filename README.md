# Awesome Graph OOD Detection

## The research problem

### Definition

TODO: we need to give a formal definition to the node/link/graph-level OOD detection problem.

### Relation with the anomaly detection problem

Unlike traditional anomaly detection which assumes a small percentage of anomalies, 
in the graph domain, 
the OOD part may contain nodes that are comparable in size to the ID part. 

(taken from Learning on Graphs with Out-of-Distribution Nodes, KDD 2022)


## Recent works
ICLR 2023. ENERGY-BASED OUT-OF-DISTRIBUTION DETECTION FOR GRAPH NEURAL NETWORKS.
[[paper]](https://arxiv.org/pdf/2302.02914.pdf)
[[code]](https://github.com/qitianwu/GraphOOD-GNNSafe)
>- Node-level with two disconnected graphs, Energy-based score with pagerank-based propagation.

WSDM 2023. GOOD-D: On Unsupervised Graph Out-Of-Distribution Detection
[[paper]](https://arxiv.org/pdf/2211.04208.pdf)
[[code]](https://github.com/yixinliu233/G-OOD-D)
>- Node-level, Self-supervised contrastive learning.

NeurIPS 2022. GraphDE: A Generative Framework for Debiased Learning and Out-of-Distribution Detection on Graphs.
[[paper]](https://openreview.net/pdf?id=mSiPuHIP7t8)
[[code]](https://github.com/Emiyalzn/GraphDE)
>- Graph-level, Generative, Variational inference.

KDD 2022. Learning on Graphs with Out-of-Distribution Nodes.
[[paper]](https://dl.acm.org/doi/10.1145/3534678.3539457)
>- Node-level with inter-edges, Semi-supervised outlier detection.

ICML workshop 2022: Towards OOD Detection in Graph Classification from Uncertainty Estimation Perspective.
[[paper]](https://arxiv.org/pdf/2206.10691.pdf)
>- Graph-level, Uncertainty estimation.


## Other resources
### OOD Generalization
- Arxiv 2022. Out-Of-Distribution Generalization on Graphs: A Survey.
[paper](https://arxiv.org/pdf/2202.07987.pdf)
- [THUMNLab/awesome-graph-ood](https://github.com/THUMNLab/awesome-graph-ood)
- [Out-Of-Distribution Generalization on Graphs: Paper List](https://graph.ood-generalization.com/)
