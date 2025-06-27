# Week_2_Carbon_Emission

# 🌍 Climate and Emissions Data Analysis

This repository contains a Python script for **exploratory data analysis (EDA)** and visualization on a cleaned climate dataset (`data_cleaned.csv`). The analysis focuses on understanding the relationships between economic indicators, energy consumption, population, and CO₂ emissions across countries and years.

---

## 📁 Files

- `data_cleaned.csv` – cleaned dataset (not included in repo, add it manually)
- `analysis.py` or `analysis.ipynb` – script or notebook containing the full code

---

## ✨ Features

✔️ Display dataset shape, data types, and descriptive statistics  
✔️ Calculate yearly global average CO₂ emissions per capita  
✔️ Plot CO₂ per capita trends over time  
✔️ Visualize total CO₂ emissions against population  
✔️ Create total energy use feature  
✔️ Plot correlation heatmap among features  
✔️ Calculate Variance Inflation Factor (VIF) for multicollinearity check  
✔️ Compare CO₂ per capita trends across selected countries  
✔️ Generate pair plots for multiple features and countries  
✔️ Create a 4D scatter plot to visualize complex feature relationships

---

## 🛠️ Libraries Used

Install dependencies using:

```bash
pip install numpy pandas seaborn matplotlib statsmodels
