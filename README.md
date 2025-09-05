# 💳 Credit Card Default Prediction

📌 Project Overview

This project predicts whether a credit card customer will default on their payment next month using Machine Learning.
We use the UCI Credit Card Default Dataset, perform Exploratory Data Analysis (EDA), and implement a Logistic Regression model for prediction.

✅ Features of this Project

✔️ Data Cleaning & Preprocessing
✔️ Exploratory Data Analysis (EDA) with Visualizations
✔️ Model Building using Logistic Regression
✔️ Model Evaluation using Accuracy Score
✔️ Future improvements: Add more models like Decision Tree, Random Forest, XGBoost


📊 Dataset Information

Source: UCI Credit Card Dataset
Rows: 30,000
Columns: 25 (includes demographics, bill amount history, payment history, etc.)
Target Column: default.payment.next.month
1 → Customer will default
0 → Customer will not default


🔍 Exploratory Data Analysis (EDA)

✔ Checked missing values (✅ No missing values)
✔ Removed ID column (not useful for prediction)
✔ Visualized target distribution
✔ Plotted credit limit, age, and other features using boxplots

Example EDA Visualization


🛠 Tech Stack

Language: Python 🐍
Libraries:
pandas, numpy → Data processing
matplotlib, seaborn → Visualization
scikit-learn → Machine Learning
Tool: Jupyter Notebook

🤖 Machine Learning Model

Model Used: Logistic Regression
Why Logistic Regression?
Simple & interpretable
Works well for binary classification
Accuracy Achieved: ~81%


📈 Model Workflow

Load Dataset
Remove ID column
Split Data → 80% Train, 20% Test
Train Logistic Regression Model
Evaluate Model → Accuracy Score


🔗 Dataset Access

Due to file size limitations on GitHub, download the dataset from: https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset?resource=download

🚀 Future Improvements

Add Decision Tree and Random Forest
Implement Hyperparameter Tuning
Deploy model using Streamlit or Flask

💡 Note
I will soon build an end-to-end project based on this concept with advanced ML models & deployment! Stay tuned. 🚀

🔥 If you like this project, give it a ⭐ on GitHub!
