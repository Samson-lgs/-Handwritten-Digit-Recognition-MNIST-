# Handwritten Digit Recognition using MNIST Dataset

This project implements handwritten digit recognition using the MNIST dataset, comparing different machine learning models with and without PCA (Principal Component Analysis).

## Project Overview
- Implemented digit recognition using multiple models:
  - Support Vector Machine (SVM)
  - Logistic Regression
  - Neural Network
- Compared performance with and without PCA dimensionality reduction
- Visualized results and model comparisons

## Features
- Data preprocessing and visualization
- PCA implementation for dimensionality reduction
- Multiple model implementations
- Performance comparison and visualization
- Interactive Jupyter notebook

## Results
- Successfully reduced dimensions from 784 to ~274 using PCA
- Maintained high accuracy while significantly reducing training time
- Best performing model: Neural Network (94.70% accuracy without PCA)
- Significant training time reduction with PCA (up to 58%)

## Requirements
- Python 3.x
- Required libraries:
  - numpy
  - pandas
  - matplotlib
  - seaborn
  - scikit-learn

## Usage
1. Clone the repository
2. Open `mnist_recognition.ipynb` in Jupyter Notebook
3. Run all cells to see the results

## Dataset
The MNIST dataset contains images of handwritten digits (0-9):
- 28x28 pixel grayscale images
- Values scaled between 0 and 255
- Each image is flattened into 784 features
