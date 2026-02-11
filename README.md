# Food Insecurity and Mental Health Analysis

##  Project Overview
This project analyzes the relationship between **food insecurity** and **mental health outcomes** using survey data.  
It investigates how **food insecurity (FIES)**, **resilience**, and **stress mindset** are associated with **psychological distress (K10)** through data cleaning, exploratory data analysis (EDA), and non-parametric statistical testing.

---

##  Repository Contents :
- `DATA_VISUALIZATION_code.ipynb` — Main notebook (cleaning + EDA + statistics + figures)
- `cleaned_data.csv` — Cleaned dataset used in analysis
- `Data_visualization_Analytical_Report.pdf` — Analytical report (results + interpretation)
- `Data_visualization_Technical_Report.pdf` — Technical report (methods + steps)
- `Presentation.pptx` — Project presentation slides  
> ⚠️ If the original Excel file contains emails/names, avoid publishing it.

---

## Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- SciPy
- Jupyter Notebook

---

##  Data Preparation (Summary)
Main preparation steps included:
- Removing duplicates and standardizing column names
- Cleaning string values (trim/format)
- Converting survey answers into numeric scales
- Creating and categorizing scores:
  - **FIES** (Food Insecurity Experience Scale)
  - **Resilience Scale (RS)**
  - **Stress Mindset Measure (SMM)**
  - **K10** (Psychological Distress)
- Handling missing values appropriately

---

##  Research Questions

This project addresses the following questions:

1. **How is food insecurity related to psychological distress?**
2. **Does resilience act as a protective factor against psychological distress?**
3. **Is stress mindset associated with better mental health outcomes?**
4. **Are there gender-based differences in psychological distress?**
5. **Is food insecurity a region-specific issue or a nationwide concern?**

---

##  Methods Used

### Exploratory Data Analysis (EDA)
- Frequency plots for demographic variables (age, gender, region, education, work hours)
- Distribution plots for scale scores (FIES, RS, SMM, K10)
- Boxplots comparing groups
- Correlation heatmap between key scores

### Statistical Analysis
Because normality tests showed non-normal distributions, non-parametric methods were used:
- **Shapiro–Wilk** (normality testing)
- **Spearman Correlation** (associations between scores)
- **Mann–Whitney U** (gender differences in distress)
- **Kruskal–Wallis** (regional differences in food insecurity)

---

##  Key Findings 
- Food insecurity showed a **significant positive association** with psychological distress.
- Resilience showed a **significant negative association** with psychological distress (protective effect).
- Stress mindset showed a **weak but significant negative association** with distress.
- Psychological distress differed by gender (females showed higher median distress).
- Food insecurity did not significantly differ across regions.

---

## Author :

**Mohammad ali othman **

Data Science Student — Jordan University of Science and Technology


---

##  License :

This project is intended for educational and research purposes.
