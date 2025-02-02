# Sports topology: exploring word embeddings in Russian

# Overview
This project explores the organization and relationships of Russian sports names within a semantic space using contextualized embeddings. 

# Dataset
The dataset consists of 100 manually collected Russian sports names categorized into 13 different types, including raquet sports, combat sports, animal sports, extreme sports, and water sports.

# Methodology
We employ the following techniques:

Embedding Extraction: Using contextualized embeddings from RuBERT to represent sports names.
Cosine Similarity: Calculating intra-group similarities to understand the closeness of sports within the same category.
Dimensionality Reduction: Visualizing the data using 2D and 3D graphs to identify distinct clusters.
Clustering Analysis: Applying methods like the Elbow Method and Silhouette Score to determine optimal cluster counts.
Autoencoder: Utilizing an autoencoder for further dimensionality reduction and clustering.

# Results
Sports are meaningfully grouped based on their semantic similarities with high cosine similarities within categories.
Dimensionality reduction and clustering reveal distinct groupings that correspond well with the predefined categories.
