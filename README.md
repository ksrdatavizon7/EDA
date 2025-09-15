# EDA

# Loan Defaulters - Exploratory Data Analysis  

## 📌 Project Overview  
This project performs **Exploratory Data Analysis (EDA)** on a loan dataset to identify key factors influencing loan defaults. The goal is to uncover trends, patterns, and insights that help financial institutions minimize risk and improve loan approval strategies.  

## 🎯 Objectives  
- Understand the dataset and its structure  
- Clean and preprocess missing/inconsistent values  
- Explore borrower demographics, loan types, and repayment behaviors  
- Identify variables correlated with loan defaults  
- Generate actionable insights for decision-making  

## 🛠️ Tools & Technologies  
- **Python**: Pandas, NumPy, Matplotlib, Seaborn  
- **Jupyter Notebook**  
- **EDA techniques**: univariate, bivariate, and multivariate analysis  

## 📊 Key Insights  
- High loan defaults are linked to specific borrower profiles (e.g., low income, high loan amount).  
- Employment stability and credit history play a significant role in repayment.  
- Certain loan purposes show a higher default probability.  
- Missing or inconsistent values in financial history strongly impact loan outcomes.  

## 📂 Repository Structure  
```bash
├── data/              # Dataset files (if included)
├── notebooks/         # Jupyter notebooks with EDA
├── reports/           # PDF report and visualizations
├── src/               # Python scripts for analysis
└── README.md          # Project summary
```

## 📥 Dataset  
You can download the dataset from the following link:  
🔗 [Loan Defaulters Dataset](https://drive.google.com/drive/folders/1x7Jbn9VoLeTS0rSZmkMgS_IOPG5_QUND?usp=sharing)  

## 🚀 How to Run  
1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/loan-defaulters-eda.git
   cd loan-defaulters-eda
   ```
2. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the Jupyter Notebook  
   ```bash
   jupyter notebook notebooks/EDA_Loan_Defaulters.ipynb
   ```

## 📦 Requirements  
Add the following to a `requirements.txt` file:  
```txt
pandas
numpy
matplotlib
seaborn
jupyter
```

## 📌 Results & Applications  
- Helps banks/financial institutions refine **credit risk models**  
- Guides better loan approval decisions  
- Supports building predictive models for **loan default classification**  
