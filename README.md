# 📊 Bank Loan Data Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Library-Pandas-orange)
![NumPy](https://img.shields.io/badge/Library-NumPy-lightgrey)
![Matplotlib](https://img.shields.io/badge/Library-Matplotlib-green)
![Seaborn](https://img.shields.io/badge/Library-Seaborn-yellow)
![Jupyter](https://img.shields.io/badge/Tool-Jupyter_Notebook-red)

A complete, notebook-driven **Exploratory Data Analysis (EDA)** of bank loan applications. The project reveals trends in funded amounts, repayments, interest rates, DTI (Debt-to-Income), and borrower risk. It also summarizes **Good vs. Bad loan metrics**, **MTD snapshots**, and **regional (state-wise) patterns** with clean visualizations.

> **Who is this for?** Banks/FinTechs, credit analysts, and learners who want a real-world finance EDA project to showcase on a resume or portfolio.

---

## 🧭 Table of Contents
- Overview
- Key Features
- Tech Stack
- Project Structure
- Setup
- How to Run
- Key Insights
- Future Enhancements
- Author
  
---

## 🔎 Overview
This project analyzes bank loan application data to:
- Track monthly & yearly application trends
- Measure total funded amounts and total amount received
- Compute average interest rate and average DTI
- Compare Good vs. Bad loans using business-friendly metrics
- Provide MTD (Month-to-Date) snapshots of key KPIs
- Explore regional variations (by State)

All analysis is implemented in a single Jupyter Notebook: `Bank_Loan_Analysis.ipynb`.

---

## 🧩 Key Features
- Time-series trends for applications, funding, and repayments
- Good vs. Bad loan metrics summarized at-a-glance
- Borrower risk indicators: Interest Rate & DTI distributions
- State-wise maps/plots to compare regional performance
- Clean Pandas pipelines for reproducible analysis
- Matplotlib/Seaborn visualizations for presentation-ready charts

---

## 🛠 Tech Stack
- Language: Python 3.x
- Libraries: Pandas, NumPy, Matplotlib, Seaborn
- Environment: Jupyter Notebook

Optional: Add `requirements.txt` and a virtual environment for easy setup.

---

## 📂 Project Structure
```
Bank_Loan_Analysis/
├── Bank_Loan_Analysis.ipynb    # Main analysis notebook
├── data/                       # Place raw/clean datasets here (not committed)
├── README.md                   # This file
└── requirements.txt            # (Optional) dependencies
```

**Suggested `requirements.txt`:**
```
pandas
numpy
matplotlib
seaborn
jupyter
```

---

## ⚙️ Setup
1. Clone the repository
   ```
   git clone https://github.com/<your-username>/bank-loan-analysis.git
   cd bank-loan-analysis
   ```
2. (Optional) Create a virtual environment
   ```
   python -m venv .venv
   # Windows
   .venv\Scripts\activate
   # macOS/Linux
   source .venv/bin/activate
   ```
3. Install dependencies
   ```
   pip install -r requirements.txt
   # or
   pip install pandas numpy matplotlib seaborn jupyter
   ```

---

## ▶️ How to Run
1. Put your dataset(s) inside the `data/` folder.
2. Launch Jupyter and open the notebook:
   ```
   jupyter notebook Bank_Loan_Analysis.ipynb
   ```
3. Run all cells (top → bottom). Update file paths as needed.

Tip: Export plots to the `images/` folder so they can be shown in the README.

---

## 🔑 Key Insights
- Identified repayment patterns across borrower segments
- Clear comparison of Good vs. Bad loans for portfolio health
- Visualized monthly trends in applications and funded amounts
- Highlighted regional differences in demand and repayments
- Computed interest rate and DTI aggregates for risk assessment

---

## 🧭 Future Enhancements
- Build a Streamlit/Power BI dashboard for interactive exploration
- Add predictive modeling for default/charge-off risk
- Schedule automated reporting (daily/weekly MTD snapshots)
- Enrich with demographics/employment features for deeper insights

---

## 👤 Author
**Ajay Singh**  
📧 <ajaysingh60970@gmail.com> • 🌐 [LinkedIn](https://www.linkedin.com/in/ajay-singh-28957035b/) • 💻 [GitHub](https://github.com/ajaysingh6097)

If you found this helpful, please ⭐ star the repo!

---


