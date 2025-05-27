# MNIST Logistic Regression Model

A machine learning project implementing logistic regression on the MNIST handwritten digit dataset using scikit-learn.

## Project Overview

This project demonstrates the application of logistic regression for multiclass classification on the classic MNIST dataset. The MNIST dataset consists of 28x28 grayscale images of handwritten digits (0-9) with a training set of 60,000 examples and a test set of 10,000 examples.

## Features

- Data loading and preprocessing using PyTorch's datasets and transforms
- Implementation of multiclass logistic regression using scikit-learn
- Model evaluation with accuracy metrics, classification report, and confusion matrix
- Visualization of sample images from the dataset

## Requirements

The project requires the following Python packages:
- numpy
- matplotlib
- scikit-learn
- torch
- torchvision

You can install all dependencies using:
```bash
pip install -r requirements.txt
```

## Usage

The main code is in the Jupyter notebook `mnist_regression_model.ipynb`. To run the project:

1. Clone the repository
2. Install the dependencies
3. Run the Jupyter notebook

## Model Performance

The logistic regression model achieves:
- Training accuracy: 93.93%
- Test accuracy: 92.57%  

The model performs well across all digit classes, with particularly high precision and recall for digits 0, 1, 4, and 6.

## Detailed Results

Classification metrics for each digit:

| Digit | Precision | Recall | F1-Score | Support |
|-------|-----------|--------|----------|---------|
| 0     | 0.95      | 0.97   | 0.96     | 980     |
| 1     | 0.96      | 0.98   | 0.97     | 1135    |
| 2     | 0.93      | 0.90   | 0.92     | 1032    |
| 3     | 0.90      | 0.92   | 0.91     | 1010    |
| 4     | 0.94      | 0.94   | 0.94     | 982     |
| 5     | 0.90      | 0.87   | 0.88     | 892     |
| 6     | 0.94      | 0.95   | 0.95     | 958     |
| 7     | 0.93      | 0.92   | 0.93     | 1028    |
| 8     | 0.88      | 0.88   | 0.88     | 974     |
| 9     | 0.91      | 0.92   | 0.91     | 1009    |

Overall accuracy: 93%

## Contributors

- Mhd Eyad Abou Ker 40208070

## License

This project is available for educational and research purposes.