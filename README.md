# Pothole Detection Using Transfer Learning

This project uses advanced transfer learning techniques to detect potholes in road images. By leveraging pre-trained models like VGG, DenseNet, and ResNet, the system achieves high accuracy in classifying roads as either normal or containing potholes.

## Features

- **Transfer Learning**: Employs state-of-the-art architectures for efficient training.
- **Multi-Model Support**: Compatible with VGG, DenseNet, ResNet, and other popular models.
- **Easy Preprocessing**: Includes resizing, normalization, and augmentation techniques.
- **High Accuracy**: Achieved through fine-tuning pre-trained networks.

## Dataset

- **Images**: 681 road images (352 normal roads, 329 with potholes).
- **Preprocessing**: All images are resized and normalized for consistent input.
- **Augmentation**: Additional transformations can be applied to enhance model performance (e.g., flipping, rotation).

## Prerequisites

- Python 3.8+
- TensorFlow 2.x 
- NumPy, OpenCV, Matplotlib, Pandas
- Scikit-learn
