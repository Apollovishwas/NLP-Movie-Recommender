# Movie Similarity Analysis

## Project Overview

This project aims to quantify the similarity between movies based on their plot summaries from IMDb and Wikipedia. Using natural language processing (NLP) techniques and clustering algorithms, we group movies into clusters and visualize their relationships through a dendrogram.

## Dataset

The dataset contains information about top-rated movies, including:

- Movie titles
- Plot summaries from IMDb
- Plot summaries from Wikipedia

## Methodology

1. **Data Preprocessing**:
   - Combine IMDb and Wikipedia plot summaries
   - Clean and tokenize text data

2. **Feature Extraction**:
   - Apply TF-IDF (Term Frequency-Inverse Document Frequency) vectorization to convert text data into numerical features

3. **Similarity Calculation**:
   - Compute cosine similarity between movie vectors

4. **Clustering**:
   - Perform hierarchical clustering on the similarity matrix

5. **Visualization**:
   - Create a dendrogram to represent movie similarities and clusters

## Tools Used

- Python
- Pandas for data manipulation
- NLTK for natural language processing
- Scikit-learn for TF-IDF vectorization and cosine similarity
- SciPy for hierarchical clustering
- Matplotlib for dendrogram visualization