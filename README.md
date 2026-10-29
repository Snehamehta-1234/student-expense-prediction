# Student Monthly Expense Prediction

Project Overview
This project uses Machine Learning to predict a student's monthly expenses based on different spending categories. It analyzes expenses such as rent, utilities, food, travel, clothing, and outings to estimate the total monthly expense.

Objectives
- Predict monthly student expenses using Machine Learning.
- Analyze different expense categories.
- Compare multiple regression models.
- Build an interactive web application for expense prediction.

Technologies Used
- Python
- Pandas and NumPy
- Scikit-learn
- Matplotlib
- Streamlit
- Flask
- Joblib
- Google Colab

## 🤖 Machine Learning Models
The following models were trained and evaluated:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

Based on the recorded evaluation results, **Linear Regression achieved the highest R² score of approximately 0.969** among the three models.

 Input Features
The model uses these six expense categories:
- Rent
- Utilities
- Food Expense
- Travel Cost
- Clothing
- Outings

The target variable is **Monthly Expense**.

Web Application
A Streamlit application was created to let users enter expense values and receive a predicted monthly expense.

The notebook also includes a Flask API implementation for making predictions.

How to Run
1. Open the notebook in Google Colab.
2. Upload or connect the required student expense dataset.
3. Run the notebook cells in order to train and evaluate the models.
4. Run the Streamlit application after generating the trained model file.
5. Enter expense values to obtain a prediction.

 📁 Project File
- `MACHINE LEARNING PROJECT WORKNG.ipynb` — notebook containing data preparation, model training, evaluation, and deployment setup.

 Note
The dataset and trained model file must be available in the required location before running the complete application.

Author
Sneha Mehta
