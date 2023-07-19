# ImageRecognitionDeepLearning

[![Pytorch](https://img.shields.io/badge/Deep%20Learning-Pytorch-blue)](https://pytorch.org/)
[![CNN](https://img.shields.io/badge/Cuda-Convolutional%20Neural%20Networks-green)]()
[![Image Recognition](https://img.shields.io/badge/Image%20Recognition-Traffic%20-8A2BE2)]()

This project focuses on the task of recognizing emergency vehicles using Convolutional Neural Networks (CNNs). The goal is to develop a robust and accurate model capable of identifying emergency vehicles in real-world scenarios.

## Dataset

The dataset used for training and evaluation consists of 681 images of emergency vehicles and 965 images of non-emergency vehicles. The images are organized in the 'vehicles' directory, with subdirectories representing the respective classes. The dataset has been preprocessed, resized to 224x224 pixels, converted to tensors, and normalized.

## Model Architecture

The CNN model architecture employed in this project is designed to capture relevant features for emergency vehicle recognition. It comprises convolutional layers for feature extraction, pooling layers for downsampling, dropout layers for regularization, and fully connected layers for classification. The model has been implemented in PyTorch.
