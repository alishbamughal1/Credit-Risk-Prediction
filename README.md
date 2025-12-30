# Loan Prediction using Machine Learning

##  Objective
The objective of this project is to predict whether a loan applicant is likely to default on a loan based on their personal, financial, and loan-related information.

---

##  Dataset
The dataset used in this project is the **Loan Prediction Dataset**, which contains two files:

- `train.csv` – used for training and evaluating the model
- `test.csv` – used for generating final predictions

 **Dataset Link (Kaggle):**  
https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset

---

##  Technologies & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
  

---

##  Project Workflow

### 1. Data Cleaning
- Handled missing values using mean (numerical) and mode (categorical)
- Encoded categorical variables using Label Encoding
- Scaled numerical features using StandardScaler

---

### 2. Exploratory Data Analysis (EDA)
- Visualized important features such as:
  - Loan Amount
  - Applicant Income
  - Education
- Used bar plots and histograms to understand data distribution

---

### 3. Model Training
Two classification models were trained:
- Logistic Regression
- Decision Tree Classifier

---

### 4. Model Evaluation
Models were evaluated using:
- Accuracy Score
- Confusion Matrix

---

### 5. Final Prediction
- The trained model was used to predict loan approval status on `test.csv`
- Predictions were saved in a CSV file:
  - `final_loan_predictions.csv`

---

## 6. Results
The models successfully classified loan approval status and provided reasonable accuracy. Logistic Regression performed well for this binary classification problem.

---
