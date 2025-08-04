## CIFAR-10 Image Classification with CNN
This notebook implements a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset into 10 categories such as airplane, automobile, bird, and more.

## Key Features
- Dataset: CIFAR-10 (32×32 color images, 10 classes)

- Preprocessing: normalization, one-hot encoding

- Architecture: Custom CNN with Conv2D, BatchNorm, MaxPooling, Dropout

- Training: EarlyStopping and ReduceLROnPlateau used

- Evaluation: Accuracy/Loss plots, confusion matrix, sample predictions

## Results
- Best Validation Accuracy: ~68%

- Test Accuracy: Comparable to validation accuracy

- Observed misclassifications in visually similar categories (e.g., cat vs. dog)

## Experiments
Performed 10 model experiments with varying layer depths (conv2d_1 to conv2d_4) and tracked performance.

Requirements
- Python 3.x

- TensorFlow

- NumPy

- Matplotlib

- scikit-learn
