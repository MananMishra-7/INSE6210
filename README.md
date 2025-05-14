# Supply Chain Optimization of Beauty Company using Six Sigma DMAIC

![Six Sigma DMAIC](https://img.shields.io/badge/Methodology-DMAIC-brightgreen)
![Python](https://img.shields.io/badge/Language-Python-blue)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## 📌 Overview

This project applies the **Six Sigma DMAIC (Define, Measure, Analyze, Improve, Control)** methodology to optimize the supply chain of a fictional beauty company. The primary focus is on **reducing defect rates** by at least 10% using statistical analysis, machine learning models (Random Forest), and root cause analysis.

## 🎯 Objectives

- Reduce defect rate from 2.27% by at least 10%
- Identify and analyze key contributors to high defect rates
- Propose actionable improvements for operational efficiency
- Implement a control plan for sustaining improvements

## 🧠 Methodology

The project follows the **DMAIC** approach:

1. **Define** – Problem definition, stakeholder mapping, CTQ identification, SIPOC diagram  
2. **Measure** – Data exploration, descriptive stats, correlation analysis  
3. **Analyze** – Root cause analysis using Pareto charts, Fishbone diagram, and Random Forest Regressor  
4. **Improve** – Feature engineering and impact testing to improve target metric  
5. **Control** – Proposed long-term control mechanisms and process monitoring techniques  

## 🧰 Tools & Technologies

- Python (Jupyter Notebooks)
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
- Excel (for initial data formatting and overview)

## 📊 Data Description

Dataset sourced from Kaggle ([Link](https://www.kaggle.com/datasets/amirmotefaker/supply-chain-dataset)) with 24 features and 100 entries, covering:

- Product Details (Type, SKU, Price, Availability, etc.)
- Supply Chain Metrics (Lead Times, Shipping, Manufacturing, etc.)
- Customer Demographics
- Defect Rate (Target Variable)

## 🔍 Key Insights

- **Inspection results** and **transportation route** (Rail, Route C) are highly associated with higher defect rates.
- **Supplier lead time**, **Manufacturing lead time**, and **Number of products sold** are the most critical numerical features influencing defects.
- Improved defect rate predicted to drop from **2.04% to 1.77%**, a **13.24% reduction** using strategic feature modifications.

## ✅ Proposed Improvements

- Reduce lead times via multisourcing and near-shoring strategies
- Implement preventive maintenance and real-time scheduling for production
- Enhance demand forecasting and regional sales strategies

## 📈 Control Measures

- Real-time process monitoring (ERP, SCADA)
- SOPs for order fulfillment and supplier interactions
- Forecast validation via MAPE and bias metrics
- PDCA & Kaizen for continuous improvement

## 📌 Future Work

- Include categorical features using encoding techniques:
  - One-Hot Encoding
  - Frequency Encoding
- Use advanced ML pipelines for full-feature modeling

## 👨‍💻 Contributors

- **Manan Mishra** – [GitHub](https://github.com/MananMishra-7)  
- **Sandip Devrao Misal**  
- **Vatsal Raviya**

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 📁 Folder Structure

