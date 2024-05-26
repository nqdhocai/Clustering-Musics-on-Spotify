# Clustering_Music_in_Spotify

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Dataset](#dataset)
- [Methods](#methods)
- [Results](#results)
- [Contributing](#contributing)

## Introduction

Clustering_Music_in_Spotify is a machine learning project aimed at clustering songs from Spotify based on their audio features. This project leverages unsupervised learning techniques to group similar songs, helping users discover new music that fits their taste.

## Installation

To install the necessary dependencies for this project, run the following command:

```bash
pip install -r requirements.txt
```

### Jupyter Notebooks

For an interactive exploration, you can use the provided Jupyter notebooks in the `notebooks/` directory.

## Dataset

The dataset used in this project consists of audio features for a variety of songs from Spotify. These features include attributes such as danceability, energy, loudness, tempo, and more.

## Methods

The following machine learning methods are utilized in this project:

- **Data Preparation**: Cleaning and normalizing the data.
- **Clustering**: Using algorithms like K-Means, DBSCAN, and Hierarchical Clustering to group similar songs.
- **Evaluation**: Validating the clustering results with metrics such as silhouette score and Davies-Bouldin index.

## Results

The results of the clustering analysis include visualizations of the clusters and insights into the characteristics of each cluster. These results can be used to recommend similar songs to users.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork this repository.
2. Create a new branch with your feature or bug fix.
3. Commit your changes.
4. Push to the branch.
5. Create a pull request.
