# Prodigy Internship Task 4

This repository contains the implementation of a hand gesture recognition model that can accurately identify and classify different hand gestures.


## Implementation
1. Import Libraries: Import necessary libraries for data manipulation, preprocessing, model training, and visualization.
2. Mount Google Drive: Mount Google Drive to access the dataset stored in a zip file.
3. Extract Dataset: Extract the dataset from the zip file into a specified directory.
4. Preprocess Images: Resize images, normalize pixel values, and expand dimensions to fit the model input.
5. Encode Labels: Encode categorical labels into numerical values and convert them to one-hot encoded vectors.
6. Split Data: Split the dataset into training and testing sets.
7. Define CNN Model: Define a Convolutional Neural Network (CNN) model architecture for image classification.
8. Compile Model: Compile the model with an optimizer, loss function, and evaluation metrics.
9. Train Model: Train the CNN model on the training data, with validation on the test data.
10. Evaluate Model: Evaluate the model's performance on the test set and print accuracy and loss.
11. Visualize Training History: Plot the training and validation loss and accuracy over epochs.
12. Make Predictions: Predict the labels for the test set and compare with true labels.
13. Visualize Predictions: Plot sample test images with their true and predicted labels to visually inspect model performance.


### Link of the dataset

Dataset :-  https://www.kaggle.com/gti-upm/leapgestrecog

The hand gestures present in this dataset are 01_palm, 02_l, 03_fist, 04_fist_moved, 05_thumb, 06_index, 07_ok, 08_palm_moved, 09_c, 10_down.

