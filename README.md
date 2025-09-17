# World Happiness Report 2024 — Exploratory Data Analysis  

This project explores the **World Happiness Report 2024** dataset, aiming to analyze global well-being levels, regional disparities, and the key drivers of happiness.  
It is part of my Data Analytics & Data Science portfolio.  

---

## Objectives  
- Explore the **distribution** of happiness scores.  
- Compare **regional differences** in happiness.  
- Identify the **factors most associated** with higher happiness.  
- Provide clear, visual insights into global well-being patterns.  

---

## Dataset Summary  
- Source: Kaggle — *World Happiness Report (2015–2024)*, filtered to 2024.  
- Scope: **140 countries**, **10 variables**.  
- Key columns:  
  - *Ladder Score* (Happiness Index, 0–10)  
  - *GDP per Capita*  
  - *Social Support*  
  - *Healthy Life Expectancy*  
  - *Freedom to Make Life Choices*  
  - *Generosity*  
  - *Perceptions of Corruption*  
  - *Regional Indicator* & *Country*  

---

## Data Cleaning & Preparation  
- Checked for **missing values** → none found.  
- Checked for **duplicates** → none found.  
- Converted *Regional Indicator* to **categorical type** for efficiency.  
- Standardized column names to lowercase with underscores.  
- Created **Ladder Score Category** with 5 qualitative levels:  
  - Very Low | Low | Medium | High | Very High  

---

## Exploratory Data Analysis (EDA)  
- **Distribution Analysis**: Ladder Score shows a **bimodal pattern** (peaks near 4.5 and 6.0).  
- **Regional Comparisons**:  
  - *Western Europe & North America* → consistently high.  
  - *South Asia & Sub-Saharan Africa* → lowest scores.  
  - *Middle East & North Africa* → greatest internal inequality.  
- **Correlation Heatmap**:  
  - Strongest correlations: Healthy Life Expectancy (0.81), GDP per Capita (0.77), Social Support (0.76).  
  - Weakest correlation: Generosity (0.13).  
- **Scatterplot GDP vs Ladder Score**: clear upward trend by region.  

---

## Tools & Methods  
- **Python** (pandas, numpy) → data preparation.  
- **matplotlib, seaborn** → visualization.  
- **Jupyter Notebook** → development environment.  

---

## Summary / Visualizations  
The notebook includes:  
- Histograms of happiness scores.  
- Boxplots & regional averages.  
- Correlation heatmap of all factors.  
- Scatterplot (GDP vs Ladder Score, colored by region).  

---

## Key Insights  
- Happiness is unevenly distributed worldwide, with clear **regional clustering**.  
- Health, economic, and social factors are **core drivers** of happiness.  
- Generosity and corruption perceptions show **weak explanatory power**.  
- No country reached a *Very High* happiness score (≥8).  

---

## Learnings & Reflection  
- Reinforced the importance of **data cleaning** and **consistent column naming**.  
- Improved efficiency by using **categorical optimization**.  
- Practiced **EDA storytelling** through structured visualizations.  
- Learned that strong **correlations across social and economic factors** explain much of the happiness variance.  

---

## License  
This project is for **educational and portfolio purposes**.  
Dataset belongs to the original source (*World Happiness Report* via Kaggle).  