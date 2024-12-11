# Churn_Analysis
Telecom Churn analysis with visualization

![giphy](https://github.com/user-attachments/assets/85deb104-a87a-423f-88c5-236d301f0dba)




# Overview

This project focuses on analyzing customer churn to identify patterns and insights that help businesses improve customer retention. The analysis utilizes machine learning techniques and statistical analysis to predict which customers are likely to leave a company or service, based on various factors.

Objectives

The primary objectives of this project are:

To explore and preprocess customer data.

To identify key factors influencing customer churn.

To build and evaluate machine learning models for churn prediction.

To provide actionable insights for reducing churn.

Features

Exploratory Data Analysis (EDA): Visualizations and statistical summaries to understand customer behavior.

Data Preprocessing: Handling missing values, feature scaling, encoding categorical variables, and data splitting.

Machine Learning Models: Training and evaluation of models such as Logistic Regression, Decision Trees, Random Forest, and Gradient Boosting.

Model Evaluation Metrics: Includes accuracy, precision, recall, F1-score, and ROC-AUC curve.

Feature Importance Analysis: Identifies the most significant features affecting customer churn.

Dataset

The dataset used for this project includes customer demographic information, account details, and service usage statistics. Key features may include:

Customer ID: Unique identifier for each customer.

Demographic Details: Age, gender, location, etc.

Account Information: Contract type, tenure, monthly charges, etc.

Service Usage: Internet service, phone service, etc.

Churn: Binary variable indicating if the customer has churned (1) or not (0).

# 🔀Workflow

Data Loading and Exploration

Importing the dataset and inspecting its structure.

Summarizing key statistics and identifying potential issues.

Data Preprocessing

Handling missing values.

Encoding categorical variables.

Splitting the dataset into training and test sets.

Exploratory Data Analysis (EDA)

Visualizing the distribution of features.

Analyzing correlations between features and churn.

Model Training and Evaluation

Training multiple machine learning models.

Comparing performance metrics.

Selecting the best-performing model for deployment.

Feature Importance and Insights

Identifying the most significant predictors of churn.

Providing actionable recommendations.

# 🔑Key Insights

Customers with longer tenures are less likely to churn.

High monthly charges correlate with increased churn.

Contract type and internet service type significantly influence customer retention.

# 📊Results

The best-performing model achieved:Random Forest

Accuracy: 79

F1-Score: 65

ROC-AUC Score: 86



# 🛠️Tools and Libraries

-Python

-Pandas

-NumPy

-Matplotlib

-Seaborn

-Scikit-learn

-XGBClassifier

-Random Forest

-Smote

# How to Use

Clone the repository:
```html
<p> git clone https://github.com/HikmetCTK/Churn_Analysis.git </p>
```
Open the Jupyter Notebook churn-analysis.ipynb.

Follow the code cells to reproduce the analysis and results.

Modify the code or dataset to suit your use case.

# Future Enhancements:

Integrate additional features such as customer feedback or social media sentiment.

Experiment with advanced models like neural networks.

Deploy the best-performing model as a web application.

# Conclusion

This project demonstrates the process of analyzing customer churn using machine learning techniques. By understanding the factors that lead to churn, businesses can take proactive steps to improve customer retention and satisfaction.

For any questions or feedback, feel free to reach out or open an issue in the repository.
