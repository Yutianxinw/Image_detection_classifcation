# 🐶🐱 Dogs vs. Cats - Image Classification (Kaggle)

This project builds a convolutional neural network (CNN) model to classify images of dogs and cats using the dataset from the [Kaggle Dogs vs. Cats Redux competition](https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition/overview).

## 🎯 Objective

To create a high-performing binary classifier that distinguishes between dog and cat images. The final model was evaluated using Kaggle’s private leaderboard.

## 🧠 Models Explored

- Baseline CNN from scratch
- Transfer learning using **ResNet50**
- Data augmentation (rotation, zoom, horizontal flip)
- Batch normalization and dropout tuning

## ⚙️ Model Training

- Optimizer: Adam
- Loss function: Binary cross-entropy
- Evaluation metric: Accuracy
- Epochs tested: 10–50
- Image resolution: 128x128, 224x224
