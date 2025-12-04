# A graph-based machine learning framework to assign empirical interaction parameters for novel molecules

## Presenting Author
Yao Fu

## Authors
Yao Fu, Martin Stroet, Megan O'Mara

## Abstract
Classical molecular dynamics (MD) is a widely adopted computational technique for investigating molecular interactions. The physics of atoms in a MD simulation is governed by a set of force fields parameters. While the force fields of common biomolecules are well-determined, novel molecules lack experimental data against which such parameters may be fitted. Due to this, obtaining accurate parameters for novel molecules is a major challenge. A common approach to this problem is to perform and fit against single point QM calculations such as DFT. However, this approach is both laborious and computationally expensive on a moderate to large scale. We propose here a graph-based machine learning framework for learning parameters from QM calculations. Our framework focuses on preserving physical interpretability as well as minimising overfitting. We show that the bonded parameters we obtain more closely align with experimental data than comparable QM calculations while being four OOMs faster.
