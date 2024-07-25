# Image Classification with SVM
This project focuses on classifying images of cats and dogs using a Support Vector Machine (SVM) classifier. The project involves image preprocessing, dimensionality reduction with PCA, and classification to distinguish between 'cat' and 'dog' images.
# Overview
This project follows these steps:

Load Images: Retrieve image file paths from the directories.
Create Dataset: Organize image paths and labels into a DataFrame.
Preprocess Images: Resize and flatten images for model input.
Dimensionality Reduction: Use PCA to reduce the number of features.
Train SVM Model: Train a Support Vector Machine classifier.
Test and Predict: Classify test images and save predictions to a CSV file.
# Dataset
The dataset consists of images categorized into 'cat' and 'dog' classes. It is divided into training and testing directories.
# Data Source
Data-https://www.kaggle.com/c/dogs-vs-cats/data
# Results
The script will output the accuracy of the SVM model and save the test predictions in svm_test_predictions.csv. The CSV file contains:
id,label
1,1
2,0
3,1
4,0
...
id: Identifier for each test image.
label: 1 for 'dog' and 0 for 'cat'.
