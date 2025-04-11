
# 🏦 Loan Status Prediction using Machine Learning

## 📌 Project Overview  
This machine learning project predicts whether a loan application will be approved or not based on applicant information. The process involves data cleaning, encoding, visualization, model building using Support Vector Machine (SVM), and evaluation.

---

## 📂 Dataset Overview  
The dataset contains details about loan applicants with the following features:

- Gender  
- Married  
- Dependents  
- Education  
- Self_Employed  
- ApplicantIncome  
- CoapplicantIncome  
- LoanAmount  
- Loan_Amount_Term  
- Credit_History  
- Property_Area  
- Loan_Status (Target: 1 = Approved, 0 = Not Approved)

---

## 🛠️ Technologies Used  
- Python  
- Pandas – for data loading and preprocessing  
- Seaborn – for visualizations  
- Scikit-learn – for model training and evaluation

---

## ⚙️ Process Workflow  

### ✅ Data Loading  
- Loaded dataset using Pandas  
- Performed basic inspection and null value treatment

### ✅ Data Preprocessing  
- Dropped rows with missing values  
- Label encoded categorical variables  
- Replaced `3+` dependents with numerical value `4`  
- Converted categorical columns (Gender, Married, Education, etc.) to numerical format

### ✅ Data Visualization  
- Plotted loan status distribution by Education and Marital Status using Seaborn

### ✅ Model Building  
- Used Support Vector Machine (SVM) with linear kernel  
- Split the dataset into training and test sets using `train_test_split`

### ✅ Model Evaluation  
- Evaluated model performance using:
  - Accuracy Score on training and test data
  - Predictions made using the trained classifier

---

## 📞 Connect with Me  
For any queries or collaboration opportunities, feel free to reach out:

📧 Email: bariv219@gmail.com  
🔗 LinkedIn: [Vaibhav Bari](https://www.linkedin.com/in/vaibhav-bari/)


