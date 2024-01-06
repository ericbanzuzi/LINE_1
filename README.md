# LINE-1

This repository aims to reproduce the LINE-1 method as originally presented in the paper titled "LINE: Large-scale Information Network Embedding" [2]. The aim was to use the method and try to replicate some of the results obtained in the paper titled "A Comparative Study for Unsupervised Network Representation Learning"[1]. The model was used for two tasks: Node Classification and Link Prediction.

## Files Overview

### 1. LINE_1_part1.ipynb
- Step-by-step development process of the LINE-1 model while testing it on a small sample data (Karate Club Network)
- Contains code for the prediction tasks
- Includes Node Classification and Link Prediction experiments on BlogCatalog, Pubmed and Cora datasets.


### 2. LINE_1_part2.ipynb
- Contains the code for LINE-1 and prediction tasks
- Includes Node Classification and Link Prediction experiments on BlogCatalog, Pubmed and Cora datasets.

### 3. LINE_1_additional_datasets.ipynb
- Contains the code for LINE-1 and prediction tasks
- Includes Node Classification and Link Prediction experiments on Amazon-Rating and Cora datasets.

### Experiments
For each data set, the model was used to produce a 128-dimensional embedding with Graph information. The embeddings were trained for 1 billion edge samples using $s = 5$ negative samples and a starting learning rate $\rho_0 = 0.025$ that was updated as $\rho_t = \rho_0(1-t/T)$, where $T$ is the total of edge samples.


## References
[1] M. Khosla, V. Setty, and A. Anand, “A comparative study for unsupervised network representation learning,” IEEE Transactions on Knowledge and Data Engineering, vol. 33, no. 5, pp. 1807–1818, 2019.

[2] J. Tang, M. Qu, M. Wang, M. Zhang, J. Yan, and Q. Mei, “Line: Large-scale information network embedding,” 2015.

