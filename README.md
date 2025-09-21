# Spotify-Project
## Overview

Music streaming platforms like Spotify generate massive amounts of data related to song characteristics, user preferences, and listening habits. By applying clustering techniques to song audio features, this project explores hidden patterns in the music dataset.

The objective is to group songs into meaningful clusters based on their audio features, providing insights into music styles and laying the foundation for applications such as playlist generation and recommendation systems.

#### Dataset

The dataset used is ML_spotify_data.csv, which contains audio features of songs. The dataset may either be sourced via the Spotify API or from pre-collected CSV files.

#### Features

Acousticness – measure of acoustic sound in a track

Danceability – suitability of a track for dancing

Energy – intensity and activity level of a song

Instrumentalness – likelihood of a track containing no vocals

Liveness – presence of a live audience

Loudness – overall loudness of a track

Speechiness – presence of spoken words

Tempo – beats per minute (BPM)

Valence – musical positiveness of a track

#### Preprocessing

Handle missing values

Normalize features (e.g., MinMaxScaler, StandardScaler)

Remove duplicates

Optional: dimensionality reduction for visualization

### Methods

The following unsupervised learning techniques are applied:

K-Means Clustering – partitions songs into k groups based on similarity

Hierarchical Clustering – builds a hierarchy of clusters

DBSCAN – density-based clustering for irregular clusters and noise detection

Gaussian Mixture Model (GMM) – probabilistic clustering assuming Gaussian distributions

Dimensionality Reduction

PCA (Principal Component Analysis) – for improving cluster separation

t-SNE – for visualization in 2D

### Evaluation

Since clustering is unsupervised, evaluation relies on interpretability and internal metrics:

Elbow Method – to determine optimal number of clusters (k) in K-Means

Silhouette Score – to measure cluster cohesion and separation

Dendrograms – to analyze hierarchical clustering

Cluster Profiles – analyzing feature averages within each cluster

Visualizations – PCA/t-SNE plots for intuitive interpretation
