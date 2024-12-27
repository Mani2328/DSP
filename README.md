# DSP
Data Science Project - Waste Classification using Convolution Neural Networks
Image Source: The original image dataset was from UC Irvine machine learning repository.

In the real waste classification project, 3 CNN custom classification models and 2 pre-trained, state-of-art models were evaluated
There were 4 class labels - Glass, Metal, Paper and Textile in experiment 1 to 6.2

Hyperparameters were added to the custom CNN models to improve the validation and test accuracy in the following oreder:
1) Experiment 1 - Batach Size and Image Size selection
2) Experiment 2 - Learning rate optimization
3) Experiment 3 - Batch Normalization
4) Experiment 4 - Regularization L1L2
5) Experiment 5 - Data Augmentation

The following pre-trained models were also trained on the real waste classification 
1) Experiment 6.1 EfficientNetV2 and MobileNetV3 without data augmentation
2) Experiment 6.2 EfficientNetV2 and MobileNetV3 with data augmentation 

Finally all the models were tested with 6 classes - Glass, Metal, Organics, Paper, Plastic, Textile.

Dateset used in this project are as follow:

Dataset 1: 270 images for training and 50 images for testing for each class. (4 classes).
Dataset 2: 450 images for training and 50 images for testing for each class (4 classes, with data augmentation).
Dataset 3: 450 images for training and 50 images for testing for each class. (6 classes, with data augmentation). 

Due to file size constraint, the images dataset were split into multiple zipped folder and assemble as indicated below
For Dataset 1: Only use images without Class_Aug pre-fix on the images name from Glass, Metal, Paper and Textile
For Dataset 2: Use all the images from Glass, Metal, Paper and Textile
For Dataset 3: Use all the images from all the 6 classes

You need to defines the path in the function load-data to load any of the dataset mention above. 
All the 3 dataset are provided in the github directory
