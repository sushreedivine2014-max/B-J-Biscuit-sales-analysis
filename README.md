# Retail Revenue Analysis 📊

## 📌 Project Overview
The **B&J Biscuit Company** was facing challenges in evaluating sales performance due to highly unstructured, inconsistent, and disconnected data. This project involved cleaning, processing, and analyzing **12,000+ rows of sales records** to create a structured dataset and an interactive dashboard for strategic decision-making.

## 📁 Project Deliverables
- **Cleaned & Structured Excel Dataset:** Multi-step data processing using advanced formulas.
- **Interactive Sales Dashboard:** Dynamic charts, pivot tables, and KPI cards.
- **Project Presentation (PPT):** Comprehensive summary of methodology and business insights.

---

## 🛠️ Project Workflow & Technical Tasks

### Phase 1: Data Cleaning & Formatting (Task 1 & 2)
- **Special Character Removal:** Replaced corrupted and erratic symbols across text entries.
- **Whitespace Trimming:** Applied `TRIM` and `CLEAN` functions to eliminate trailing and unwanted spaces.
- **Text Standardisation:** Used `PROPER`, `UPPER`, and `LOWER` functions for naming consistency.
- **Data Splitting:** Divided composite strings into distinct columns (`Buyer Name` and `Location`).

### Phase 2: Lookup Mapping & Data Integration (Task 3)
- Utilized **`XLOOKUP`** (and `VLOOKUP` fallbacks) to connect transaction records with the master Products sheet, accurately fetching:
  - Unit Price
  - Product Cost
  - Product Category
  - Product Name

### Phase 3: Feature Engineering & Metrics Calculation (Task 4 & 5)
Calculated core financial KPIs using explicit formulas:
- **Total Revenue:** `Quantity Purchased × Unit Price`
- **Total Cost:** `Quantity Purchased × Cost`
- **Total Profit:** `Revenue - Cost Amount`
- **Profit Margin %:** `(Profit / Revenue) × 100`
- **Demographic Derivation:** Calculated customer ages using `Current Year - Buyer DOB Year`.

### Phase 4: Segmented Data Analysis (Task 6, 7 & 8)
- **Customer & Demographics:** Grouped customers by age brackets (18-25, 26-35, 36-45, 46-55, 55+) and evaluated revenue split by **Gender**.
- **Location Analytics:** Ranked regions by top-performing revenue and profit margins.
- **Payment Method Analysis:** Identified payment choice trends (**UPI vs. Card**) broken down by age groups and count of orders.

### Phase 5: Dashboard Visualization (Task 9 & 10)
Created an executive-facing interactive dashboard utilizing:
- **Charts:** Donut charts for gender distributions, Histograms for age group spreads, Scatter plots for price-vs-profit correlations, and Line/Combo charts for sales trends.
- **Interactive Controls:** **Slicers** mapped to *Region, Age Group, Gender, and Sales Representative* for seamless, dynamic data filtering.

## 📊 Key Deliverables in this Repository
1. **`[B&J_Biscuit_Co_Sales_Analysis].xlsx`**: The complete production file containing the raw data, cleaned dataset sheets, calculations, and the interactive dashboard.
2. **`[P2_Retail_Revenue_Analysis].pptx`**: The final summary presentation designed for stakeholder review, outlining key data insights and strategic recommendations.

## 🎯 Evaluation Metrics Met
* **Accuracy:** 100% complete data preprocessing with zero broken formulas.
* **Clarity:** Professional chart design with clean, readable data visualizations.
* **Structure:** Organized documentation mapping directly to the project objectives.
