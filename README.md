# Breast Cancer Detection

## Project Overview
This project implements a machine learning model to detect breast cancer using the Wisconsin Breast Cancer dataset. The model classifies breast masses as either Malignant (M) or Benign (B) based on various features extracted from digitized images of fine needle aspirate (FNA) of breast masses.

## Dataset Description
The dataset contains features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. The features describe characteristics of the cell nuclei present in the image. Key features include:

- Radius (mean of distances from center to points on the perimeter)
- Texture (standard deviation of gray-scale values)
- Perimeter
- Area
- Smoothness (local variation in radius lengths)
- Compactness (perimeter² / area - 1.0)
- Concavity (severity of concave portions of the contour)
- Concave points (number of concave portions of the contour)
- Symmetry
- Fractal dimension

For each feature, the dataset provides the mean, standard error, and "worst" or largest (mean of the three worst/largest values) values, resulting in 30 features.

## Implementation Details
The project is implemented in Python using the following libraries:
- pandas and numpy for data manipulation
- scikit-learn for machine learning algorithms
- matplotlib and seaborn for data visualization

The implementation includes:
1. Data preprocessing and exploratory data analysis
2. Feature scaling using StandardScaler
3. Model training using Logistic Regression
4. Model evaluation using various metrics:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - ROC-AUC score


## Model Performance
The model achieves high accuracy in classifying breast masses, with detailed performance metrics available in the notebook.
