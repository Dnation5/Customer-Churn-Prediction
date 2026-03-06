# Customer-Churn-Prediction
An end-to-end customer churn prediction project developed using Python and Scikit-learn. The project includes data cleaning, exploratory data analysis, feature engineering, model comparison (Logistic Regression, Random Forest, Gradient Boosting), and hyperparameter optimization to enhance predictive performance
---

## Project Structure

LoanDefaultRisjPrediction/ <-- project root

├── data/ # Raw dataset

├── notebooks/ # Jupyter notebooks

├── src/ # Python package with reusable functions

├── model / # saved model

├── reports / # Final Report

├── requirements.txt

├── customerchurn_evn / # project environment path

└── README.md


---

## Technologies Used

- Python 3.13.9
- 
- Jupyter Notebook
- 
- pandas, numpy
- 
- scikit-learn
- 
- matplotlib, seaborn

---

## Features

1. **Data Loading & Preprocessing**
   - Drop unnecessary columns (`customer id`)
   - Encode categorical variables (One-Hot Encoding)
   - Scale features (StandardScaler)

2. **Exploratory Data Analysis (EDA)**
   - Class distribution visualization
   - Correlation heatmaps

3. **Machine Learning Models**
   - **Logistic Regression** for baseline modeling
   - **Random Forest Classifier** for model comparison
   - **Gradient Boosting Classifier** for model comparison

4. **Evaluation**
   - Confusion matrix 
   - Recall, Precision, F1 Score
   - ROC_AUC
   - Feature Importance for Random Forest

5. **Final Report**

    - See reports/final_report.pdf
   

---

