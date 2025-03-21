# CT Slice Location Prediction Project

## Project Overview

Machine learning system for predicting anatomical positions from CT scan features using regression models and neural networks. Developed as part of MLPR coursework at the University of Edinburgh. Code for this coursework is almost **from scratch** without using some popular ML libraries(except some optimization functions) which means deeper understanding on math and basic ML algorithms.

***Final mark: 80***

 **Key Features** :

* Multiple model implementations (Linear/Logistic Regression, Neural Networks)
* Bayesian optimization with Gaussian Processes
* Comprehensive performance analysis framework

## Technical Stack

* Python 3.9
* NumPy
* Matplotlib
* Scipy
* Jupyter Notebook

## Dataset

* CT scan slices from 97 patients
* 384 features per scan slice
* Preprocessed dataset with 5,785 training samples

## Key Results

| Model                 | Validation RMSE | Test RMSE |
| --------------------- | --------------- | --------- |
| Linear Regression     | 0.423           | 0.423     |
| Logistic Ensemble     | 0.254           | 0.285     |
| Neural Network        | 0.267           | 0.271     |
| Bayesian-Optimized NN | 0.239           | 0.268     |

## Contributors

* [Chunyu Yan] - Core algorithm development
* [Chi Xing] - Core algorithm development
