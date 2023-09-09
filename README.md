# Diabetes-Prediction-with-ML

**Link :**
🔗https://github.com/Sanskriti1102/Diabetes-Prediction-with-ML/blob/main/Diabetes%20Prediction%20with%20ML%20on%20PIMA%20Diabetes%20Dataset.ipynb

**Code Description:**

This Python script demonstrates the process of diabetes detection using Support Vector Machines (SVM). It follows a step-by-step procedure for data preprocessing, model training, and prediction. Below is a breakdown of the code:

1. **Importing Libraries**: The script starts by importing necessary libraries, including NumPy, Pandas, and scikit-learn's modules for data preprocessing, model selection, and metrics.

2. **Loading the Dataset**: It loads the diabetes dataset from a CSV file using Pandas and displays the first few and last few rows of the dataset to provide an overview.

3. **Data Exploration**: The code performs basic data exploration tasks, such as checking the shape of the dataset, displaying statistical measures, and counting occurrences of values in specific columns.

4. **Data Standardization**: The script standardizes the feature data using the `StandardScaler` from scikit-learn. Standardization removes the mean and scales the data to unit variance, which is a common preprocessing step for machine learning models.

5. **Splitting Data**: The dataset is split into training and testing sets using the `train_test_split` function. This ensures that the model can be evaluated on unseen data.

6. **Support Vector Machine (SVM)**: It creates an SVM classifier with a linear kernel using `svm.SVC(kernel='linear')`. SVM is a popular algorithm for binary classification tasks like diabetes prediction.

7. **Model Training**: The SVM classifier is trained on the training dataset using the `fit` method.

8. **Model Evaluation**: The code predicts labels for both the training and test datasets and calculates accuracy scores using `accuracy_score` to assess the model's performance.

9. **Input Data for Prediction**: An example input data point is created as a tuple and converted to a NumPy array. It is then reshaped to match the expected format for prediction.

10. **Standardizing Input Data**: The input data is standardized using the same scaling transformation applied to the training data.

11. **Prediction**: The trained SVM classifier predicts whether the given input data indicates the presence or absence of diabetes.

12. **Output Feedback**: Depending on the prediction result, the code provides appropriate feedback, indicating whether diabetes has been detected or not.

This code serves as a basic framework for diabetes prediction using SVM. It can be further extended and optimized for real-world applications, such as building a web application for diabetes risk assessment.

---
Task 1 given by InternPe
