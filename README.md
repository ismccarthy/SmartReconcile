**SmartReconcile** is a Python-based tool designed to streamline and automate financial reconciliation tasks typically performed in SAP environments. It loads GL, AP, or AR line item data (exported from SAP), performs reconciliation checks, identifies discrepancies, and optionally forecasts future values.

> ⚡ Built by Ian McCarthy – SAP Finance Consultant & Python Programmer

---

## 🔍 Features

- 🔗 **Data ingestion** from Excel or CSV (SAP GL, AR/AP exports)
- 📊 **Reconciliation engine** – matches debits/credits, flags exceptions
- 📈 **Forecasting module** – basic cost/cash predictions using time series
- 📥 **Clean report export** – Excel or PDF with summary visuals

---

## 📁 Sample Workflow

1. Export SAP GL/AP/AR data to Excel
2. Load into SmartReconcile (`data/` folder)
3. Script runs reconciliation logic and highlights issues
4. Forecasting (optional): predict costs, detect anomalies
5. Output exception report and visual summary

---

## 🛠️ Tech Stack

- `pandas`, `openpyxl` – data loading & wrangling
- `matplotlib`, `plotly` – charts & reporting
- `statsmodels`, `scikit-learn` – optional forecasting
- `xlsxwriter` – formatted Excel exports

---

## 🔮 Future Plans

- Simulated SAP API integration via mock OData
- UI (Streamlit) for non-technical users
- Deployment to SAP Business Technology Platform (BTP)

---

## 📌 Author

**Ian McCarthy**  
SAP Finance + BI Consultant | Python & R Programmer  
📧 ianmccarthyonline@gmail.com  
🧠 Exploring finance, analytics, and automation  
