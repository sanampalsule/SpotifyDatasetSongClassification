# Spotify Dataset Song Classification

## Overview: 
The notebook demonstrates a music genre classification project using a dataset of songs from two genres: Hip-Hop and Rock. The goal is to build a machine learning model that can predict the genre of a song based on its audio features. The notebook explores various techniques such as data preprocessing, feature analysis, dimensionality reduction, and model training to achieve this task.

## Technical Components: 


- Python: The primary programming language used for the entire project.
- Jupyter Notebook: The interactive development environment (IDE) used to create and run the code.
- pandas: Used for data manipulation, loading, and analysis of the datasets.
- NumPy: Used for numerical computations and array operations.
- scikit-learn (sklearn):
  - StandardScaler: Used for standardizing the audio features.
  - PCA: Used for dimensionality reduction of the audio features.
  - train_test_split: Used for splitting the dataset into training and testing sets.
  - DecisionTreeClassifier: Used as one of the classification models.
  - LogisticRegression: Used as another classification model.
  - accuracy_score, confusion_matrix, classification_report: Used for model evaluation metrics.
  - KFold: Used for k-fold cross-validation.
- matplotlib: Used for creating visualizations, such as plots and charts.
- seaborn: Used for enhanced data visualization, such as the correlation matrix heatmap.
