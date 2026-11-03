\# Home Loan Default – Risk Management (PRCP-1006)



Predicts which home loan applicants are likely to default and ranks them into 10 risk bands.



\## Highlights

\- Data: Home Credit Default Risk (7 tables, 307,511 applicants, 8.07% defaulters)

\- 405 engineered features from bureau, previous applications, instalments and credit card history

\- Best model: LightGBM (validation ROC-AUC 0.7892); compared with XGBoost, Random Forest and Logistic Regression

\- Threshold tuned to 0.172 (recall 0.42, precision 0.29, F1 0.34)

\- Risk bands: default rate rises from 0.94% (D1) to 30.74% (D10); the riskiest 20% hold about 57% of defaulters

\- SHAP explanation: external credit scores are the strongest drivers



\## Files

\- `HomeLoan\_Default.ipynb`: full notebook (analysis, models, comparison, challenges report)



\## Data

Dataset not included because of size. Download it from the Home Credit Default Risk competition on Kaggle and place the CSV files next to the notebook.



\## Tools

Python, pandas, NumPy, scikit-learn, LightGBM, XGBoost, SHAP, Matplotlib, Seaborn

