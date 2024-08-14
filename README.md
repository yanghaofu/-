
### 图网络
- [x] HGNN
- [ ] GCN
- [ ] GAT
- [ ] GraphSAGE
- [ ] GAE
- [x] Cross-links Matter for Link Prediction: Rethinking the Debiased GNN from a Data Perspective


#### Cross-links
本文解决了基于图神经网络（GNN）的**链接预测中存在的偏差问题**，特别关注节点簇间的偏差，即所谓的交叉链接。研究发现现有的GNN模型在处理同一簇内部链接和交叉链接时存在严重的数据偏差。为了解决这些问题，论文提出了一种双GNN框架，可以有效减少偏差，并在端到端的方式下提升模型效用。**具体方法是生成去偏置的节点嵌入，并将其与原始GNN嵌入融合，通过增强的监督信号和动态训练策略来实现**。
这篇文章提醒浅薄的我从本质的角度看待问题，之前的很多工作都是想着怎么从模型的角度提高精度，但是某些具体问题还是得抓住本质，就像本文从监督增强的角度考虑，取得了很好的效果。美中不足，还需要不少理论支支撑来证明方法的有效性。


### 智能合约
- [x] Improving Smart Contract Security with Contrastive Learning-based Vulnerability Detection
