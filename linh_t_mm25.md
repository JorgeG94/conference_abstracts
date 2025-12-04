# Expanding the scalability of graph neural network for ab initio molecular dynamics simulations 

## Presenting Author

Thuy Linh La 

## Authors 

Thuy Linh La, Yugam Aggarwal, Truyen Tran, Svetha Venka, Sherif Abdulkader Tawfik 

## Abstract 

Classical molecular dynamics (MD) efficiently simulates system
behaviour under ambient conditions using classical force fields that
scale well with system size. When quantum-level accuracy is required,
ab initio MD (AIMD) is employed, but its computational expense limits
accessible spatial and temporal scales. Recently, graph neural network
(GNN) models, such as M3Gnet and DeePMD, have emerged to replace
costly ab initio calculations with machine learning surrogates. GNNs
represent molecular structures as graphs, encoding atomic interactions
through message-passing schemes, aspiring to achieve AIMD accuracy
at classical MD efficiency. However, input structure size presents a
significant training limitation, as graphs capturing physical properties
scale with structural complexity. This work examines scalability
challenges in training GNN models and proposes structural pruning
methods to improve their scalability.
