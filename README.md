# Network Analysis and Node Classification with Zachary Karate Club and Cora Datasets

## Overview

This project is part of the Social Information Network Analysis and Engineering course at The Hong Kong University of Science & Technology. The primary objective is to analyze the Zachary Karate Club network, perform node embedding and clustering using the Deep Graph Library (DGL), and conduct node classification using the Cora dataset.

## Dataset

- **Zachary Karate Club Dataset**: Represents the social interactions between members of a karate club.
- **Cora Dataset**: A citation network dataset used for node classification tasks.

## Contents

The project is divided into three main sections:

1. **Girvan-Neuman Algorithm**:
    - Draw the BFS result for paths starting from node C.
    - Obtain the number of shortest paths from C to each node.
    - Calculate the betweenness contributions for each path.

2. **Node Embedding and Clustering**:
    - Build the GraphSAGE model with two GNN layers and ReLU activation function.
    - Train the node embedding using adjacency-based similarity function.
    - Draw the node embedding using Matplotlib.
    - Partition the graph into subgraphs using k-means clustering.
    - Repeat with three GNN layers and a 2-hop similarity function.

3. **Node Classification**:
    - Build the GraphSAGE model with two GNN layers and a ReLU activation function.
    - Add a linear layer on top for classification.
    - Train the model on the Cora dataset and report the testing accuracy.

## Methods

- **DGL (Deep Graph Library)**: Used for graph neural network tasks and network analysis.
- **NetworkX**: Used for loading and manipulating the network data.
- **Matplotlib**: Employed for creating various visualizations.
- **GraphSAGE**: A framework for inductive representation learning on large graphs.
- **K-means Clustering**: Used to partition the graph into subgraphs.
- **Node Classification**: Using the GraphSAGE model and cross-entropy loss for classification tasks.

## Results

- **Girvan-Neuman Algorithm**: Visualizations of BFS results, shortest paths, and betweenness contributions.
- **Node Embedding and Clustering**: Visualizations of node embeddings and clustering results.
- **Node Classification**: Reported testing accuracy on the Cora dataset.

## Usage

1. **Environment Setup**: Ensure you have the necessary Python libraries installed (DGL, NetworkX, Matplotlib, sklearn, torch).
2. **Data Loading and Preprocessing**: Follow the steps in the notebook to load and preprocess the data.
3. **Running the Analysis**: Execute the provided code to perform the network analysis, node embedding, clustering, and classification tasks.

## Requirements

- Python 3.x
- DGL (Deep Graph Library)
- NetworkX
- Matplotlib
- numpy
- sklearn
- torch

## Conclusion

This project demonstrates the application of network analysis techniques, node embedding, clustering, and node classification using the Zachary Karate Club and Cora datasets. It highlights the use of the Girvan-Neuman algorithm, GraphSAGE model, and k-means clustering for social network analysis.

## Acknowledgements

- The authors of the tools and libraries used in this analysis.
- The SNAP group for providing the datasets.
