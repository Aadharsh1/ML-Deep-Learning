# Transfer Learning Models

This directory contains the various models used for transfer learning across different datasets. Each model is specifically tailored to the complexity and requirements of the dataset it is applied to.

## Overview

The models in this directory include:

- **EfficientNet B0**
  - Used for datasets with higher complexity such as CIFAR-10 and Food101.
  - Files:
    - [Transfer_Learning_CIFAR10.ipynb](https://github.com/Aadharsh1/ML-Deep-Learning/blob/main/Transfer_Learning_Examples/Models/CIFAR10/Transfer_Learning_CIFAR10.ipynb)
    - [Transfer_Learning_Food101_10.ipynb](https://github.com/Aadharsh1/ML-Deep-Learning/blob/main/Transfer_Learning_Examples/Models/Food101/Transfer_Learning_Food101_10.ipynb)
    - [Transfer_Learning_Food101_Mini.ipynb](https://github.com/Aadharsh1/ML-Deep-Learning/blob/main/Transfer_Learning_Examples/Models/Food101/Transfer_Learning_Food101_Mini.ipynb)

- **ResNet50**
  - Used for the validation of the Imagenet validation set.
  - Files:
    - [imagenet_val_test.ipynb](https://github.com/Aadharsh1/ML-Deep-Learning/blob/main/Transfer_Learning_Examples/Models/Imagenet_Validation/imagenet_val_test.ipynb)

## EfficientNet B0

### CIFAR-10
- **Description**: Transfer learning applied to the CIFAR-10 dataset using the EfficientNet B0 model.
- **Notebook**: [Transfer_Learning_CIFAR10.ipynb](https://github.com/Aadharsh1/ML-Deep-Learning/blob/main/Transfer_Learning_Examples/Models/CIFAR10/Transfer_Learning_CIFAR10.ipynb)

### Food101 (10 classes)
- **Description**: Transfer learning applied to the Food101 dataset (10 classes) using the EfficientNet B0 model.
- **Notebook**: [Transfer_Learning_Food101_10.ipynb](https://github.com/Aadharsh1/ML-Deep-Learning/blob/main/Transfer_Learning_Examples/Models/Food101/Transfer_Learning_Food101_10.ipynb)

### Food101 Mini (3 classes)
- **Description**: Transfer learning applied to the Food101 Mini dataset (3 classes) using the EfficientNet B0 model.
- **Notebook**: [Transfer_Learning_Food101_Mini.ipynb](https://github.com/Aadharsh1/ML-Deep-Learning/blob/main/Transfer_Learning_Examples/Models/Food101/Transfer_Learning_Food101_Mini.ipynb)

## ResNet50

### Imagenet Validation Set
- **Description**: Validation of the Imagenet validation set using ResNet50 pretrained weights.
- **Notebook**: [imagenet_val_test.ipynb](https://github.com/Aadharsh1/ML-Deep-Learning/blob/main/Transfer_Learning_Examples/Models/Imagenet_Validation/imagenet_val_test.ipynb)
