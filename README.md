# ***Data Embedding Experiments with t-SNE, MDS and PCA***

## Overview
This project explores various data embedding techniques, including t-SNE, MDS, and PCA, applied to the Small Digits and Fashion MNIST datasets.

[This exercise](#exercise-t-sne) was assigned by the professor of the Machine Learning course at Sapienza University of Rome.

## Table of Contents
- [Project Description](#project-description)
- [Datasets](#datasets)
- [Methods](#methods)
- [Requirements](#requirements)
- [References](#references)
- [Original Exercise](#exercise-t-sne)

## Project Description
The project focuses on:
1. Understanding and applying different dimensionality reduction techniques.
2. Visualizing the data to discern patterns and clusters.
3. Comparing the performance and outcomes of t-SNE, MDS, and PCA.
4. Experimenting same tecniques using different parameters

## Datasets
- **Small Digits Dataset**
- **Fashion MNIST Dataset**

## Methods
1. **t-SNE** t-Distributed Stochastic Neighbor Embedding
2. **MDS** Multidimensional Scaling
3. **PCA** Principal Component Analysis


## Requirements
You can install the required libraries using:
```
pip install -r requirements.txt
```

## References
Used images and some experiments ideas comes from: https://distill.pub/2016/misread-tsne/


---

# **EXERCISE: t-SNE**

_**NOTE: The 3 best solutions will get +1 point to the final grade!**_

We are now 2/3 through the ML course -- it's time to prove yourself a worthy ML practitioner! 🤓

Your task is to fill in this Section. In particular:

- Use markdown and code cells, as if you are writing this part of the notebook for your own students!
- You can use Scikit-learn's implementation of t-SNE, your own, or whatever you prefer.

The Section should include _at least_ the following experiments:

- Embed the small digit data into 2D using t-SNE.
- Embed the small digit data into 3D using t-SNE.
- Comment on the differences you observe between the two plots.
- Comment on the differences you observe with PCA and MDS embeddings in the same target space.
- Embed a _larger_ dataset into 2D using t-SNE, e.g. MNIST, or character emojis, or pokemon images... you choose it!
- Add whatever you think it's worth adding. If you think a t-SNE parameter needs further discussion, or some other aspect is worth discussing, feel free to do it!

Send me your notebooks via email. Participation is not mandatory.

---