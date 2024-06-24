# Conformal Prediction Examples

This repository contains examples of applying conformal prediction to various datasets using custom Convolutional Neural Networks (CNNs) and transfer learning techniques. Conformal prediction is a statistical method that provides a measure of confidence in the predictions made by machine learning models.

## Overview

Conformal prediction was applied to different datasets to observe the prediction sets on new samples. The datasets include:

- **CIFAR-10**
- **CIFAR-100**
- **FashionMNIST**
- **Food101**
- **MNIST**
- **Tiny Imagenet**

For simpler datasets like MNIST and FashionMNIST, custom CNNs were built. For more complex datasets like Food101, CIFAR-10, CIFAR-100, and Tiny Imagenet, transfer learning was used.


## Conformal Prediction on Different Datasets

### Fashion MNIST
- **Description**: Conformal prediction applied to the Fashion MNIST dataset.
- **Notebook**: [conformal_prediction_Fashion_Mnist.ipynb](https://github.com/Aadharsh1/ML-Deep-Learning/blob/main/Conformal_Prediction__Examples/FashionMNIST/conformal_prediction_Fashion_Mnist.ipynb)

### Food101
- **Description**: Conformal prediction applied to the Food101 dataset using transfer learning.
- **Notebook**: [conformal_prediction_Food101.ipynb](https://github.com/Aadharsh1/ML-Deep-Learning/blob/main/Conformal_Prediction__Examples/Food101/conformal_prediction_Food101.ipynb)

### MNIST
- **Description**: Conformal prediction applied to the MNIST dataset.
- **Notebook**: [conformal_prediction_MNIST.ipynb](https://github.com/Aadharsh1/ML-Deep-Learning/blob/main/Conformal_Prediction__Examples/MNIST/conformal_prediction_MNIST.ipynb)

### CIFAR-10
- **Description**: Conformal prediction applied to the CIFAR-10 dataset.
- **Notebook**: [conformal_prediction_cifar10.ipynb](https://github.com/Aadharsh1/ML-Deep-Learning/blob/main/Conformal_Prediction__Examples/CIFAR10/conformal_prediction_cifar10.ipynb)

### CIFAR-100 (20 classes)
- **Description**: Conformal prediction applied to the CIFAR-100 dataset (20 classes).
- **Notebook**: [conformal_prediction_cifar100_20.ipynb](https://github.com/Aadharsh1/ML-Deep-Learning/blob/main/Conformal_Prediction__Examples/CIFAR100/conformal_prediction_cifar100_20%20.ipynb)

### CIFAR-100 (Superclasses)
- **Description**: Conformal prediction applied to the CIFAR-100 dataset (superclasses).
- **Notebook**: [cp_cifar100_superclasses.ipynb](https://github.com/Aadharsh1/ML-Deep-Learning/blob/main/Conformal_Prediction__Examples/CIFAR100/cp_cifar100_superclasses%20.ipynb)

### Tiny Imagenet (10 classes)
- **Description**: Conformal prediction applied to the Tiny Imagenet dataset (10 classes).
- **Notebook**: [tiny_imagenet_10.ipynb](https://github.com/Aadharsh1/ML-Deep-Learning/blob/main/Conformal_Prediction__Examples/Tiny_Imagenet/tiny_imagenet_10.ipynb)
