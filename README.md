# Maximizing Revenue for Drivers Through Payment Type

<div align="center">
  <br />
      <img src="https://github.com/user-attachments/assets/d1ab8588-4c79-4120-b760-c6baaa513b22" alt="Project Banner">
  <br />

  <div>
    <img src="https://img.shields.io/badge/-Python-black?style=for-the-badge&logoColor=white&logo=python&color=3776AB" alt="Python" />
    <img src="https://img.shields.io/badge/-Pandas-black?style=for-the-badge&logoColor=white&logo=pandas&color=150458" alt="Pandas" />
    <img src="https://img.shields.io/badge/-NumPy-black?style=for-the-badge&logoColor=white&logo=numpy&color=013243" alt="NumPy" />
    <img src="https://img.shields.io/badge/-Jupyter-black?style=for-the-badge&logoColor=white&logo=jupyter&color=F37626" alt="Jupyter" />
  </div>
</div>

## 📋 Table of Contents
1. ⚙️ [Overview](#overview)
2. 📊 [Data Overview](#data-overview)
3. 🛠 [Methodology](#methodology)
4. 🔍 [Key Findings & Insights](#key-findings--insights)
5. 🧪 [Hypothesis Testing](#hypothesis-testing)
6. 💡 [Recommendations](#recommendations)
7. 💻 [GitHub Implementation](#github-implementation)
8. 📎 [Conclusion](#conclusion)

## ⚙️ Overview
This project investigates how payment type affects fare amounts in taxi services. The objective is to determine if nudging customers towards specific payment methods can maximize revenue for drivers without negatively impacting customer experience.

## 📊 Data Overview
- **Dataset:** NYC Taxi Trip Records
- **Data Cleaning:** Focused on relevant columns, removing inconsistencies
- **Key Columns Used:**
  - Passenger count
  - Payment type (Card or Cash)
  - Fare amount
  - Trip distance
  - Duration (minutes)

## 🛠 Methodology
1. **Descriptive Analysis** - Summary statistics to understand fare distribution.
2. **Hypothesis Testing** - Conducted a T-Test to analyze differences in fare amounts based on payment method.
3. **Regression Analysis** - Examined relationships between trip distance, payment method, and fare amount.

## 🔍 Key Findings & Insights
- **Journey Insights:**
  - Customers paying with cards tend to have higher average trip distances and fares compared to those paying with cash.
  - Customers prefer using credit cards for longer trips and higher fares.
- **Payment Preference Analysis:**
  - Card payments account for **74.7%** of transactions, while cash accounts for **25.3%**.
  - The data suggests a revenue optimization opportunity by encouraging card transactions.
- **Passenger Count Analysis:**
  - Single-passenger rides dominate and are more frequently associated with card payments.

## 🧪 Hypothesis Testing
- **Null Hypothesis:** No difference in average fare between card and cash payments.
- **Alternative Hypothesis:** There is a significant difference in fare amounts based on payment method.
- **Results:**
  - T-statistic = **9.8**, P-value < **0.05**
  - Null hypothesis rejected → Significant difference in fare amounts between payment types.

## 💡 Recommendations
1. **Encourage Card Payments** - Promote card usage to capitalize on higher fare amounts.
2. **Incentivize Digital Transactions** - Offer discounts and rewards for credit card payments to increase adoption.
3. **Improve Payment Experience** - Ensure secure and seamless digital payment options for better customer convenience.

## 💻 GitHub Implementation
To implement and share this analysis on GitHub, follow these steps:

### 🏗 Repository Setup
```bash
# Initialize a new GitHub repository
git init

git add .
git commit -m "Initial commit - Maximizing Revenue Analysis"
git branch -M main
git remote add origin <your-github-repo-url>
git push -u origin main
```

### 📂 Folder Structure
```plaintext
📂 maximizing-revenue-analysis
│── 📂 data             # Contains dataset files
│── 📂 notebooks        # Jupyter Notebooks for analysis
│── 📜 README.md        # Project documentation
│── 📜 requirements.txt # Dependencies
```

### 📦 Dependencies
Create a `requirements.txt` file and include necessary Python packages:
```plaintext
pandas
numpy
matplotlib
seaborn
scipy
statsmodels
jupyter
```
Install dependencies using:
```bash
pip install -r requirements.txt
```

### 🚀 Running the Analysis
Run the Jupyter Notebook to explore the data and generate insights:
```bash
jupyter notebook analysis.ipynb
```

## 📎 Conclusion
The study demonstrates that card transactions tend to yield higher fare amounts compared to cash. By implementing targeted incentives and optimizing payment processes, taxi drivers and companies can potentially increase revenue effectively.

