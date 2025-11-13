# 🧠 Complaint Data Tagging, Root Cause Identification & Exploratory Data Analysis

## 📘 Summary
This project demonstrates how unstructured complaint and maintenance data can be transformed into actionable insights. Using Python and Excel concepts, complaint, cause, and correction data were systematically tagged, cleaned, and analyzed. The resulting report highlights recurring issues, root causes, and opportunities for process improvement.

---

## 🔍 Project Overview

### 🎯 Objective
- Categorize complaint, cause, and correction data into:
  - **Root Cause**
  - **Symptom Condition**
  - **Symptom Component**
  - **Fix Condition**
  - **Fix Component**
- Perform **Exploratory Data Analysis (EDA)** to uncover trends, recurring issues, and actionable insights.

### ⚙️ Tools & Technologies
- **Python:** pandas, numpy, re, matplotlib, seaborn  
- **Excel:** Data validation, pivot tables  
- **Dashboard Tools (optional):** Tableau / Power BI  
- **Environment:** Jupyter Notebook / Google Colab  

---

## 🧩 Task 1 — Data Tagging (Rule-Based NLP)

### 🧰 Approach
1. Normalized text (lowercase, remove punctuation, trim spaces)  
2. Mapped keywords to predefined taxonomy categories  
3. Applied rule-based tagging using conditional logic  
4. Added confidence scoring: High / Medium / Low  
5. Tagged unmapped entries as **Unmapped** for manual review  

### 📊 Results & Insights
- Most frequent issues: **loose wire connectors**, **corrosion**, **improper crimping**  
- Indicates gaps in assembly quality and component design  
- Tagged data enables trend analysis and predictive maintenance

---

## 🧹 Task 2 — Data Cleaning & Exploratory Data Analysis (EDA)

### 🧰 Data Cleaning Steps
1. Column profiling for types, uniqueness, and value distributions  
2. Handling missing values (imputation/removal)  
3. Standardized categorical values (typos, capitalization)  
4. Checked numerical outliers using IQR  
5. Verified referential integrity and consistent units  

### 📈 Exploratory Data Analysis
- **Correlation analysis:** Relationships between causes, conditions, fixes  
- **Frequency analysis:** Top recurring failures and affected components  

**Visualizations (placeholders):**  
- Bar chart: Top 5 Root Causes  
- Pie chart: Fix Component distribution  
- Trend plot: Issue frequency over time  

### 💡 Key Findings
- Electrical issues (loose connectors, corrosion) = **60% of failures**  
- Repeated fixes indicate weak supplier quality/design tolerance  
- Recommendations: standardize torque, add connector insulation

---

## 📊 Insights & Recommendations
- **Root Causes:** Address loose connections and corrosion via materials and inspections  
- **Operational Improvement:** Automate tagging dashboards for real-time monitoring  
- **Predictive Opportunity:** Structured data enables predictive failure modeling  
- **Quality Control:** Implement feedback loop linking complaints to production/design  

---

## 🚀 Results & Learnings
- Automated tagging successfully structured unstructured text  
- Identified high-frequency failure modes for actionable improvements  
- Enhanced Python, Excel, and visualization skills  

---

## 🧾 Future Enhancements
- Use **NLP models** (spaCy, BERT) for smarter tagging and sentiment detection  
- Automate **EDA report generation** with Python templates  
- Build **interactive dashboards** in Tableau / Power BI for stakeholders  

---

## 📷 Dashboard / Visuals

[!(https://via.placeholder.com/600x300?text=Dashboard)](https://public.tableau.com/views/ComplaintDataTaggingRootCauseIdentificationExploratoryDataAnalysis/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)  


---

*This README serves as a professional standalone project report for the portfolio project: “Complaint Data Tagging, Root Cause Identification & Exploratory Data Analysis.”*

