# Implementing PCA and K-Means on the MNIST Dataset

## About the Project

This project implements Principal Component Analysis (PCA) and K-Means clustering from scratch using NumPy
on the MNIST Dataset.  

### Features

* Principal Component Analysis (PCA) from scratch using NumPy
* Implementation of the K-Means Clustering Algorithm on the Images of the MNIST Dataset.
* Projection of Images onto low-dimensional affine subspaces 
* Classification of MNIST Digits using PCA and K-Means Clustering
  
#### Example Results 


* Principal Components and Mean of Images (MNIST 1000 samples) 
<img width="630" height="415" alt="Comparison of Principal Components agains the mean" src="https://github.com/user-attachments/assets/c38be192-2af3-4968-82a1-11b889b7bbda" />


* Projection of images onto a lower-dimensional affine subspace
<img width="385" height="470" alt="Plot of projected Images onto the subspace " src="https://github.com/user-attachments/assets/70e2178d-c1c3-4086-9555-4b9bacdc39a5" />


  * K-Means clustering on MNIST digits (0 and 1) after PCA projection
<img width="515" height="409" alt="K-Means Clustering Plot" src="https://github.com/user-attachments/assets/a9a1ce72-b6fb-4b94-9ea3-e8de8c9e7383" />




### Built with
* numpy
* matplotlib

## Getting Started
1. Clone the repo
```
git clone https://github.com/sebastianfeder/mnist-pca-kmeans.git
```
2. Install required libaries with
```
pip install -r requirements.txt
```
3. To view the implementations and plots, open
```
src/main.ipynb
```

Authors:
* Sebastian Feder
* Technical University of Berlin (TU Berlin)
