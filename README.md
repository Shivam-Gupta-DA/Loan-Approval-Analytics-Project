# 🏦 Loan Approval Analysis  

## 📌 Project Overview  
This project conducts an **Exploratory Data Analysis (EDA)** on a **home loan approval dataset** to uncover key patterns and insights related to loan approvals. The dataset, sourced from **Skill Circle**, contains various attributes influencing loan decisions. The focus is on **data exploration, visualization, and hypothesis testing**.  

---

## 📊 Dataset Overview  
The dataset consists of **12 key attributes** related to loan approval:  

| Column | Description |
|--------|------------|
| `Loan_ID` | Unique loan identifier |
| `Gender` | Applicant's gender (Male/Female) |
| `Married` | Marital status of the applicant |
| `Dependents` | Number of dependents the applicant has |
| `Education` | Graduate or Non-Graduate |
| `Self_Employed` | Whether the applicant is self-employed |
| `ApplicantIncome` | Applicant's income level |
| `CoapplicantIncome` | Co-borrower's income level |
| `LoanAmount` | Amount of loan requested |
| `Loan_Amount_Term` | Duration for which the loan is sanctioned |
| `Credit_History` | Loan repayment history |
| `Property_Area` | Applicant's area type (Urban, Semi-Urban, Rural) |

---

## 🎯 Project Objectives  
✔ Perform **Exploratory Data Analysis (EDA)** on loan approval data  
✔ Identify **factors influencing loan approvals**  
✔ Test hypotheses related to **self-employment, location, and loan amounts**  
✔ Provide **recommendations for improving loan approval strategies**  

---

## 🛠️ Tools & Technologies Used  
- 🐍 **Python**  
- 🏷️ **Pandas**  
- 📊 **Matplotlib & Seaborn**  
- 📈 **Data Visualization**  
- 📓 **Jupyter Notebook**  

---

## 🏗️ Key Steps Performed  

### 📌 Task 1: **Data Exploration**  
✅ Load and inspect the dataset  
✅ Handle missing values and outliers  
✅ Summarize key statistics (mean, median, standard deviation)  

### 📌 Task 2: **Data Visualization**  

📍 **Univariate Analysis**  
- Histograms for numeric variables  
- Box plots to detect outliers  
- Bar charts for categorical variables  

📍 **Bivariate Analysis**  
- Scatter plots to explore relationships  
- Pair plots to visualize interactions  
- Box plots & violin plots for categorical vs. numeric data  

📍 **Multivariate Analysis**  
- Correlation heatmap to identify relationships  
- Stacked bar charts for categorical distributions  

---

## 🔬 Hypothesis Testing  

### 📍 Hypothesis 1: **Self-employed applicants have a lower approval rate compared to salaried individuals**  
✅ **Validation**: Violin plots show that self-employed individuals tend to receive **fewer loan approvals**.  

### 📍 Hypothesis 2: **Applicants from rural areas have lower loan approval rates than urban applicants**  
✅ **Validation**: A pie chart of **Property_Area** confirms that **rural applicants face higher rejection rates**.  

### 📍 Hypothesis 3: **Higher loan amounts lead to lower approval rates**  
✅ **Validation**: A heatmap shows a **strong correlation (~0.5) between loan amount and applicant income**, impacting approval decisions.  

---

## 📊 Key Insights from EDA  

✔ **Most Important Factor for Loan Approval**: ✅ **Credit history** significantly influences approval chances.  
✔ **Self-Employed Applicants**: ❌ Lower approval rates compared to salaried individuals.  
✔ **Impact of Loan Amount**: 💰 Higher loan amounts **decrease approval rates**.  
✔ **Property Area Influence**: 🏡 **Urban applicants** have a **higher** loan approval rate than rural applicants.  

---

## 📢 Recommendations  

📌 **Encourage Strong Credit History**  
✔ Banks should emphasize **timely repayments** to improve approval chances.  

📌 **Flexible Loan Schemes for Self-Employed Individuals**  
✔ Introduce **alternative credit scoring methods** (e.g., transaction history, business performance metrics).  

📌 **Income-Based Loan Eligibility Limits**  
✔ Adjust loan approval policies based on applicant **income levels and risk assessment**.  

📌 **Improve Processing for High-Value Loans**  
✔ Introduce **additional verification steps or flexible payment plans** for high-loan applicants.  

---

## 📌 Conclusion  
🔹 **Credit history** is the most crucial factor in loan approval decisions.  
🔹 **Self-employed individuals** face **higher rejection rates** compared to salaried applicants.  
🔹 **Higher loan amounts reduce approval chances**, as they indicate **higher financial risk**.  
🔹 **Better financial awareness and alternative scoring mechanisms** can enhance approval rates and financial inclusion.  

---

## 📁 Repository Structure  

📂 Loan-Approval-Analysis
* │── 📜 Loan sanction analysis.ipynb # Jupyter Notebook with data analysis
* │── 📄 PPT Presentation - Loan Approval.pptx # Project presentation
* │── 📄 README.md # Project documentation (this file)

---

## 🤝 Connect with Me  
💼 [LinkedIn](https://www.linkedin.com/in/shivam-gupta)  
📧 Email: your-shivamguptacpl@gmail.com  

🚀 If you found this project useful, give it a ⭐ on GitHub!  
