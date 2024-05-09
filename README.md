# FoodVision-101 Classifier

## Overview
This repository contains the implementation of a deep learning model for classifying images of sushi, steak, and pizza using the FoodVision-101 dataset. The model is based on a custom implementation of the ResNet-9 architecture and is trained on a subset of the FoodVision-101 dataset, focusing specifically on these three popular food categories.

## Motivation
The goal of this project is to develop an accurate image classifier that can distinguish between different types of food items commonly found in images shared on social media, restaurant menus, and food blogs. By focusing on sushi, steak, and pizza, we aim to showcase the model's effectiveness in recognizing distinct visual features of these foods, which can have practical applications in food recognition systems, dietary analysis tools, and restaurant recommendation engines.

## Dataset
The dataset used for training and evaluation is a subset of the FoodVision-101 dataset, which originally consists of 101 food categories. For this project, we selected 200 images each for testing and 800 images each for training, ensuring a balanced distribution across the three classes: sushi, steak, and pizza. Each image is labeled with its corresponding food category, facilitating supervised learning.

## Model Architecture
The model architecture is based on the ResNet-9 architecture, a variant of the popular ResNet architecture specifically designed for small to medium-sized datasets. ResNet-9 consists of four convolutional layers followed by batch normalization, ReLU activation, and max-pooling, culminating in a fully connected layer with softmax activation for multi-class classification.

## Results
After training the model on the training dataset and evaluating its performance on the test dataset, we achieved an impressive accuracy of nearly 80%. This indicates that the model is capable of accurately classifying images of sushi, steak, and pizza with high confidence, demonstrating its potential utility in real-world applications.

## Usage
To use the model, follow these steps:
1. Clone the repository to your local machine.
2. Install the necessary dependencies (Python, PyTorch, etc.).
3. Download the dataset or use your own dataset following the provided format.
4. Train the model.
5. Evaluate the trained model on a separate test dataset to assess its performance.
6. Experiment with hyperparameters, data augmentation techniques, and model architectures to further improve accuracy.

## Contributing
Contributions to this project are welcome! Whether it's fixing bugs, optimizing code, adding new features, or improving documentation, feel free to submit pull requests or open issues. Please adhere to the project's coding style and guidelines.
