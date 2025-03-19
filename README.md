# Route Difficulty Analysis to Istinye University  

This project analyzes the difficulty of routes from different neighborhoods of istanbul to Istinye University. The goal is to classify routes as challenging, moderate, or easy using different machine learning models.  

## Project Overview  
We applied multiple machine learning algorithms to find the best-performing model for route difficulty classification. The models were tested with and without hyperparameter tuning and cross-validation to compare their effectiveness.  

## Project Structure  
- data_processing.ipynb → Prepares and processes the dataset.  
- model_training.ipynb → Trains and compares different models.  

## Machine Learning Models Used  
- Supervised Models:  
  - Random Forest  
  - Logistic Regression  
  - Gradient Boosting  
- Unsupervised Models:  
  - K-Means Clustering  
- All models were evaluated with and without hyperparameter tuning and cross-validation.  

## How to Use  
1. Run data_processing.ipynb to clean and prepare the dataset.  
2. Run model_training.ipynb to train different models and compare results.  

## Tools & Libraries  
- Python (Google Colab)  
- Pandas, NumPy (Data processing)  
- Scikit-learn (Machine learning)  

This project provides insights into the accessibility of Istinye University from different areas and helps identify the best model for route difficulty classification.  
Feel free to explore the notebooks!
