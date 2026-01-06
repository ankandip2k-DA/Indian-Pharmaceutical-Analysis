# 💊 Indian Pharmaceutical Market Analysis  
### *Data-Driven Insights using Excel*

## 📌 Project Overview
The Indian pharmaceutical industry includes thousands of products across diverse therapeutic classes and pricing segments.  
This project analyzes a **large-scale pharmaceutical dataset** to uncover:

- Medicine pricing trends  
- Manufacturer dominance  
- Product discontinuation patterns  
- Therapeutic class insights  

The objective is to support **competitive analysis and pricing strategy decisions** using data-driven insights.

---

## 🎯 Project Objectives
- Understand medicine pricing patterns across segments  
- Identify top manufacturers and market leaders  
- Analyze product discontinuation trends  
- Deliver actionable business recommendations  

---

## 📂 Dataset Overview
- **Source:** Kaggle – Indian Pharmaceutical Products Dataset  
- **Total Records:** 153,972  

### Key Fields
| Column Name | Description |
|------------|-------------|
| brand_name | Medicine name |
| manufacturer | Producing company |
| price_inr | Price in INR |
| dosage_form | Tablet, syrup, etc. |
| primary_ingredient | Key component |
| therapeutic_class | Drug category |
| is_discontinued | Product availability |

---

## 🧹 Data Cleaning & Preparation
Performed using **Excel – Power Query Editor**:

- Removed unnecessary index columns  
- Handled missing values (pack size, unit, strength)  
- Removed duplicate records and null brand names  
- Standardized text using **TRIM & Proper Case**  
- Filtered invalid prices (`price_inr ≤ 0`)  
- Split packaging details into `pack_size` and `pack_unit`  
- Ensured correct data types for all columns  

---

## 💰 Price Categorization
Created a `Price_Group` column for affordability analysis:

| Price Group | Range (INR) |
|------------|-------------|
| Very Low | < ₹50 |
| Low | ₹50 – ₹100 |
| Medium | ₹101 – ₹200 |
| High | ₹201 – ₹500 |
| Very High | > ₹500 |

✔ Used as a **slicer** in the Power BI dashboard for interactive analysis.

---

## 📊 Data Analysis & Dashboard Design
### 🛠 Tools Used
- Microsoft Excel  
- Power BI  

### 📈 Key Visuals
- **KPI Cards:** Total Products, Average Price, % Discontinued  
- **Bar Chart:** Top 10 Manufacturers  
- **Pie Chart:** Distribution by Dosage Form  
- **Column Chart:** Average Price by Therapeutic Class  
- **Scatter Plot:** Price vs Pack Size  
- **Slicers:** Price Group, Therapeutic Class  

---

## 🔍 Key Insights
- **Top Manufacturers:** Sun Pharma, Cipla, and GSK dominate product variety  
- **Price Distribution:** ~60% of medicines priced below ₹200  
- **Dosage Form:** Tablets account for over 70% of products  
- **Therapeutic Class:** Antibiotics hold the largest market share  
- **Premium Segment:** High-value drugs (>₹500) mainly belong to specialized therapies  
- **Discontinuation Rate:** Only ~3% of products are discontinued  

---

## 💡 Business Recommendations
- 🎯 Focus on **mass-market pricing (₹50–₹200)**  
- 🧪 Increase R&D investment in **antibiotics and antihistamines**  
- 📦 Standardize packaging and branding to improve cost efficiency  
- 💸 Monitor pricing closely in **price-sensitive therapeutic classes**  
- 📈 Use Power BI dashboards for **real-time market tracking**  

---

## 🚀 Conclusion & Next Steps
This project demonstrates how **Excel and Power BI** can transform raw pharmaceutical data into actionable insights for **pricing strategy and competitive analysis**.

### Future Enhancements
- Integrate **sales and regional data**  
- Connect with **Azure SQL** for automation  
- Apply **AI-based forecasting** for price trend prediction  

---

## 🙌 Acknowledgements
- **Dataset:** Kaggle – Indian Pharmaceutical Products Dataset  
- **Tools:** Microsoft Excel & Power BI  
