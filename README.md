# Graph Clustering Project

This project focuses on the study and implementation of various graph clustering techniques, mainly Spectral Clustering, Stochastic Block Models, and Deep Graph Clustering.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Implemented Techniques](#implemented-techniques)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Graph clustering is an essential task in network analysis, aimed at partitioning a graph into meaningful groups or clusters. This project explores and implements several prominent graph clustering algorithms to analyze and understand complex networks.

## Installation

To use this project, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/your-username/graph-clustering.git
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

To run the implemented clustering techniques, execute the respective scripts provided in the project. Detailed usage instructions for each technique can be found in their corresponding documentation within the project directory.

Example usage:

```bash
python main.py --method spectral --adj adjacency_matrix.csv --features node_features.csv --n_clusters 3
```

## Implemented Techniques
1. Spectral Clustering: Spectral clustering is a popular technique for graph clustering that leverages the eigenvalues of a similarity matrix derived from the graph. It aims to partition the graph into clusters that are well-connected internally and have weak connections with other clusters.
2. Stochastic Block Models: Stochastic Block Models (SBM) assume that the graph is generated by a probabilistic model where nodes belong to one of several blocks, and the probability of an edge between nodes depends on the blocks they belong to. SBM aims to recover the underlying block structure of the graph.
3. Deep Graph Clustering: Deep Graph Clustering methods leverage deep learning techniques to learn embeddings for nodes in the graph and perform clustering based on these embeddings. These methods often combine graph neural networks with clustering algorithms to achieve state-of-the-art results.

## License
This project is licensed under the MIT License.