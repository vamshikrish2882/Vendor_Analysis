# 🧠 Vendor Analysis & Performance Intelligence System  

## Overview
The **Vendor Analysis & Performance Intelligence System** is a complete end-to-end data analytics project that transforms raw procurement and sales data into meaningful insights.  
It demonstrates advanced data analysis, automation, and reporting skills using Python, SQL, and Power BI.  

---

## 🔍 Project Objectives
- Automate the extraction, transformation, and loading (ETL) of vendor data.  
- Compute critical performance KPIs such as Gross Margin %, Gross Profit, Freight %, and Turnover.  
- Identify top-performing vendors and areas for improvement through data-driven insights.  
- Present findings through interactive dashboards and professional reports.  

---

## 🧰 Tech Stack
| Category | Tools & Technologies |
|-----------|----------------------|
| Programming | Python (Pandas, NumPy, Matplotlib, Seaborn, SQLite3) |
| Data Visualization | Power BI, Excel |
| Automation | ETL Scripts (ingestion_db.py, get_vendor_summary.py) |
| Environment | Jupyter Notebook, VS Code |
| Reporting | Power BI Dashboard, PDF Summary |

---

## 📊 Key Features
- **Exploratory Data Analysis (EDA):** Uncovers patterns and trends in purchase and sales data.  
- **Vendor Performance Scoring:** Calculates KPIs and ranks vendors based on efficiency and profitability.  
- **Data Integration:** Merges multiple datasets into a unified analytical database.  
- **Visual Insights:** Power BI dashboards and heatmaps for executive-level reporting.  
- **Automated Workflow:** Streamlined ETL process for consistent and repeatable analytics.  

---

## 🏗️ Project Structure
```
Vendor_analysis_new/
│
├── ingestion_db.py                  # Loads and merges source datasets
├── get_vendor_summary.py            # Builds vendor KPI summary table
├── Exploratory_Data_Analysis_code.ipynb
├── Vendor_Performance_Analysis_code.ipynb
├── vendor_sales_summary.xlsx        # Processed summary data
├── Vendor Performance Report.pdf    # Final analytical report
├── vendor_performance.pptx          # Power BI dashboard slides
└── inventory/                       # Raw data files
```

---

## ⚙️ How to Run
```bash
# Clone repository
git clone https://github.com/<your-username>/Vendor_Analysis.git
cd Vendor_Analysis

# Install dependencies
pip install pandas numpy matplotlib seaborn sqlite3

# Execute ETL and summary scripts
python ingestion_db.py
python get_vendor_summary.py
```

---

## 📈 Results & Impact
- Reduced vendor evaluation time by **60%** through automation.  
- Identified **top 20% vendors** contributing to **80% of total sales value**.  
- Enhanced procurement decision-making with visual dashboards.  
- Improved transparency, consistency, and reporting accuracy.  

---

## 🚀 Future Enhancements
- Integration with **cloud-based databases (AWS, Azure)**.  
- Predictive analytics for **vendor risk assessment**.  
- Automated report generation and **Power BI API refresh**.  

---

## 👤 Author
**Vamshikrishna Pandilla**  
*M.S. Data Science, University of Maryland, Baltimore County*  
📧 Email: pandirlavamshikrishna602@gmail.com 
🔗 [LinkedIn](https://linkedin.com/in/vamshikrishna-pandilla)

---

**“Turning raw data into business intelligence for smarter procurement decisions.”**
