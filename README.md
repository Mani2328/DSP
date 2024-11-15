# DSP
Data Science Project - CNN Classification project for real waste
Image Source: 

The original image dataset was from UC Irvine machine learning repository.

In the real waste classification project, 3 CNN custom classification models and 2 pre-trained CNN state-of-art models were tested.
Hyperparameters were added to the custom CNN models to improve the validation and test accuracy in the following oreder:
There are 4 class labels - Glass, Metal, Paper and Textile
1) Experiment 1 - Batach Size and Image Size selection
2) Experiment 2 - Learning rate optimization
3) Experiment 3 - Batch Normalization
4) Experiment 4 - Regularization L1L2
5) Experiment 5 - Data Augmentation

The following pre-trained models were also trained on the real waste classification 
1) Experiment 6.1 EfficientNetV2 and MobileNetV3 without data augmentation
2) Experiment 6.2 EfficientNetV2 and MobileNetV3 with data augmentation 

Finally all the models were tested with 6 classes - Glass, Metal, Organics, Paper, Plastic, Textile.

Dateset used in this project
Dataset 1: 270 images for training and 50 images for testing for each class. (4 classes).
Dataset 1: 450 images for training and 50 images for testing for each class (4 classes, with data augmentation).
Dataset 1: 450 images for training and 50 images for testing for each class. (6 classes, with data augmentation). 

You need to defines the path in the function load-data to load any of the dataset mention above. 
All the 3 dataset are provided in the github directory
