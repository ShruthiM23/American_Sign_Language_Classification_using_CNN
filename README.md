# American_Sign_Language_Classification_using_CNN

# Problem Statement:

This is an internship project at MedTourEasy wherein I have developed a Convolution Neural Network based Image Classification to predict 3 signs(A,B and C).

# Project Workflow and observations:

1. We divided the data into training and test sets with 1600 and 400 images respectively.
2. Visualised the training data and familiarised with the sign symbols.
3. Labels 'A', 'B' and 'C' are encoded as 0, 1, and 2, respectively for both train and test datasets.
4. Defined a convolutional neural network to classify the data.
5. Compiled the model with the 'adam' optimizer, 'categorical_crossentropy' as the loss function, and 'accuracy' as a metric.
6. Trained the data with the arguments x_train,y_train_encoded,epochs=2.
7. The model is a good fit with an accuracy of ~99% on both the train and test datasets.
8. Visualised the model prediction mistakes which were only 2 misclassifications.

# Visualize A,B,C images from the training data

![image](https://user-images.githubusercontent.com/85027425/132130691-8e5de54d-6612-4641-ad9a-3682f85dba6c.png)

# Visualize the misclassified images

![image](https://user-images.githubusercontent.com/85027425/132130739-e135749c-e3f4-4ef5-b2ac-d134605439d7.png)

