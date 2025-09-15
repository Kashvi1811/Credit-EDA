Credit Risk EDA 📊

Exploratory Data Analysis of credit applications to uncover patterns in loan defaults and repayment behavior.

📑 Table of Contents

Overview

Features

Project Structure

Getting Started

Usage

Tech Stack

Future Improvements

License

Contact

🔎 Overview

This project analyzes loan application data to understand factors influencing repayment difficulties. Using Exploratory Data Analysis (EDA), the study identifies risk drivers in consumer lending and provides insights into creditworthiness.

The repository provides:

A structured EDA workflow (data cleaning, outlier detection, univariate & bivariate analysis).

Identification of default risk patterns in applicant profiles.

Visualizations of correlations and trends across socio-economic & loan-related variables.

✨ Features

Outlier Analysis: Detect anomalies in income, loan amounts, and demographic data.

Target Variable Imbalance Check: Assess distribution of repayment vs. default cases.

Univariate & Bivariate Analysis: Examine categorical and numerical drivers of default.

Correlation Analysis: Identify strong predictor variables.

Risk Profiling: Highlight applicant categories more likely to repay or default.

📂 Project Structure
credit-risk-eda/
├── data/
│   ├── application_data.csv        # Client details at loan application
│   ├── previous_application.csv    # Records of previous loans
│   ├── columns_description.csv     # Data dictionary
├── notebooks/
│   └── credit_eda.ipynb            # Full EDA notebook
├── reports/
│   └── Credit EDA Case Study.pdf   # Detailed case study & results
├── requirements.txt                # Dependencies
└── README.md                       # Project documentation

⚡ Getting Started

Clone the repository:

git clone https://github.com/<your-username>/credit-risk-eda.git
cd credit-risk-eda


(Optional) Create a virtual environment:

python -m venv env
source env/bin/activate       # macOS / Linux
env\Scripts\activate          # Windows PowerShell


Install dependencies:

pip install -r requirements.txt

🖥️ Usage

Open the Jupyter Notebook:

jupyter notebook notebooks/credit_eda.ipynb


Run the notebook step by step to explore:

Data cleaning & preprocessing.

Outlier detection & imbalance analysis.

Univariate, bivariate, and correlation analyses.

Risk segmentation of applicants.

🛠 Tech Stack

Python, Jupyter

pandas, NumPy

Matplotlib, Seaborn

scikit-learn (for preprocessing support)

🚀 Future Improvements

Extend analysis with predictive modeling (Logistic Regression, XGBoost, etc.).

Address class imbalance using SMOTE or weighted models.

Build a credit risk scoring model for new applicants.

Deploy findings in an interactive Streamlit dashboard.

📜 License

This project is intended for educational and personal use. All rights reserved by Kashvi1811.
For any usage beyond personal or educational purposes, please contact me in advance.

🤝 Contact & Collaboration

I’m always open to feedback, ideas, and collaboration opportunities!

GitHub: @Kashvi1811

LinkedIn: Kashvi on LinkedIn

Email: kashvisoni2005@gmail.com
