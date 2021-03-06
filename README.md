# Human Gut Microbiome Analysis
Code for __"Absence of enterotypes in the human gut microbiomes reanalyzed with non-linear dimensionality reduction method"__ paper (https://www.biorxiv.org/content/10.1101/2021.11.04.467087v1).
It is advised to run notebooks in the order mentioned below:

1. Preprocessing.ipynb
2. Intrinsic_dim_estimation.ipynb
3. Manifold_learning.ipynb
4. Autoencoders.ipynb
5. Clustering.ipynb

Synthetic_data.ipynb - generates simple synthetic dataset.  
Re-run the whole pipeline (1-5) for a synthetic dataset results (see the comments in notebooks).
Visualization_separate.ipynb - visualizes continuous specificity of the data points distribution.  
Visualization_merged.ipynb - demonstrates batch effect for merged AGP and HMP datasets.  

The data is available on figshare by DOI: 10.6084/m9.figshare.19091423
