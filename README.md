# Comparative Analysis of Machine Learning Algorithms on MNIST

## Project Overview
This project compares the performance of five different machine learning models on the MNIST handwritten digit classification dataset. The goal was to evaluate accuracy, precision, and efficiency across different architectures.

## Models Evaluated
1. **K-Nearest Neighbours (KNN)**
2. **Naive Bayes**
3. **Decision Tree Classifier**
4. **Multi-Layer Perceptron (MLP)**
5. **Convolutional Neural Network (CNN)** - *Best Performer (~99% Accuracy)*

## Results
The Convolutional Neural Network (CNN) outperformed all other models due to its ability to capture spatial hierarchies in image data.

| Model | Accuracy |
| :--- | :--- |
| **CNN** | **98.69%** |
| **MLP** | **94.94%** |
| **KNN** | **96.81%** |
| **Decision Tree** | **86.53%** |
| **Naive Bayes** | **55.44%** |

## How to Run
1. Open the `.ipynb` file in Google Colab.
2. Run all cells to download the dataset and train the models.
3. See the `MNIST_Assignment_Report.pdf` for detailed confusion matrices and analysis.
