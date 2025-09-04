# ResNet50 on Tiny ImageNet

This repository contains a Jupyter Notebook demonstrating how to train and evaluate a ResNet50 model on the [Tiny ImageNet dataset](https://www.kaggle.com/datasets/akash2sharma/tiny-imagenet/data)

# Overview

* Loads the Tiny ImageNet dataset using kagglehub.
* Preprocesses data into a PyTorch Dataset & DataLoader.
* Building ResNet50 architecture from scratch and training
* Fine-tuning ResNet50 using torchvision.models.
* Evaluating all models on validation dataset.

# Training

The notebook trains a ResNet50 model:

* Data augmentation via torchvision.transforms

* CrossEntropy loss

* Optimizer: SGD

* Evaluation with accuracy metrics

