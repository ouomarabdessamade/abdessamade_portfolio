# Abdessamade portfolio

# [Project: Graph Neural Networks in Recommender Systems: A Comparative Study](https://github.com/ouomarabdessamade/LightGCN)

## Introduction
This project is a comparative study conducted during my master's program, where I explored the efficacy of various graph neural network approaches in recommendation systems. Specifically, I focused on methods that leverage the interaction between users and items to make recommendations, known as user-item collaborative filtering.

### Models Studied
- Graph Convolution Matrix Completion (GC-MC)
- Neural Graph Collaborative Filtering (NGCF)
- LightGCN
- UltraGCN

### Benchmark Datasets
- Gowalla Dataset
- Yelp2018 Dataset

## Work Environment
- Google Colab Pro +
  - GPU: T4 (15.0 GB), V100 (16.0 GB), A100 (40.0 GB)
- Kaggle GPU: P100

## Evaluation Metrics
- Recall@k: Computes the fraction of relevant items out of all relevant items.
- NDCG@k: Measures ranking quality, accounting for the position of the hit by assigning higher scores to hits at top ranks.

## Results
### Testing Performance
I conducted tests to compare the performance of the studied models.

### Accuracy-Diversity Comparison
I analyzed the models' performance with different values of k (5, 10, 30, 40, and 50) using Recall@k and NDCG@k.

### Training Efficiency of Models
I compared the training efficiency of the models, particularly in the Yelp2018 dataset, considering:
- Total training time
- Number of epochs required to achieve optimal performance

## Discussion
I discussed the advantages and limitations of each model, addressing issues such as oversmoothing problems. Additionally, I provided important conclusions to improve recommendations, especially for large-scale recommendation systems.
