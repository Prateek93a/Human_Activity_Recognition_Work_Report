# Human Activity Recognition - Work Report and Code

## Overview
This work report discusses the problem of Human Activity Recognition based on UCI dataset Human Activity Recognition using Smartphone. Various Machine Learning Models have been proposed for the same. This report proposes two models: Single Layer Perceptron model and Radial Basis Function Network, for classifying the given data into various activity labels. I have also introduced new kernel function.
            
## Dataset Used
The following dataset has been used for the purpose:
[Human activity recognition using smartphones data set](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones)

## Machine Learning Models  Proposed
The following Machine Learning Models have been studied for the task. The intuition and maths have been described in the work report. 
### A. Single Layer Perceptron
### B. RBF Network
Two kernel functions have been used for performing non-linear transformation of input samples:
#### B.1. Traditional Gaussian RBF using Euclidean Distance Metric
#### B.2. Custom RBF using Manhattan Distance Metric

 ## My Experience
 While working on the project, I explored various works that have already been done on the task and different models that have been proposed so far. However the problem with most Machine Learning models is that they are computation intensive and are not suitable for deploying on devices with low computational power such as mobile phones. The models I have proposed work fast and have high accuracy on the given dataset but they require lots of pre-processing before they can be used for predictions, a problem that traditional Machine Learning models face.

I learned many things related to data visualisation and inference. In case of RBF Network, I also tried to bring novelty by introducing a new kernel function for non-linear transformation of the input samples. 
High train and test accuracies indicate the models perfomed very well on the dataset.
