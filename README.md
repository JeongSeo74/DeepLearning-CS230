# DeepLearning-CS230
CS230-Deep Learning (2019 FALL) 

Final Project - Deep-Learning Based Classification Models for Wafer Defective Pattern Recognition

Wafer Map dataset is from kaggle
https://www.kaggle.com/qingyi/wm811k-wafer-map

@Model and DATA
-VGG-16, ResNet-50 and two Simplified VGG-16 are trained on NVIDIA RTX 2080(8G) with Keras.
-Dataset is unbalanced so two data augmentation ways are used: Convolutional Autoencoder and Rotating.

@CONCLUSIONS
-Training accuracy: 0.99, Test Accuracy: 0.98 is the best (GAP-SV)
-VGG-16 is the best for both augmented dataset (f1 score:0.91)
-GAP-SV is best with rotating data (training time is half of VGG-16)
