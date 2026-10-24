# Campus Placement Prediction and Student Employability Analysis Using Apache Spark and PySpark

## Overview

This project uses Apache Spark and PySpark to analyze student employability and predict campus placement outcomes using machine learning. It processes a dataset containing approximately 100,000 student records and explores the relationship between academic performance, technical skills, internships, projects, certifications, and placement outcomes.

The project implements classification models to predict whether a student is likely to be placed, regression models to estimate expected salary in Lakhs Per Annum (LPA), and K-means clustering to identify student employability profiles.

## Objectives

1. To implement distributed machine learning using Apache Spark and PySpark by processing student records using Spark DataFrames and Spark ML pipelines.
2. To develop and compare Logistic Regression, Decision Tree, Support Vector Machine (SVM), and Naive Bayes models for placement classification.
3. To develop salary prediction models using Linear Regression and Decision Tree Regression.
4. To evaluate machine learning models using appropriate classification and regression metrics.
5. To analyze placement-related factors using exploratory data analysis, correlation heatmaps, and K-means clustering.

## Technologies Used

- **Apache Spark** – Large-scale data processing and machine learning.
- **PySpark** – Python interface for Spark DataFrames and ML pipelines.
- **Python** – Programming language.
- **Jupyter Notebook** – Development and execution environment.
- **Pandas, NumPy, Matplotlib, Seaborn** – Data analysis and visualization, where used.

## Machine Learning Models

### Placement Classification
The following algorithms are implemented and compared:

- Logistic Regression
- Decision Tree Classifier
- Support Vector Machine (SVM)
- Naive Bayes

Evaluation metrics include Accuracy, Precision, Recall, F1-score, and Confusion Matrix.

### Salary Prediction
The following regression algorithms are used to estimate expected salary:

- Linear Regression
- Decision Tree Regression

Models are evaluated using R², Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE).

### Student Clustering
K-means clustering is used to group students into employability profiles based on relevant academic and skill-related attributes. Silhouette scores are used to compare clustering configurations.

## Project Workflow

1. Load the student dataset into Spark DataFrames.
2. Perform data cleaning and preprocessing.
3. Conduct exploratory data analysis and generate visualizations.
4. Prepare features and train placement classification models.
5. Train and evaluate salary regression models.
6. Compare model performance using evaluation metrics.
7. Apply K-means clustering to identify student profiles.
8. Analyze and visualize the final results.

## Results and Analysis

The project compares multiple machine learning models to identify suitable approaches for placement classification and salary prediction. It also uses clustering to explore differences in student employability profiles.

Refer to the project notebook and report for the actual model evaluation results, visualizations, and detailed analysis.

## Project Files

- **Jupyter Notebook:** Contains the implementation, preprocessing, model training, evaluation, and visualizations.
- **Project Report:** Contains the problem statement, objectives, methodology, implementation details, screenshots, result analysis, and conclusion.
- **Dataset:** Student records used for placement classification, salary prediction, and clustering.

## How to Run

1. Clone this repository:

   ```bash
   git clone <your-repository-url>
   ```

2. Install the required dependencies:

   ```bash
   pip install pyspark pandas numpy matplotlib seaborn jupyter
   ```

3. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open the project notebook and update the dataset path to match your local file location.

5. Run the notebook cells sequentially to execute the project.

Ensure that Java and Apache Spark are configured correctly for your environment.

## Dataset

The project uses a student placement dataset containing academic, skill-related, and placement information.

**Dataset Source:** : https://www.kaggle.com/datasets/likithagedipudi/campus-placement-prediction?resource=do

Note: If the dataset is synthetic, the results represent patterns in the generated data and should not be interpreted as guaranteed real-world placement outcomes.

## Author

Putluru Om Sai Nandan Reddy

B.Tech Computer Science and Engineering

Lovely Professional University
