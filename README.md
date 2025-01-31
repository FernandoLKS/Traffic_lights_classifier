# Traffic Light Detection and Classification with Faster R-CNN
This repository contains the implementation of a system for detecting and classifying traffic lights in images, using the Faster R-CNN model from the torchvision library. The goal is to identify the presence of traffic lights and determine the signal (red, yellow, or green) in real-time.

# Dataset
The model was trained using the LISA Traffic Light Dataset, which contains annotated video sequences of traffic lights under different lighting and weather conditions (https://www.kaggle.com/datasets/mbornoe/lisa-traffic-light-dataset/data).

# Project Overview
The following libraries and frameworks were used in the project:
1. `Pandas` - For extracting and visualizing information in tables.
2. `Numpy` - Assists in manipulating images, matrices, and vectors.
3. `OpenCV` - For image preprocessing.
4. `Matplotlib` - For visualizing images.
5. `PyTorch` - For creating and training the models.

# Modelos
For detecting the bounding boxes of traffic lights, a pre-trained `fasterrcnn_resnet50_fpn` model was used. For classifying the traffic light signal, a convolutional neural network (CNN) was created using PyTorch.
