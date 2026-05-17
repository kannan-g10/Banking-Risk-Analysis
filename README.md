# 🏦 Banking Operations & Financial Performance Dashboard

## 🚀 Project Overview
This project is an advanced end-to-end Power BI business intelligence solution engineered for a banking ecosystem. The dashboard integrates core financial metrics, transactional high-value data, and operational human capital indicators to provide leadership with instant, scalable visibility into financial growth, tenure tracking, and operational efficiency.

## ❓ Problem Statement
Modern banking intelligence requires highly flexible time-series modeling and strict data normalization. Traditional reporting frameworks in this domain encounter two significant friction points:
* **🧱 DAX Bloat & Redundancy:** Developing separate, repetitive DAX measures for every financial KPI (e.g., current value, Year-over-Year change, percentage growth) creates an unmanageable data model.
* **⚠️ Initialization & Granularity Errors:** Structural misconfigurations—such as computing structural dates (e.g., `Year of Joining`) as temporary measures rather than persistent columns—cause visual initialization breaks and data rendering failures.

## 💾 Dataset Information
The underlying data model processes transactional ledger entries and internal organizational metadata:
* **📈 Financial Dimensions:** Account balances, high-value transaction indicators, loan structures, and product profitability metrics.
* **👥 Operational Metadata:** Employee profiles, officer roles, branch allocations, and historical retention indicators (such as `Year of Joining`).
* **📅 Temporal Dimensions:** A dedicated calendar dimension mapping standard dates to sequential fiscal years and quarters.

## 🛠️ Tools & Technologies Used
* **📊 BI Tool:** Power BI Desktop
* **🧮 Data Engine & Modeling:** Power BI Model View for enterprise data schema layout.
* **⚡ Advanced DAX & Design Patterns:** **Calculation Groups** for scalable, unified time-intelligence management.
* **🧹 Data Engineering:** Table View calculated columns for rigid dimensional schema mapping.

## 🖥️ Dashboard Key Implementations
* **🎛️ Advanced Calculation Groups:** Engineered calculation groups inside the Power BI Model View. This allows complex time intelligence functions (like **Year-over-Year (YoY) growth**, Month-to-Date, and Year-to-Date calculations) to be written *once* and applied globally across any selected banking metric without measure duplication.
* **📐 Structural Axis Correction:** Restructured the `Year of Joining` property as a native, optimized calculated column rather than an active measure. This resolved initialization data-load crashes and stabilized cross-filtering functionality in visual grids.
* **💼 Operational Growth View:** A high-level financial overview tracking portfolio size shifts alongside internal operational changes.

---
## 🖥️ Dashboard Preview
* **Home Page:**
<img width="2618" height="1532" alt="image" src="https://github.com/user-attachments/assets/bb5cad3d-e85e-4727-8a09-a4afe797005c" />
---

* **Loan Analysis Page:**
<img width="2592" height="1514" alt="image" src="https://github.com/user-attachments/assets/fabf2df6-a78a-4bd4-a401-c73907393425" />
---

* **Deposit Analysis Page:**
<img width="2596" height="1516" alt="image" src="https://github.com/user-attachments/assets/fb7bdabb-d792-4b95-aabb-993d0e02a5bb" />
---

* **Summary Page:**
<img width="2580" height="1530" alt="image" src="https://github.com/user-attachments/assets/76f82c41-5f0f-40e6-8836-e876825d6645" />

---

## 🔮 Future Enhancements
* **🛡️ Risk & Credit Scoring:** Integrate predictive DAX logic or Python-based predictive scripts to evaluate loan risk default probabilities directly on the visual floor.
* **🔗 Cloud Sync Integration:** Move backend CSV/Excel models into an automated Azure SQL Database environment with automated scheduled incremental refreshes.
* **🎯 Customer Churn Predictors:** Layer behavioral analytics onto account balances to flag customers exhibiting high attrition behaviors.

## 🏁 Conclusion
By modernizing the banking dashboard architecture using Calculation Groups and rigid calculated column structures, this project successfully optimizes Power BI data processing speeds and provides an interactive, enterprise-grade data tool for automated financial performance and margin analysis.
