# The-Mnist-hand-Written-digit-image-classification

# Problem Statement

The MNIST dataset is a collection of handwritten digits from 0 to 9. The objective of this project is to build a model that can accurately classify these digits.

# Data Source

The mnist dataset consist of 60000 training images and 10000 testing imagesg. The dataset is taken directly from keras library

# Pre-processing

In pre-processing steps all the images are normalized by dividing each pixel value by 255 to scale the values between 0 and 1

# Model 

The model consists of a sequential model with a Flatten layer and a Dense layer. The Flatten layer is used to convert the 2D image into a 1D array, and the Dense layer is used for classification. The number of neurons in the Dense layer is set to 10, which corresponds to the 10 possible digit classes.

# Hyperparameters 

The model is trained useing Adam optimizer. The loss function used is sparse categorical  cross-entropy and the evaluation matrics used here is accuracy.The batch size is of 64 batches and model is trained for 20 epochs with validation split of 0.2

# evaluation metrics

The model is evaluated on the test set using accuarcy as the evaluation matrics

# Conclusion

In this project, we proposed an approach for classifying the MNIST dataset using a sequential model with a Flatten layer and a Dense layer. The model achieved an accuracy of 97.85% on the test set, demonstrating its ability to accurately classify handwritten digits.
