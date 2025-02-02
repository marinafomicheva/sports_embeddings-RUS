# Sports Topology: Exploring Word Embeddings in Russian

## Overview
This project analyzes the organization and relationships among Russian sports terminology using word embeddings. Our goal is to explore how sports names cluster within a semantic space, providing insights into their contextual relationships.

## Dataset
The dataset includes 100 Russian sports names, manually curated and classified into 13 distinct categories such as racquet sports, combat sports, animal sports, extreme sports, and water sports.

## Methodology
We used several techniques to examine and visualize the semantic space of sports names:

- **Embedding Extraction:** Used contextualized embeddings from RuBERT to accurately represent sports names.
- **Cosine Similarity:** Calculated intra-category similarities to assess the closeness of sports within the same type.
- **Dimensionality Reduction:** Employed techniques like PCA and t-SNE for 2D and 3D visualization of the sports names, facilitating the identification of distinct clusters.
- **Clustering Analysis:** Applied clustering algorithms and evaluating methods such as the Elbow Method and Silhouette Score to determine the optimal number of clusters.
- **Autoencoder:** Using an autoencoder to enhance dimensionality reduction and clustering accuracy.

## Results
The analysis demonstrates that sports names are meaningfully grouped based on their semantic similarities, with high cosine similarity scores within each category. The application of dimensionality reduction and clustering techniques successfully reveals distinct groupings, aligning closely with the predefined categories.
