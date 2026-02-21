# Shop-Smart


## 📌 Project Overview

This project focuses on analyzing e-commerce user behavior data and building a machine learning model to predict whether a user is likely to purchase a product or not based on their browsing and interaction patterns.

The dataset contains detailed user activity information such as:

-Time spent on different types of pages

-Month and weekend activity

-Visitor and traffic-related attributes

The complete workflow includes Exploratory Data Analysis (EDA), feature encoding, model training, and post-pruning of a Decision Tree to improve generalization performance.


## 🎯 Objective

To understand customer behavior using data analysis and build a Decision Tree Classifier that predicts:
- "Will user make a pruchase? (Yes/No)"

## 📂 Dataset Description


<img width="736" height="827" alt="Screenshot 2026-02-21 231412" src="https://github.com/user-attachments/assets/e21128c8-c5d7-4447-8cc2-28520f699487" />



## 🔍 Exploratory Data Analysis (EDA)

During EDA, the following steps were performed:

-Data overview and structure analysis

-Handling missing or inconsistent values

-Distribution analysis of numerical features

-Relationship analysis between user behavior and purchase decision

-Identification of important features influencing revenue


## 🛠️ Data Preprocessing

- Categorical Feature Encoding (Label Encoding/ One-hot Encoding).

- Feature Selection and Feature scaling.

- Train Test split



## 🤖 Machine Learning Model

- Trained a Decision Tree Classifier to predict user purchase behavior.

- Evaluated model performance with accuracy and precision scores



## 🌳 Post-Pruning (Cost Complexity Pruning)

To prevent overfitting:

- Calculated ccp_alpha values

- Trained multiple trees using different alpha values

- Selected the optimal ccp_alpha with the best validation score


## 📈 Results & Insights

- Identified key user behavior patterns that influence purchasing

- Post-pruning significantly reduced overfitting

- Achieved a balanced and interpretable decision tree model

### Accuracy - 0.8888888888888888

### Precision Score - 0.6974063400576369

### Recall Score - 0.5888077858880778

### F1 Score - 0.6385224274406333

