# SVM
Machine Learning Support Vector Machine Implementation

## Introduction
Several SVM algorithms are implemented in this project

## Problems
1. Solve Primal problem with stochastic gradient update
2. Solve Dual problem with stochastic online update
3. Implement kernelised SVM (Linear, Polynomial, RBF kernels)
4. Implement Sequential Minimal Optimization, a training algorithm for the soft-margin SVM

## How to run
Simply run the jupyter notebook. Make sure using the correct environment. For detailed instructions please see the pdf file.

## Results
Used on a generated toy binary classification data and a part of the fashion-MNIST dataset, comprising pictures of clothing.

### Toy dataset
<img width="590" alt="image" src="https://user-images.githubusercontent.com/88305416/208589624-ab4c2a73-e174-4521-a9e3-2f2a995739b4.png">

Achieve 100% accuracy using soft-margin SVM with RBF kernel (sigma = 1)
<img width="556" alt="image" src="https://user-images.githubusercontent.com/88305416/208590019-1cb1b794-dc20-4110-b141-675d04da5575.png">


### MNIST dataset
<img width="579" alt="image" src="https://user-images.githubusercontent.com/88305416/208589668-26df79aa-bfdf-4ee2-82a0-32b6adf3ea52.png">

Accuracy = 83.5% using SMO on MNIST dataset, converged for 4min 16s on a M1 pro mac
<img width="911" alt="image" src="https://user-images.githubusercontent.com/88305416/208590389-1d32fa61-bd3f-4768-b1e5-3b5ad9426891.png">
