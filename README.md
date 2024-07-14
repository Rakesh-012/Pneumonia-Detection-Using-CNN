# Pneumonia Detection from Chest X-Ray Images using CNN
This repository contains code and resources for training a deep learning model to detect pneumonia from chest X-ray images using Convolutional Neural Networks (CNN). The model is trained on a dataset consisting of chest X-ray images labeled as either normal or pneumonia.

## Dataset
The dataset used for training the model was initially obtained from Kaggle. I have made some modifications to the dataset, and the updated version can be downloaded from [Google Drive.](https://drive.google.com/drive/folders/1nnfFqdPVLCAiSdTaNEGNc7WWELP7eMfz?usp=drive_link)

The dataset consists of a training set, a validation set, and a test set, with images classified into two categories: normal and pneumonia.

## Dependencies
The following dependencies are required to run the code in this repository:

- *Python 3.x*
- *TensorFlow*
- *Keras*
- *NumPy*
- *Matplotlib*
- *Pandas*

## You can install the required dependencies using the following command:
pip install tensorflow keras numpy matplotlib pandas

## Model Architecture
The model is a Convolutional Neural Network (CNN) with the following architecture:

- *Input layer: 224x224x3 images*
- *Convolutional layers*
- *Max pooling layers*
- *Fully connected layers*
- *Output layer with softmax activation for binary classification (normal or pneumonia)*


## Acknowledgments
The initial dataset was provided by Kaggle.

The project was inspired by various deep learning tutorials and research papers on pneumonia detection using CNNs.
