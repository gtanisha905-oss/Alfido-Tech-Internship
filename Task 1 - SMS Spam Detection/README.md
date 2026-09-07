# Task 1 - SMS Spam Detection

## Alfido Tech Artificial Intelligence Internship

### Project Overview
This project focuses on detecting whether an SMS message is Spam or Ham (Not Spam) using Machine Learning and Natural Language Processing (NLP).

### Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib
- TF-IDF Vectorization

### Machine Learning Models
- Logistic Regression
- Random Forest Classifier

### Key Techniques
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- TF-IDF feature extraction
- Stratified train-test split
- 5-Fold Stratified Cross-Validation
- Model evaluation
- Confusion Matrix
- ROC-AUC analysis

### Final Model Performance
The Random Forest model achieved:

- Accuracy: 97.97%
- Precision: 100.00%
- Recall: 83.97%
- F1-Score: 91.29%
- ROC-AUC: 99.36%

### Dataset
SMS Spam Collection Dataset from the UCI Machine Learning Repository.

### Files
- `Task_1_SMS_Spam_Detection.ipynb` - Complete project notebook
- `spam_random_forest_model.pkl` - Trained Random Forest model
- `tfidf_vectorizer.pkl` - TF-IDF vectorizer
- `README.md` - Project documentation
- `Report/` - Project report

### How to Run
Open the Jupyter/Google Colab notebook and run the cells sequentially.

The saved model and TF-IDF vectorizer can be loaded using Joblib for making predictions on new SMS messages.
