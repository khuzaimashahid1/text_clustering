# Text Clustering
This repository contains code for clustering text documents using the K-means algorithm. The code preprocesses the text data, creates a TF-IDF representation, computes distances between documents, performs K-means clustering, and visualizes the clusters.

# Getting Started
## Prerequisites
Make sure you have the following libraries installed:

NumPy
Pandas
NLTK
BeautifulSoup
Scikit-learn
Matplotlib
mpld3

## Usage
You can run the code by executing the script. The script performs the following steps:

Import the required libraries.
Define helper functions for reading files and folders, tokenizing and stemming text, and computing distances.
Read the files and folders containing the text documents.
Tokenize and stem the text.
Split the text into training and testing sets.
Create a TF-IDF representation for the text data.
Compute distances between documents using cosine similarity.
Perform K-means clustering on the training set.
Visualize the clusters using multidimensional scaling (MDS).
Evaluate the clusters using external evaluation metrics such as purity and internal evaluation metrics such as inter-cluster distances.
Repeat the above steps for different values of K.

## Results
The code outputs visualizations of the clusters using scatter plots. It also prints the maximum and average inter-cluster distances for both the training and testing sets. For K=6, the code calculates the purity of the clusters using predefined classes.