# Diabetes-Prediction-with-ML

**🔗Project Link:** [Diabetes-Prediction-with-ML](https://github.com/Sanskriti1102/Diabetes-Prediction-with-ML/blob/main/Diabetes%20Prediction%20with%20ML%20on%20PIMA%20Diabetes%20Dataset.ipynb)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Library](https://img.shields.io/badge/Library-scikit--learn%2C%20NumPy%2C%20Pandas-green)

## Problem Statement

As part of my AI/ML internship at InternPe, I took on a project to develop a diabetes prediction model using Support Vector Machines (SVM). The objective was to utilize machine learning techniques to predict diabetes based on patient data and provide a foundation for future healthcare applications.

## Description

In this project, I accomplished the following key tasks:

1. **Importing Libraries**: The script starts by importing necessary libraries, including NumPy, Pandas, and scikit-learn's modules for data preprocessing, model selection, and metrics.

2. **Loading the Dataset**: I loaded the diabetes dataset from a CSV file, giving an overview by displaying the first and last few rows.

3. **Data Exploration**: Basic data exploration was conducted, examining dataset dimensions, statistical summaries, and value counts in specific columns.

4. **Data Standardization**: To prepare the data for SVM, feature standardization was performed using the `StandardScaler` from scikit-learn, a crucial step for effective machine learning.

5. **Splitting Data**: The dataset was divided into training and testing sets, enabling model evaluation on unseen data.

6. **Support Vector Machine (SVM)**: A SVM classifier with a linear kernel was created using scikit-learn's `svm.SVC(kernel='linear')`.

7. **Model Training**: The SVM classifier was trained on the training dataset using the `fit` method.

8. **Model Evaluation**: Predictions were generated for both training and test datasets, and model performance was assessed using accuracy scores from `accuracy_score`.

9. **Input Data for Prediction**: An example input data point was constructed as a tuple, converted to a NumPy array, and reshaped to match the prediction format.

10. **Standardizing Input Data**: The input data was standardized using the same scaling transformation applied to the training data.

11. **Prediction**: The trained SVM classifier predicted the presence or absence of diabetes for the given input data.

12. **Output Feedback**: Depending on the prediction result, appropriate feedback was provided, indicating whether diabetes was detected.

This project serves as a foundational framework for diabetes prediction, offering potential applications in healthcare risk assessment.

## How It's Done

### Libraries Used
- Python 3.8+
- Pandas 1.3.3
- NumPy 1.21.2
- scikit-learn 0.24.2

### Data Source
The dataset used in this project was obtained from [diabetes.csv dataset link](https://github.com/Sanskriti1102/Diabetes-Prediction-with-ML/blob/main/diabetes.csv), containing patient data and diabetes outcomes.

### Running the Project
1. Clone this repository to your local machine.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the Jupyter Notebook or Python script to execute the diabetes prediction analysis.

### Happy coding! 😊🩺

# Task given by InternPe.

