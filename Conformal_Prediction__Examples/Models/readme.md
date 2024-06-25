# Conformal Prediction Models

This directory contains the various models used for conformal prediction across different datasets. Each model is specifically tailored to the complexity and requirements of the dataset it is applied to.

## Overview

The models in this directory include:

- **Simple CNN**
  - Used for simpler datasets like MNIST and FashionMNIST.
  - Files:
    - [FashionMNIST_model.ipynb](https://github.com/Aadharsh1/ML-Deep-Learning/blob/main/Conformal_Prediction__Examples/Models/Simple_CNN/conformal_prediction_Fashion_Mnist.ipynb)
    - [MNIST_model.ipynb](https://github.com/Aadharsh1/ML-Deep-Learning/blob/main/Conformal_Prediction__Examples/Models/Simple_CNN/conformal_prediction_MNIST.ipynb)

- **Custom CNN**
  - A more complex version of the Simple CNN used for the Food101 dataset.
  - Files:
    - [Food101_model.ipynb](https://github.com/Aadharsh1/ML-Deep-Learning/blob/main/Conformal_Prediction__Examples/Models/Custom_CNN/conformal_prediction_Food101.ipynb)

- **EfficientNet B0**
  - Used for datasets with higher complexity such as CIFAR-10 and CIFAR-100.
  - Files:
    - [CIFAR10_model.ipynb](https://github.com/Aadharsh1/ML-Deep-Learning/blob/main/Conformal_Prediction__Examples/Models/EfficientNet_B0/conformal_prediction_cifar10.ipynb)
    - [CIFAR100_20_model.ipynb](https://github.com/Aadharsh1/ML-Deep-Learning/blob/main/Conformal_Prediction__Examples/Models/EfficientNet_B0/conformal_prediction_cifar100_20%20.ipynb)
    - [CIFAR100_superclasses_model.ipynb](https://github.com/Aadharsh1/ML-Deep-Learning/blob/main/Conformal_Prediction__Examples/Models/EfficientNet_B0/cp_cifar100_superclasses%20.ipynb)

- **ResNet50**
  - Used for highly complex datasets like Tiny Imagenet.
  - Files:
    - [Tiny_Imagenet_10_model.ipynb](https://github.com/Aadharsh1/ML-Deep-Learning/blob/main/Conformal_Prediction__Examples/Models/ResNet50/tiny_imagenet_10.ipynb)

