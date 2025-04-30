# Contrastive Principal Component Analysis (cPCA)

This repository contains a complete reproduction and extension of the results from the paper:

**Abid, A., Zhang, M. J., Bagaria, V. K., & Zou, J. (2018).**  
*Exploring patterns enriched in a dataset with contrastive principal component analysis*.  
_Nature Communications, 9(1), 2134._  
[DOI: 10.1038/s41467-018-04608-8](https://doi.org/10.1038/s41467-018-04608-8)

## Overview

Contrastive PCA (cPCA) is an unsupervised learning method that identifies patterns unique to a target dataset relative to a background dataset. This repository includes:

- Code to reproduce synthetic and real-world results from the paper.
- Visualizations for different contrast parameters \(\alpha\).
- Comparison of cPCA with other dimensionality reduction techniques (e.g., PCA, LDA, ICA).
- Kernel extension of cPCA.
- Automatic selection of \(\alpha\).
- Reimplementation of figures using Python.

## Contents

- `data/`: Cleaned/preprocessed datasets (e.g., mice protein expression).
- `cpca/`: Implementation of cPCA and kernel cPCA.
- `README.md`: This file.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/Dhruban/cpca_601.git
   cd cpca_601
   
