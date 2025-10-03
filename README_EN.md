📌 About the Project

This project aims to predict customer churn for the fictitious telecom operator Interconnect using contractual, personal, and service data.

In addition to churn prediction, customer clustering was performed to support segmentation and retention strategies.

## 🗂️ Data Structure

Four datasets were used:

- `personal.csv` → customers' personal information  
- `contract.csv` → contract type and duration, billing method, churn status  
- `internet.csv` → subscribed internet services  
- `phone.csv` → subscribed phone services  

## 🔎 Project Steps

**Exploratory Data Analysis (EDA)**

- Handling missing values  
- Data type conversion  
- Distribution and outlier analysis  
- Correlation study  

**Preprocessing**

- Normalization of numerical variables  
- One-Hot Encoding for categorical variables  
- Train-test split with stratification  

**Modeling**

- Logistic Regression  
- Random Forest  
- Gradient Boosting  

**Evaluation**

- Accuracy, Precision, Recall, F1-Score  
- Confusion Matrix  
- Classification Report  

**Clustering (extra)**

- Dimensionality reduction with PCA  
- Customer grouping using K-Means  

## 📊 Key Results

- Gradient Boosting showed the best test performance.  
- The model can identify customers likely to churn, enabling more effective retention strategies.  
- Clustering revealed behavioral patterns useful for targeted marketing campaigns.  

## 🛠️ Technologies Used

- Python (pandas, numpy, matplotlib, seaborn)  
- scikit-learn  
- PCA & K-Means  
