# Iris-Classification
This repository contains a machine learning model for classifying Iris flowers into three species: Setosa, Versicolor, and Virginica. The model achieves an accuracy of 93.3% on a test dataset.

## Key Features:
Data Preprocessing: The dataset underwent preprocessing steps to handle missing values, if any, and to ensure uniformity in data format.

Data Visualization: Exploratory Data Analysis (EDA) techniques were applied to gain insights into the distribution of features and the relationships between them. Visualization aids such as histograms, scatter plots, and pair plots were utilized.

Label Encoding: Categorical target variable 'Species' was encoded using LabelEncoder from scikit-learn to convert it into numerical values for model training.

Model Training: Logistic Regression algorithm from scikit-learn was employed to build the classification model. The model was trained on a training dataset and evaluated using a separate test dataset.

User Interaction: A user-friendly interface allows users to input values for Sepal Length, Sepal Width, Petal Length, and Petal Width, and receive the predicted Iris species based on the trained model.

## Usage
1. Clone the repository.
2. Run `iris_classification_model.ipynb` in a Jupyter environment.
3. Input values for Sepal Length, Sepal Width, Petal Length, and Petal Width to predict the Iris species.
  
## Files Included
- `iris_classification_model.ipynb`: Jupyter Notebook with code for data preprocessing, model training, and evaluation.
- `iris.csv`: Dataset containing features and target variable.

## Dependencies
- Python 3.x
- scikit-learn
- pandas
- numpy

## Credits
- Dataset sourced from the UCI Machine Learning Repository.
- Special thanks to scikit-learn and pandas libraries for their valuable tools and functionalities.


