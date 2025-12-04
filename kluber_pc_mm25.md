# Density-based Atomistic Transformer Machine Learning (DAT-ML)

## Presenting Author
Physics Claire Kluber

## Authors
Physics Claire Kluber

## Abstract
Interaction energy prediction, or more broadly lattice energy prediction, is a problem central to computational chemistry. In this work, we create an atomistic transformer model that learns interaction energies for both neutral and charged systems. We develop DAT-ML as a new approach to interaction energy prediction based on the deformation electron density of interacting monomers. By incorporating transformer subnetworks for both unique elements and monomer charges,  the model can learn the same physics for neutral and charged monomers, using S66 (neutral) and IL174 (charged) as model datasets. In our preliminary work, we achieve a test MAE of 0.3 kcal/mol and RMSE of 0.8 kcal/mol, indicating that the model surpasses the 1.0 kcal/mol threshold of chemical accuracy. Ultimately, DAT-ML paves the way to more speedy, accurate, stable, and scalable interaction energy prediction, and is the first step in a machine learning approach to the many-body expansion.
