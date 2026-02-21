# 🐜 Ant Attraction – Three-Way ANOVA Analysis

This project was developed as part of my application for the M.Sc. Data Science program at TU Dortmund University and demonstrates applied statistical modeling, experimental design analysis, and reproducible research in Python.

This project analyzes a controlled experiment investigating how different sandwich characteristics affect ant attraction.

The goal is to determine whether:

- Bread type  
- Topping type  
- Butter (yes/no)  

significantly influence the number of ants attracted to a sandwich.

The analysis was conducted as part of my application for the M.Sc. Data Science program at TU Dortmund University.

---

## 🔬 Experimental Design

Fully crossed **4 × 3 × 2 factorial design**:

- 4 Bread types  
- 3 Toppings  
- 2 Butter conditions  
- 2 replications per condition  

Total observations: **48**

Response variable: `antCount` (number of ants)

---

## 📊 Methodology

- Three-way ANOVA (Type II sums of squares)
- Assumption checks:
  - Shapiro–Wilk test (normality)
  - Levene’s test (homogeneity of variance)
- Tukey HSD post-hoc comparisons
- Effect size (eta-squared)

Implemented in Python using:
`pandas`, `scipy`, `statsmodels`, `matplotlib`

---

## 📈 Key Results

- **Topping:** Highly significant effect (p < 0.001)  
- **Butter:** Significant effect (p < 0.001)  
- **Bread:** No significant effect  

Topping explains the largest proportion of variance (~45%).

---
