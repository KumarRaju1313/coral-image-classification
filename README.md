# Coral Image Classification

## Project Description
This project focuses on classifying coral images into two categories: healthy corals and bleached corals. The images undergo various preprocessing steps, including resizing, duplicate removal, augmentation, conversion to grayscale, and adjustments in contrast and brightness. Several machine learning models were trained and optimized using hyperparameter tuning to achieve the best classification accuracy.

## Dataset
The dataset consists of images categorized into two folders: `healthy_corals` and `bleached_corals`. Images are preprocessed and augmented to increase the dataset size and improve model performance.

## Installation
To get started with this project, you need to install the required libraries.

## Preprocessing
The images undergo several preprocessing steps:

1. **Loading and Resizing**: Images are resized to 64x64 to reduce computational load.
2. **Duplicate Removal**: Duplicate images are identified and removed.
3. **Augmentation**: Images are augmented using techniques like mirroring and rotation.
4. **Grayscale Conversion**: Images are converted to grayscale.
5. **Contrast and Brightness Adjustment**: The contrast and brightness of the images are adjusted.

## Models and Hyperparameter Tuning
The following machine learning models were trained and optimized using GridSearchCV for hyperparameter tuning:

### 1. Support Vector Machine (SVM)
### 2. Random Forest
### 3. K-Nearest Neighbors (KNN)
### 4. Logistic Regression

```

## Evaluation Metrics
The models were evaluated using the following metrics:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## Results
The results of the hyperparameter tuning and model evaluation are printed in the script output. The best model can be selected based on the test accuracy and other evaluation metrics.

