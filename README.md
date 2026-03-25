# Credit Card Fraud Detection

## Project Overview
This project aims to detect fraudulent credit card transactions using machine learning models.

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting

## Problem Statement
Credit card fraud detection is a highly imbalanced classification problem where fraudulent transactions are rare.

## Approach
- Data preprocessing & scaling
- Handling imbalanced data (undersampling)
- Model training & evaluation
- Performance comparison

## Evaluation Metrics
- Precision
- Recall
- F1 Score
- ROC Curve

## Results
Random Forest and Gradient Boosting performed best with high recall and F1-score.

## 📂Dataset
- Dataset is not included due to size.  
- You can download it from: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

## Key Insight
Recall is more important than accuracy in fraud detection because missing fraud cases is costly.

## Future Improvements
- Use SMOTE for better data balancing
- Hyperparameter tuning
- Deploy model using Streamlit or FastAPI
- Add real-time fraud detection system

## How to Run

### Clone the repository
git clone https://github.com/your-username/credit-card-fraud-detection.git

### Navigate to project folder
cd credit-card-fraud-detection

### Install dependencies
pip install -r requirements.txt

### Run Jupyter Notebook
jupyter notebook

## Author

Adarsha G C