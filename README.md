
# Loan Default Risk Prediction 🏦📊

A machine learning project to predict loan approval status based on applicant financial and personal information. This model aids lenders in automating decisions and assessing applicant risk with higher accuracy.

---

## 🚨 Problem Statement

Financial institutions need to make fast and reliable decisions about whether to approve a loan application. Manual assessment is time-consuming and can lead to inconsistencies. The goal is to build a predictive model that classifies whether a loan should be approved (Y/N) based on historical application data.

---

## ⚠️ Challenges Addressed

- Handling missing and inconsistent values across various features  
- Managing outliers in numerical data (e.g., income and loan amount)  
- Encoding categorical variables for model compatibility  
- Balancing data distribution for target classes  
- Selecting appropriate models (Logistic Regression, Random Forest, etc.)
- Preventing overfitting using cross-validation and tuning

---

## 📚 Dataset Information

- **Source**: Loan prediction dataset from analytics competitions  
- **Size**: ~600 observations  
- **Columns**:
  - `Loan_ID`, `Gender`, `Married`, `Dependents`, `Education`, `Self_Employed`
  - `ApplicantIncome`, `CoapplicantIncome`, `LoanAmount`, `Loan_Amount_Term`, `Credit_History`
  - `Property_Area`, `Loan_Status` (Target)

---

## 🧰 Technologies Used

- **Python**
- **Pandas**, **NumPy** — Data wrangling
- **Matplotlib**, **Seaborn** — Visualization
- **Scikit-learn** — Modeling and Evaluation
- **Jupyter Notebook**

---

## 🔄 Project Workflow

1. **Import Libraries & Load Data**
2. **Exploratory Data Analysis (EDA)**
   - Univariate & bivariate analysis
   - Missing value heatmaps, distribution plots
3. **Data Cleaning**
   - Imputation, outlier handling using IQR method
4. **Feature Engineering**
   - Encoding categorical variables (Label/One-Hot)
5. **Model Building**
   - Logistic Regression, Decision Tree, Random Forest
6. **Evaluation**
   - Accuracy, Confusion Matrix, Cross-Validation
7. **Prediction on New Data**

---

## 💾 Installation & Usage

```bash
# Clone the repo
git clone https://github.com/yourusername/loan-prediction.git

# Navigate into the project
cd loan-prediction

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook Loan_prediction.ipynb
