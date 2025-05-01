# 📌 Race and Economic Opportunity – Research Poster

This project explores how socio-economic and racial variables predict economic mobility using U.S. Census data from the Opportunity Insights dataset.  
It was developed as part of a course on statistical data analysis and visualization, and presented in an academic research poster format.

---

## 🎯 Research Question

How do race and parent income percentile influence future income rank among different demographic groups?

---

## 📁 Data

- **Source**: [Opportunity Insights – Public Use Census Data](https://opportunityinsights.org/data/)
- **Sample**: 64 U.S. aggregated demographic regions
- **Variables Used**:  
  - `par_pctile` (parent income percentile)  
  - `count_black_pooled` (Black population count)  
  - `kir_1par_black_male` (income rank for Black males from single-parent households)  
  - `kir_1par_white_male` (same for white males)

---

## 🔍 Methods

- Correlation analysis among key variables
- Linear regression between Black population and income rank
- Predictive modeling using K-Nearest Neighbors (KNN)
- Visualizations include ECDFs, histograms, scatter plots, and tables

---

## 📊 Key Findings

- Higher Black population count is negatively associated with mobility outcomes.
- Parent income percentile has a strong positive correlation with future income rank.
- KNN model performed well (R² = 0.962, RMSE = 1.078), demonstrating prediction capability.

---

## 📂 Folder Contents

| File                     | Description                                |
|--------------------------|--------------------------------------------|
| `Research_Poster.Rmd`    | RMarkdown file used to generate the poster |
| `Research_Poster.html`   | Final HTML poster using `posterdown`       |
| `table_1.csv`            | Cleaned dataset used in the analysis       |

---

## 👤 Author

**Byeolha Kim**  
M.A. Candidate in International Economics  
American University  
📧 bk4098a@american.edu  
🔗 [GitHub Profile](https://github.com/bk4098a)
