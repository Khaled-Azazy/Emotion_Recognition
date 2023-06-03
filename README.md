# Emotion_Recognition

This project aims to build an emotion recognition model using different datasets like FER13, AffectNet, and RAF-DB. The model is built from scratch using TensorFlow and Keras. Image augmentation techniques, including rotation, shearing, cropping, and more, are applied to enhance the model's performance.


## Introduction

Emotion recognition plays a crucial role in various applications such as human-computer interaction, affective computing, and sentiment analysis. This project focuses on developing an emotion recognition model using deep learning techniques.

## Data Sets

The following datasets were used in this project:

- FER13: The Facial Expression Recognition 2013 (FER2013) dataset contains 35,887 grayscale images of 48x48 pixels, labeled with 7 emotion categories.
- AffectNet: AffectNet is a large-scale facial expression dataset with over 1 million facial images. It provides a wide range of emotions and includes diverse demographics.
- RAF-DB: The Radboud Faces Database (RAF-DB) is a dataset with 8,000 images depicting facial expressions of 7 emotion categories.

Please refer to the respective datasets' documentation for more details on how to access and use them.

## Model Architecture

The emotion recognition model is built from scratch using the TensorFlow and Keras frameworks. The architecture consists of several convolutional and pooling layers followed by fully connected layers. The model is trained using the combined datasets of FER13, AffectNet, and RAF-DB to leverage their diversity and enhance the model's ability to generalize emotions.

## Image Augmentation

To improve the model's robustness and generalization, image augmentation techniques are applied during the training process. These techniques include rotation, shearing, cropping, flipping, and more. Image augmentation helps to create additional training samples by applying random transformations to the original images.
