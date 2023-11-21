# Alzheimer's Detection using CNN (ResNet50)

## Overview
This project utilizes a Convolutional Neural Network (CNN) based on the ResNet50 architecture for the detection of Alzheimer's disease in MRI scans. The code is implemented in Python using the Keras deep learning library. The dataset used for training and testing is the Alzheimer's Dataset.

## Dataset
The dataset used in this project is obtained from the Alzheimer's Dataset found on Kaggle. It comprises MRI scans that are categorized into the following classes:

- MildDemented (Class 0)
- ModerateDemented (Class 1)
- NonDemented (Class 2)
- VeryMildDemented (Class 3)

## Data Preprocessing
The images are loaded and preprocessed using Keras' ImageDataGenerator. The dataset is then split into training and testing sets, with 80% of the data used for training and 20% for testing.

## CNN Model (ResNet50)
The Convolutional Neural Network (CNN) model is based on the ResNet50 architecture, a deep neural network with 50 layers. The model is compiled using the Adam optimizer and Categorical Crossentropy loss. The training process involves data augmentation, and callbacks are implemented for model checkpointing, early stopping, and learning rate reduction.

## Results and Evaluation
The training history, including metrics such as accuracy, loss, AUC, and precision, is saved and visualized. The model's predictions are displayed for a sample of the test dataset, and a confusion matrix is generated. Additional metrics, such as F1 score and accuracy, are printed for comprehensive evaluation.

## Visualization
A function named `Train_Val_Plot` is utilized to visualize the training history. This function plots accuracy, loss, AUC, and precision over epochs.

## Prediction and Evaluation
The trained model is employed to predict Alzheimer's disease classes for the test dataset. Predictions are visually compared with actual labels, and a confusion matrix is created. F1 score, accuracy, and a classification report are printed for a detailed evaluation.

 ## Report Contents
1. The Dataset
2. The network structure and hyperparameters
3. Loss Function
4. The Optimiser
5. Cross-fold validation
6. Results
7. Evaluation of the results
8. Impact of varying hyperparameters

# [View Evaluation](https://github.com/OliverNagy10/CNN---ResNet50/blob/main/ResNet50_Analsys_and_Evaluation.pdf)
# [View Notebook](https://github.com/OliverNagy10/CNN---ResNet50/blob/main/CNN_ResNet50.ipynb)
