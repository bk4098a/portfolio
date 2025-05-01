# 🏃 Predicting Race Performance from Bib Numbers  
### Boston Marathon 2023 – Slide Deck

This slide presentation analyzes whether bib numbers — assigned based on qualifying times — can effectively predict race outcomes in the 2023 Boston Marathon.  
It also examines demographic differences in performance, focusing on gender and age group trends.

---

## 🎯 Key Research Questions

- Does a **lower bib number** correspond to a **faster finish time**?
- Are there **statistically significant performance differences** by **gender** and **age**?
- Can bib numbers serve as a **valid performance proxy**?

---

## 📊 Analysis Summary

- **Bib Number vs Finish Time**:  
  Strong positive relationship (Adjusted R² = 0.6116)

- **Gender Differences**:  
  Female runners finish ~23.5 minutes slower on average (p < 0.001)

- **Age Effects**:  
  Average finish time rises with age, especially after 60

---

## 📁 Dataset

- **Source**: [Score Network – Boston Marathon 2023](https://data.scorenetwork.org/running/boston_marathon_2023.html)
- **N** ≈ 26,000 runners
- **Variables**: `bib_number`, `finish_net_minutes`, `gender`, `age_group`

---

## 📈 Visualizations

- Scatter plots with regression line  
- Violin plots (by gender)  
- Bar charts (by age group)  
- Density plots (distribution comparison)  
- Gender × Age overlays  

---

## 🧰 Tools Used

- **Language**: R (RMarkdown, xaringan)
- **Packages**: `ggplot2`, `dplyr`, `readr`, `xaringan`, `stats`
- **Slide Format**: HTML (`xaringan::moon_reader`)

---

## 🌐 View the Slides

🔗 [View Hosted Slide Deck](https://bk4098a.github.io/portfolio/)

---

## 📂 Folder Contents

| File                            | Description                  |
|---------------------------------|------------------------------|
| `index.html`                    | Final slide deck             |
| `Boston_Marathon_Final_Slides.Rmd` | Source presentation file     |
| `boston_marathon_2023_cleaned.csv` | Cleaned marathon data        |
| `fonts.html`, `*.css`           | Custom theme assets          |

---

## 👤 Author

**Byeolha Kim**  
M.A. Candidate, International Economics  
American University  
📧 bk4098a@american.edu  
🔗 [GitHub Profile](https://github.com/bk4098a)
