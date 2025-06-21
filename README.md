## Pneumonia Detection Using CNN

This project uses a Convolutional Neural Network (CNN) to detect pneumonia from grayscale chest X-ray images. It leverages TensorFlow and Keras for model training and evaluation, using the publicly available [Chest X-Ray Pneumonia Dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia).

## Dataset
- Source: Kaggle - [Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)
- Contains chest X-ray images categorized as NORMAL and PNEUMONIA.

## Features
- Data augmentation using `ImageDataGenerator`
- Grayscale image classification (150x150 resolution)
- CNN model architecture for binary classification
- Train-validation split: 80-20
- Model evaluation on test data
