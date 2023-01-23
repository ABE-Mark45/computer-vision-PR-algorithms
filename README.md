# Computer Vision Algorithms

The repository contains my implementation of different algorithms used in the context of computer vision and patter recognition.

# Parts

## PCA/LDA

- Principal Components Analysis implementation
- Linear Discriminant Analysis implementation
- Applying algorithms on Eigen faces dataset
- Using nearest neigbour matching to recognize faces

## KMeans

- Implementation of KMeans clustering algorithm
- Experiments of varying number of clusters on the results

## Spectral Clustering

- Implementing spectral clustering algorithm
- Implementing different clustering evaluation metrics
  - Conditional entropy
  - Jaccard index
  - F1-score
  - Beta-CV
  - Normalized cut score

## Bayes Classifier

- Implementing Bayes classifier and naive Bayes classifier

## Panorama Stitching

- Generating SIFT features and using 1-NN brute force matching by OpenCV
- Calculating the homography between two images
- Implementing forward warping and inverse warping algorithms
- Generalizing inverse warping to multiple images

## Dynamic Programming Based Stereo Matching

- Using dynamic programming to calculate disparity between two rectified stereo pair

## Lucas-Kanade Alignment Tracker

- Using Lucas-Kanade algorithm to match a template (object to be tracked) in a series of image assuming small motion and brightness constancy
