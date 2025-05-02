# Employee Retention Prediction

## Project Overview

This project aims to predict employee attrition using machine learning models. It explores various features related to employee demographics, job satisfaction, work-life balance, and more to identify factors that contribute to employee turnover.

## Dataset

The project utilizes the "Human_Resources.csv" dataset, which contains information about employees. The dataset is assumed to be located in the `/content/drive/MyDrive/Data Science for Business/` directory within your Google Drive.

## Libraries Used

The project utilizes several Python libraries, including:

* pandas
* numpy
* seaborn
* matplotlib
* sklearn (for data preprocessing, model training, and evaluation)
* tensorflow (for deep learning model)

## Project Workflow

1. **Problem Statement and Business Case:** The project starts by defining the problem of employee attrition and its impact on businesses.

2. **Import Libraries and Datasets:** Necessary libraries are imported, and the dataset is loaded into a pandas DataFrame.

3. **Visualize Dataset:** Exploratory data analysis is performed to understand the data distribution, identify potential relationships between features, and visualize key insights.

4. **Create Testing and Training Dataset & Perform Data Cleaning:** The dataset is split into training and testing sets, and data cleaning techniques like one-hot encoding and scaling are applied.

5. **The Intuition Behind Classification Models:** An overview of logistic regression, artificial neural networks, and random forest classifiers is provided.

6. **Understand How to Assess Classification Models:** Key metrics for evaluating classification models, such as accuracy, precision, recall, and F1-score, are discussed.

7. **Train and Evaluate a Logistic Regression Classifier:** A logistic regression model is trained and evaluated using the prepared dataset.

8. **Train and Evaluate a Random Forest Classifier:** A random forest classifier is trained and evaluated using the prepared dataset.

9. **Train and Evaluate a Deep Learning Model:** A deep learning model using TensorFlow and Keras is trained and evaluated using the prepared dataset.


## Usage

To run this project, you need to:

1. **Mount your Google Drive** to access the dataset. You can do this using the following code snippet: from google.colab import drive drive.mount('/content/drive')

2. **Load the dataset** using pandas: python employee_df = pd.read_csv('/content/drive/MyDrive/Data Science for Business/Human_Resources.csv')
  
3. **Follow the code cells in the notebook** to execute the data preprocessing, model training, and evaluation steps.


## Results

The project evaluates the performance of each model using classification metrics and visualizes the results using confusion matrices and performance reports. You can observe the accuracy, precision, recall, and F1-score of each model to assess their effectiveness in predicting employee attrition.


## Conclusion

This project demonstrates the application of machine learning techniques to predict employee attrition. By analyzing employee data, the project identifies key factors that influence attrition and provides insights to help businesses develop strategies to retain their workforce.
