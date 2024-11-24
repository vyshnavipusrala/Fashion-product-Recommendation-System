# Fashion Product Recommendation System
## Overview
A visual-based recommendation system using ResNet50 for fashion products. It recommends similar products based on visual features extracted from images, using the Nearest Neighbors algorithm.

## Features
VisualSimilarity: Recommends similar products based on input image.

ResNet50: Uses pre-trained ResNet50 for feature extraction.

NearestNeighbors: Finds visually similar products.

Scalable: Efficient for large datasets.
## Technologies
Keras: For deep learning.

ScikitLearn: For NearestNeighbors.

Pickle: For saving features.

NumPy: For numerical operations.
 
## Dataset
Uses fashion-product-images-small dataset for training and testing.
https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small/code

## How it Works
DataPreprocessing: Resize and normalize images.

FeatureExtraction: Extract features using ResNet50.

SimilaritySearch: Find k-nearest neighbors.

Recommendations: Return similar products.
