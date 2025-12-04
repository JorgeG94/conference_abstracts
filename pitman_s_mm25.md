# Dual-purpose datasets: Benchmarking the formation energy of metal complexes for density functional theory and basis sets

## Presenting Author
Samuel Pitman

## Authors
Samuel J. Pitman, Laura K. McKemmish

## Abstract
Errors in simulations of transition-metal (TM) chemistry with density functional theory (DFT) and Gaussian basis sets remain poorly understood. Yet datasets of tens of thousands of DFT results are routinely used to train machine learning (ML) models for faster simulations. Without understanding the underlying model-chemistry errors and the multireference nature of TM complexes - potentially more significant than fitting error - ML accuracy is unclear, limiting applicability. To address this, we developed a medium-accuracy dataset of 30k TM complex energies using DLPNO-CCSD(T)/cc-pVDZ and a high accuracy, 150 TM formation energy dataset using DLPNO-CCSD(T)/CBS. This enables multi-fidelity ML training (few high-accuracy results plus many moderate-accuracy ones) and benchmarking of density functional approximations with multiple basis sets. These benchmarks provide error estimates for existing datasets (and ML models) and give model-chemistry recommendations for future dataset generation.
