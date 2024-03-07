# Abdessamade portfolio

# [Project: Graph Neural Networks in Recommender Systems: A Comparative Study](https://github.com/ouomarabdessamade/LightGCN)

This project presents a comparative study of various graph neural network-based approaches in recommender systems. The study focuses on models utilizing user-item interaction graphs for recommendations, specifically in user-item collaborative filtering.

## Models Studied
1. Graph Convolution Matrix Completion (GC-MC)
2. Neural Graph Collaborative Filtering (NGCF)
3. LightGCN : Simplifying and Powering Graph Convolution Network for Recommendation
4. UltraGCN : Ultra Simplification of Graph Convolutional Networks for Recommendation

## Datasets
The study utilizes two benchmark datasets:
1. Gowalla Dataset
2. Yelp2018 Dataset

## Work Environment
- Google Colab Pro +:
  - GPU T4 with 15.0 GB GPU Memory
  - GPU V100 with 16.0 GB GPU Memory
  - GPU A100 with 40.0 GB GPU Memory
- GPU P100 provided by Kaggle

## Evaluation Metrics
1. Recall@k: Computes the fraction of relevant items out of all relevant items.
2. NDCG@k: Measures ranking quality, assigning higher scores to hits at top ranks with logarithmic discounting.

## Results
- Testing Performance: Comparative analysis of models' performance.
- Accuracy-diversity comparison with different values of k (k=5, 10, 30, 40, and 50).
- Training Efficiency: Comparison of training efficiency in Yelp2018 dataset, including total training time and number of epochs required for optimal performance.

## Discussion
- Discussing advantages and limitations of each model, such as the oversmoothing problem.
- Drawing important conclusions for enhancing recommendations, particularly for large-scale recommendation systems.

## Conclusion
This project contributes to understanding the efficacy of graph neural network-based approaches in recommender systems. By evaluating performance, efficiency, and discussing limitations, it provides insights for improving recommendation systems, particularly in handling large-scale datasets.
