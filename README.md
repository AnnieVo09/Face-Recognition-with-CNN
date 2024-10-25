# Face Recognition with Convolutional Neural Networks

## Introduction

This project explored the development and evaluation of Convolutional Neural Networks (CNNs) for face recognition using the Labeled Faces in the Wild (LFW) dataset from scikit-learn., a real-world collection of over 13,000 facial images. The LFW dataset presents a challenge due to its class imbalance, with some individuals having significantly more images than others. The objective of the project was to build and compare CNN models, varying both kernel sizes and the number of filters, to understand the impact of these architectural changes on model performance.

## Contents

The Jupyter notebook:

- Imports the LFW dataset
- Splits data into train and test sets 
- Defines CNN architecture with convolution, pooling, dropout and dense layers
- Compiles and trains model
- Makes predictions on test set
- Evaluates model accuracy 
- Visualizes some predictions

It also shows the full CNN architecture visualization produced by VisualKeras.

## Setup

To run this facial recognition project, you need:

- Python 3
- TensorFlow 
- Keras
- scikit-learn
- VisualKeras
- Open CV

Install requirements with:

```
pip install tensorflow keras scikit-learn visualkeras opencv-python
```

## Usage 

Run the Jupyter notebook cell-by-cell to execute the CNN facial recognition workflow from end-to-end.

## Results

The CNN model achieves an accuracy of 95% on the test set for recognizing individual identities. The final classification report and confusion matrix evaluate performance in detail.

## Customization

The CNN architecture and training hyperparameters can be tweaked as needed to experiment with improving accuracy. More data augmentation could also help the model generalize better to new faces.
