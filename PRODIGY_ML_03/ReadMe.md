# Prodigy Internship Task 3

This repository contains the implementation of a support vector machine (SVM) to classify images of cats and dogs.

## Implementation

Here is a complete and detailed implementation. The code is divided into 3 parts. First one to preprocesses the images and save them to a pickle file. Second code contains the training of model and saving the model. Third part is to test the model on new data.

*Dog&Cat_SVM1.py*

1. **Import Libraries**: Import necessary libraries for file handling, image processing, and data serialization.
2. **List Files in Directory**: List all files in the dataset directory.
3. **Separate Image Paths by Class**: Categorize image paths into separate lists for cats and dogs.
4. **Image Processing Function**: Create a function to read, resize, normalize, and flatten images, then append them with labels to data containers.
5. **Process Cat Images**: Process images of cats using the defined function and assign label 0.
6. **Process Dog Images**: Process images of dogs using the defined function and assign label 1.
7. **Save Processed Data**: Serialize the processed data using `pickle` and save it to a file.

*Dog&Cat_SVM2.py*

1. **Import Libraries**: Import necessary libraries.
2. **Load and Shuffle Data**: Load the preprocessed data from a pickle file and shuffle it.
3. **Prepare Features and Labels**: Separate the features and labels from the data.
4. **Split Data**: Split the dataset into training and testing sets.
5. **Standardize Data**: Standardize the feature values to have zero mean and unit variance.
6. **Perform PCA**: Apply Principal Component Analysis (PCA) to reduce dimensionality while retaining 95% variance.
7. **Grid Search for SVM**: Use GridSearchCV to find the best hyperparameters for the Support Vector Machine (SVM) model.
8. **Save Best Model**: Save the trained SVM model with the best parameters.
9. **Evaluate Model**: Evaluate the model on the test set and print the classification report.
10. **Visualize Predictions**: Display a few random test images with their predicted and actual labels.

*Dog&Cat_SVM3.py*

1. **Import Libraries**: Import necessary libraries.
2. **Preprocess Test Images**: Read, resize, normalize, and flatten the test images, then save the processed data in a pickle file.
3. **Load Pre-trained Model and Test Data**: Load the previously saved SVM model and the preprocessed test data from pickle files.
4. **Separate Features and File Names**: Extract features and file names from the loaded test data.
5. **Standardize Data**: Standardize the feature values to have zero mean and unit variance.
6. **Apply PCA**: Reduce dimensionality of the standardized data using PCA with the number of components previously determined.
7. **Randomly Select Image for Prediction**: Select a random image from the test set, reshape it, and predict its label.
8. **Print and Visualize Prediction**: Print the prediction and display the selected image with its predicted label.


### Link of the dataset

Dataset :- https://www.kaggle.com/c/dogs-vs-cats/data


